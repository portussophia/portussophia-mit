# PortusSophia™ Research Node (MIT Academic Node)

**Domain:** `mit.portussophia.com`
**Purpose:** Academic / research / institutional review content
**Tone:** Formal, neutral, research-focused (no personal narrative)

---

## Repository Structure

```
/
├── _config.yml           # Jekyll config for GitHub Pages
├── index.md              # Landing page (research overview)
├── golden-trace.md       # Golden Trace ledger overview + example entries
├── methods.md            # Governance workflows, witness cycles, integrity sealing
├── postulates.md         # PortusNexus™ postulates (N₁–N₇)
├── governance.md         # Steward roles, boundaries, checks-and-balances
└── README.md             # This file
```

---

## Deployment Instructions

### Step 1: Create GitHub Repository

Create new repository:
- **Name:** `portussophia-mit` (or similar)
- **Organization:** `portussophia`
- **Visibility:** Public

### Step 2: Push Content

```powershell
# From this directory (site-public/mit-node/)
git init
git add .
git commit -m "Initial commit: MIT academic node bootstrap"
git branch -M main
git remote add origin https://github.com/portussophia/portussophia-mit.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

In repository settings:
1. Navigate to **Settings → Pages**
2. Set **Source:** Deploy from branch `main` → `/ (root)`
3. Set **Custom domain:** `mit.portussophia.com`
4. Click **Save**
5. Wait ~5 minutes for GitHub to generate SSL certificate

### Step 4: Configure Cloudflare DNS

In Cloudflare dashboard for `portussophia.com` zone:

1. Navigate to **DNS**
2. Add or update record:
   - **Type:** CNAME
   - **Name:** `mit`
   - **Target:** `portussophia.github.io` (or your org Pages host)
   - **TTL:** Auto
   - **Proxy:** DNS only (gray cloud) — for initial debugging
3. Delete any conflicting A records for `mit` subdomain

### Step 5: Configure Cloudflare SSL/TLS

In Cloudflare dashboard:
1. Navigate to **SSL/TLS → Overview**
2. Set **Mode:** Full (not Flexible)
3. Navigate to **SSL/TLS → Edge Certificates**
4. Ensure **Always Use HTTPS:** ✅ On
5. Ensure **Minimum TLS Version:** 1.2

### Step 6: Verify Deployment

```powershell
# Test DNS propagation
nslookup mit.portussophia.com

# Expected: CNAME → portussophia.github.io → A records

# Test HTTP response (wait 5-10 minutes for propagation)
curl -I https://mit.portussophia.com

# Expected: 200 OK
```

---

## Content Guidelines

**Audience:** Academic, institutional, external review
**Tone:** Formal, neutral, research-focused
**Restrictions:**
- No personal narrative
- No "pitch" or marketing language
- No unverified claims
- Citations and references required where applicable

**What Belongs Here:**
- Governance architecture documentation
- Integrity ledger (Golden Trace) overview
- Witness cycle methodology
- Postulates and structural constraints
- Formal proofs and mathematical models (future)
- Peer review artifacts (future)

**What Does NOT Belong Here:**
- Personal stories or narrative arcs
- Motivational content
- Unverified philosophical speculation
- Marketing or promotional material

---

## Maintenance

**Owner:** PeterGate (Governance Steward)
**Content Steward:** Sara Harmonia (tone/language only)
**Approval Authority:** Founder (all content changes require approval)

**Update Process:**
1. Draft content changes locally
2. Submit for LOGOS structural review (if canonical)
3. Submit for DRACO risk review (if canonical)
4. Obtain Founder approval
5. Commit and push to `main` branch
6. Verify deployment at `mit.portussophia.com`

---

## Governance Compliance

**Classification:** Public (CUI-Eligible Draft)
**Distribution:** Unlimited (Subject to Future Reclassification)
**Integrity:** All canonical content must be sealed via Golden Trace ledger
**Trademarks:** All PortusSophia™ trademark entities must include ™ symbol
**Controlled Lexical Element:** *"Here and Now!"* (if referenced, must be exact format)

---

## Status

**Node Status:** Bootstrap Phase (Pending Deployment)
**Last Updated:** 2025-12-04
**Next Actions:**
1. Create GitHub repository `portussophia-mit`
2. Push content from `site-public/mit-node/`
3. Enable GitHub Pages with custom domain `mit.portussophia.com`
4. Configure Cloudflare DNS (CNAME: `mit` → `portussophia.github.io`)
5. Configure Cloudflare SSL/TLS (Mode: Full)
6. Verify deployment

---

**PortusSophia™** — Governance-first architecture, preserved in *"Here and Now!"*

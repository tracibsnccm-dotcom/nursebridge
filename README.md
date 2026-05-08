# NurseBridge™
### Nursing Student Retention & Readiness Platform
**nursebridgeedu.com**

---

## Repository Structure

```
nursebridge/
├── public/
│   └── index.html              # Main demo site (nursebridgeedu.com)
├── emails/
│   ├── nursebridge-email-sequence-01-intro.html       # The First Brick
│   ├── nursebridge-email-sequence-02-life.html        # Life Doesn't Stop
│   ├── nursebridge-email-sequence-03-language.html    # Giving Language
│   ├── nursebridge-email-sequence-04-burnout.html     # Burnout / FIRE→ASH™
│   ├── nursebridge-email-sequence-05-stress.html      # Stress vs. Anxiety
│   ├── nursebridge-email-sequence-06-attrition.html   # Attrition & Retention
│   └── nursebridge-email-sequence-07-platform.html    # Platform Overview
├── docs/
└── README.md
```

---

## Demo Site

**File:** `public/index.html`
**Deploys to:** `nursebridgeedu.com`

The demo site is a single self-contained HTML file. No build step required.
Deploy via Vercel, Netlify, or GitHub Pages by pointing the publish directory to `/public`.

### Embedded Interactive Tools
- **FIRE → ASH™** — Burnout Recognition Framework (Spark → Smoke → Fire → Ash)
- **Stress or Anxiety Check-In™** — 3-tab: Stress Checklist · Anxiety Scale · Journal

### Brand Colors
| Role | Name | Hex |
|---|---|---|
| Primary | Deep Teal | `#1a6b72` |
| Secondary | Soft Sage | `#6b9e82` |
| Accent | Warm Coral | `#d96b52` |
| Background | Warm Cream | `#faf6f0` |
| Text | Soft Charcoal | `#2c3e4a` |

---

## Email Sequence

7-email automation sequence targeting nursing program administrators and faculty.
All emails are self-contained HTML files, table-based, email-client safe.

| # | File | Theme |
|---|---|---|
| 01 | `nursebridge-email-sequence-01-intro.html` | The First Brick |
| 02 | `nursebridge-email-sequence-02-life.html` | Nursing school does not happen separately from life |
| 03 | `nursebridge-email-sequence-03-language.html` | Giving Language to the Experience |
| 04 | `nursebridge-email-sequence-04-burnout.html` | Burnout Rarely Happens All at Once |
| 05 | `nursebridge-email-sequence-05-stress.html` | Stress and Anxiety Are Not the Same |
| 06 | `nursebridge-email-sequence-06-attrition.html` | Attrition & Retention Data |
| 07 | `nursebridge-email-sequence-07-platform.html` | Platform Overview — Proactive, Not Reactive |

**CTA across all emails:** Explore the Demo → nursebridgeedu.com
**Audience:** Nursing program administrators and faculty

---

## Deployment

### Recommended: Vercel (fastest)
1. Push this repo to GitHub
2. Connect repo to Vercel at vercel.com
3. Set **Root Directory** to `public`
4. Add custom domain: `nursebridgeedu.com`
5. Deploy — live in ~60 seconds

### Alternative: Netlify
1. Push to GitHub
2. Connect at netlify.com
3. Build directory: `public`
4. Add custom domain

### Alternative: GitHub Pages
1. Go to repo Settings → Pages
2. Source: Deploy from branch `main`, folder `/public`
3. Add custom domain in Pages settings

---

## Domain Setup (nursebridgeedu.com)

After deploying, point your domain registrar DNS to your host:

**Vercel:**
```
A     @     76.76.21.21
CNAME www   cname.vercel-dns.com
```

**Netlify:**
```
A     @     75.2.60.5
CNAME www   [your-site].netlify.app
```

---

© 2025 NurseBridge™. All rights reserved.
Contents are proprietary. nursebridgeedu.com

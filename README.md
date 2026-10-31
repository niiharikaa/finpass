# FinPass

Clickable prototype of FinPass, a user-controlled Financial Passport for multi-source earners in Singapore.
FNCE6082 Digital Transformation of Financial Services · Group 7: Ankur Malik, Atharva Suhas Kulange, Janhavi Bilgaye, Niharika Singavajhala, Xu Xiuying.

**Version 2**

- **Applicant app:** log in, connect income sources, see the five signals, share with a lender, revoke access.
- **Lender credit desk:** review applications, apply a debt-service rule, approve or decline.
- Use the **Demo** switch (bottom right) to move between Arjun and Lender X. The ↺ button resets the demo.

All people, lenders, institutions and figures are illustrative. No real accounts or Singpass connection are used.
The passport cover uses an original FinPass emblem, not the Singapore state arms.

## What's new in version 2

- New first page: one centred layout on a single background, with the FinPass passport cover above the headline.
- Passport cover redesigned in brick red and cream, with an original emblem (shield, check mark, laurels, "Financial Identity" ribbon). It also appears on the My passport page and as a watermark on the home dashboard.
- The QR login step now sits in a centred card on the same background.
- Fixed: the small passport cover on the My passport page was missing its emblem.
- Fixed: icons inside the coloured circles showed grey instead of white.

## Demo flow

1. Log in with the simulated Singpass QR.
2. On Home, click **Review request**, choose which signals to share and for how long, then share.
3. Switch to **Lender X**, open Arjun's application (debt service 38%, within the 45% limit) and approve it.
4. Switch back to **Arjun** to see the approval notification, then revoke access.

## Run locally

Open `index.html` in a browser. There is no build step.

## Deploy

It is a single static file, so Vercel serves it with no configuration.

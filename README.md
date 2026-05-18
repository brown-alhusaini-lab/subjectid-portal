# Subject ID Portal

A lightweight landing page for the **Alhusaini Lab** (Brown University) MRI subject enrollment workflow. 


**For internal lab use only.**

## What it does

- Displays a short “redirecting” message with Alhusaini Lab / Brown branding.
- Automatically redirects after 2 seconds to the MRI enrollment portal (Google Apps Script, hosted on Brown’s Google Workspace domain).
- Provides a manual link if the redirect does not fire.

You must sign in with your **Brown Google account** to use the enrollment portal.

## Project structure

```
subjectid-portal/
└── index.html    # Static landing page (HTML + inline CSS)
```


## Deployment


The enrollment app itself lives in **Google Apps Script** on `script.google.com/a/macros/brown.edu`. To change where users are sent, update the redirect URL in `index.html`:


## License & access

This portal is for Alhusaini Lab research operations at Brown University. Do not redistribute enrollment links or subject data outside approved lab channels.

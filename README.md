
# Bringing Your Tech to Life – Ticket System

## ✅ Overview

This project is a complete, customizable ticket intake system for computer repair shops, built with:

- Google Apps Script (backend)
- Google Sheets (data store)
- Google Drive (attachments)
- HTML + JavaScript frontend (host anywhere)

## 🌐 Live Frontend Deployment

To deploy your form:
1. Upload `index.html` to your web host or GitHub Pages.
2. Ensure your domain is registered in your reCAPTCHA settings and Apps Script deployment.

## 🧠 Backend Setup

Your live Apps Script URL:
```
https://script.google.com/macros/s/AKfycbxKUu4LglbgMw2biHLvi9tNtfNF4m00J2uFGczdM53sQHKrxTdmkLFVgQNh5fSKltfs/exec
```

1. Deploy `Ticket-SubmissionFromWebsite.gs` in Google Apps Script with "Anyone" access.
2. Connect to your Google Sheet named `Tickets` with sheets:
   - Active Tickets
   - Archived Tickets
   - SpamLog

3. Make sure your Constants.gs file has the correct:
   - Spreadsheet ID
   - Folder ID for Attachments and GeneratedTickets
   - reCAPTCHA Secret Key
   - Support/NoReply email addresses

## ✅ Deployment Domains
Ensure these domains are listed in both:
- reCAPTCHA console
- Apps Script OAuth Consent Screen

```
bringingyourtechtolife.com
www.bringingyourtechtolife.com
www-bringingyourtechtolife-com.filesusr.com
byt2l.github.io
www.byt2l.github.io
```

## ✅ Google Workspace Email Roles
- `support@bringingyourtechtolife.com` — Sends client emails
- `noreply@bringingyourtechtolife.com` — Sends system notifications (no reply expected)

## ✅ reCAPTCHA

Current site key used:  
`6Lc5-YIrAAAAAApN80HxqROf1j9Gy-wZLMKGjMag`

Backend uses server-side validation.

## 🔐 Licensing

Feel free to use and resell this solution with your branding.

---

📣 Questions? You know where to find me.

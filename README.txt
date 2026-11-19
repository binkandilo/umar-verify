UMAR VERIFY — starter website

Included:
- index.html: responsive blue-and-white landing page and account UI preview.
- This is a FRONT-END DEMO only. Registration, login, wallet, payments, and NIN/BVN checks are not active.

To preview:
1. Extract the ZIP.
2. Open index.html in Chrome on your phone or computer.

To publish free:
1. Create a GitHub account.
2. Create a public repository named umar-verify.
3. Upload index.html.
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. GitHub will provide the public website address.

Before accepting real users:
- Connect secure authentication and database (for example, Supabase).
- Use only an authorised NIN/BVN verification provider and its official API.
- Keep secret API keys on a server, never in index.html.
- Add consent, privacy notice, role-based admin access, audit logs and payment-provider integration.
- Do not collect/store OTPs or credentials for other services.

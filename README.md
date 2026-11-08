# Projomia website

Local source for the public pages. This folder is a separate repository from the Projomia application.

**Not published.** https://projomia.com is not being served from this folder yet. Do not treat the intended URLs as live.

Intended addresses after the owner publishes:

- https://projomia.com
- https://projomia.com/privacy/
- https://projomia.com/support/

## What was found on the domain

On 8 November 2026 the public nameservers answered as Cloudflare:

- armando.ns.cloudflare.com
- malavika.ns.cloudflare.com

A, AAAA, MX, TXT, and www lookups from this network timed out, so the current address, mail, and verification records were **not** read. Do not change DNS from this note alone.

## Publish later, only with owner authorization

1. Create a **public** GitHub repository for this folder when the owner asks. GitHub Pages on a custom domain requires a repository GitHub can serve. This task does not create that remote.
2. Enable GitHub Pages from the repository root (main branch, `/`).
3. The `CNAME` file already contains `projomia.com`.
4. In the Cloudflare zone, **export the current records first**. Keep every MX, TXT (SPF, DKIM, DMARC), and any existing website or verification record that is still in use.
5. For the apex domain, add only the GitHub Pages addresses if they are not already present. GitHub’s current Pages addresses are:
   - A: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - AAAA: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
6. Leave those records DNS-only (not proxied) until GitHub has issued the certificate. Proxying through Cloudflare before that can block certificate checks.
7. If `www` is used, a CNAME to the GitHub Pages host is enough. Do not replace it if it already points somewhere the owner still needs.
8. After HTTPS works, open `/`, `/privacy/`, and `/support/` and confirm the links. Only then add the privacy URL inside the app.

No analytics, cookies, backend, or form is included. The support page has no email address because none was supplied.

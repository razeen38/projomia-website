# Projomia public website

Published with GitHub Pages from `main`, repository root, at https://projomia.com/.

Current published design (12 November 2026): interactive **Project Pulse** homepage — attention board by role, blind-spot diagnosis, cost-of-blocker calculator, sample briefing, privacy-by-design, and email access request. No App Store download yet.

## Live pages

- Homepage: https://projomia.com/
- Privacy: https://projomia.com/privacy/
- Support: https://projomia.com/support/
- Project Pulse (full): https://projomia.com/pulse.html
- Related interactive pages also live: `try.html`, `briefing.html`, `clarity.html`, `morning.html`, `decision-lab.html`, `your-briefing.html`
- Public contact approved by the Owner: raazeen@gmail.com
- Prepared App Store metadata: [app-store/listing.md](app-store/listing.md)

## Verified 8 November 2026 (core site)

Privacy and Support returned HTTP 200 in Chrome. HTTP and www requests redirect to canonical HTTPS. Chrome reports a valid Let's Encrypt certificate for projomia.com through 6 February 2027. GitHub Pages reports DNS check successful and Enforce HTTPS enabled.

Google public DNS returned all four GitHub Pages A records, all four AAAA records, and the www CNAME to razeen38.github.io. Delegation points to armando.ns.cloudflare.com and malavika.ns.cloudflare.com. Cloudflare shows these website records in DNS-only mode.

No analytics, advertising, cookies, backend, or support form is included. Optional app AI sharing, credentials, GPS in original photographs, retention and deletion are explained in the privacy policy.

The website repository contains website and listing content only. The private application source remains in its separate authoritative local workspace. App Store preparation is not an app upload or a public release.

## Superseded local design — do not resume as current

The local cinematic NORTHLINE homepage (layered phone hero, scroll-driven Capture→Act reels, launch-list dock) was an unpushed alternative. It is **superseded** by the published Project Pulse design on `main` / projomia.com.

Preserved only for history, not for publication:

- Branch `superseded/cinematic-northline-2026-11-11` — tip `a03167b`
- Branch `superseded/cinematic-northline-2026-11-11-wip` — unfinished interactive-try experiment on top of that design

Do not merge those branches into `main` unless the Owner explicitly chooses to replace the live Project Pulse site. Continue website work from published `main`.

## Remaining needs (outside this design deferral)

1. **Apple Developer Program** must be Active before App Store / TestFlight links can replace “Request access by email.”
2. **App Store Connect** listing still pending; prepared copy lives in `app-store/listing.md`.
3. Optional cleanup: several early interactive experiment pages remain public; decide which stay linked from the homepage versus retire.
4. Optional App Store gate: a public Terms page is not on the live site yet (Privacy and Support are).
5. Live product story uses illustrated fictional briefings, not the simulator NORTHLINE screenshot set from the superseded design.

## Maintenance

Keep the CNAME as projomia.com and preserve unrelated DNS records. Check live HTTPS pages after publication. Do not change DNS based only on a local resolver failure.

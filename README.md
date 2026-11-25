# AMC Georgetown location site: Design preview, not live

Ticket AMC-2026-11-25-georgetown-site-build. Georgetown is the same clinic as Georgetown East
(101 Cooperative Way #235). Built the same way as amc-copperascove-design-preview, including the
Nov 25 review changes: button hover, menu matching this location's live menu minus Home, scroll-away
header + sticky bottom CTA, Short Answer stock images on service and condition pages.

Full Georgetown location site on the AMC main design (Local Ember Alpine, AMC palette). Every URL on
the live georgetown.anthonychiro.com site (sitemap, menus, WordPress page and post lists) is kept at
the same slug so rankings can carry over, except /additional-offers/ and /ai-generated-content-disclaimer/,
removed on John's instruction (same as the Copperas Cove preview).

- noindex,nofollow on every page and robots.txt Disallow: /
- Forms off: disabled inputs and buttons, no form actions, no tracking or third-party scripts
- Service and condition pages use the Local Ember catalog (tools/bd-generator/catalog); acupuncture
  pages use services/acupuncture.json
- Blog: 2 posts rewritten as the pattern (auto-accident-tips, sciatic-leg-pain); remaining placeholders
  at their exact live URLs
- Legal pages are the Local Ember standards, at the live site's slugs
- Review layer: assets/review-comments.js adds a Local Ember reviewer toolbar. It is not part of the
  site design and must not ship to the live site.
- Not the live site. Not sent to the client.
- Do not expand the homepage-only folder in amc-main-design-preview/georgetown/.

# Technical SEO Rules for Codex HTML Changes

## 1. Purpose

These rules prevent Codex HTML modifications from damaging crawling, indexing, canonicalization, rendering, international targeting, performance, analytics, or buyer conversion. Technical SEO findings must be evidenced at URL or template level and separated from assumptions.

## 2. Pre-Change Baseline

Record before editing:

- Production and source URL
- HTTP status and redirect behavior
- Canonical, robots meta, X-Robots-Tag when available, and hreflang
- Title, description, H1, main content, internal links, and schema
- robots.txt and XML sitemap relationship
- Rendered desktop/mobile output
- GA4/GTM, pixels, consent, verification, and conversion events
- Current GSC index/inspection information when provided
- Field and lab performance evidence when available

Create a dated backup. URL, redirect, indexation, or deployment changes require explicit approval.

## 3. Crawlability Rules

- Priority pages must return the intended 200 response and be accessible without login, form submission, or internal search.
- Important navigation must use `<a href>` links.
- robots.txt must not unintentionally block pages or resources required for rendering.
- CSS and JavaScript necessary for primary content should be crawlable.
- Avoid crawl traps from filters, calendars, session IDs, infinite parameters, and internal search.
- Sitemaps support discovery but do not replace internal linking.
- Do not use robots.txt as a canonicalization or removal mechanism.

## 4. Indexability Rules

- Confirm the intended index state before changing robots directives.
- Default `index,follow` need not be declared.
- Check HTML robots meta and HTTP X-Robots-Tag for conflicts; the more restrictive applicable rule may control behavior.
- Do not ship an intended indexable page with `noindex` in source HTML and expect JavaScript to remove it reliably.
- Only valuable canonical pages should be indexable and listed in XML sitemaps.
- Staging, preview, internal search, cart/account, duplicate filters, and utility pages require an intentional control strategy.
- Removal decisions must consider backlinks, traffic, conversions, dependencies, and replacement paths.

## 5. Canonical and URL Rules

- Use one absolute HTTPS canonical in valid HTML `<head>`.
- Canonical pages should normally self-reference.
- Align canonical, redirects, sitemaps, internal links, hreflang, and structured-data URLs.
- Do not specify conflicting canonical targets through HTML, HTTP headers, JavaScript, or sitemaps.
- Link internally to canonical URLs, not redirects or parameter variants.
- Control protocol, host, case, trailing slash, pagination, sort, filter, tracking, print, and duplicate-file variants.
- Do not canonicalize materially different products, languages, or buyer intents to one page.
- Canonical is a signal, not a guarantee that Google will select it.

## 6. Redirect and Status Rules

- Use permanent server-side redirects for approved permanent URL moves.
- Redirect to the closest relevant replacement, not automatically to the homepage.
- Avoid chains, loops, mixed protocols, and redirecting URLs that should remain accessible.
- Preserve query parameters only when they remain necessary and safe.
- Return genuine 404/410 behavior for removed content with no replacement.
- Do not return a 200 page that only states “not found.”
- Keep temporary redirects temporary and documented.

## 7. JavaScript and Rendering Rules

- Ensure primary text, product data, links, metadata, and structured data appear in rendered HTML.
- Prefer server rendering or reliable pre-rendering for essential content when architecture permits.
- Use History API routing with unique URLs; do not rely on hash fragments for separate indexable views.
- Do not require scrolling, clicking, consent rejection, or form input to load essential content.
- Avoid contradictory source and rendered titles, canonicals, robots directives, or schema.
- Test with browser rendering and Google inspection tools when accessible.
- Provide useful error handling when APIs fail; do not render empty indexable shells.

## 8. Mobile and International Rules

- Mobile must contain equivalent primary content, metadata, internal links, images, and structured data.
- Do not block mobile resources or hide important specifications.
- Set a valid viewport and keep tables/forms usable on small screens.
- Each localized page must contain genuinely localized primary content.
- Hreflang targets must be canonical, indexable, reciprocal, and language/region correct.
- Include `x-default` only when a genuine default/fallback page exists.
- Do not use automatic redirects that prevent buyers or crawlers from selecting another locale.

## 9. Sitemap and Internal Discovery Rules

- Include only canonical, indexable, preferred URLs in XML sitemaps.
- Use absolute URLs and truthful meaningful `lastmod` values.
- Remove redirected, blocked, noindex, error, staging, and parameter URLs.
- Ensure every priority sitemap URL also has a logical internal link path.
- Keep category, product, solution, case, blog, FAQ, and language relationships discoverable.
- Validate sitemap status and declared location after URL/template changes.

## 10. Performance and Page Experience

- Use field data at the 75th percentile when available; use lab data to diagnose.
- Good Core Web Vitals targets: LCP ≤ 2.5 s, INP ≤ 200 ms, CLS ≤ 0.1.
- Identify the real LCP element and avoid lazy-loading it unnecessarily.
- Reserve media and embed dimensions to reduce layout shift.
- Reduce render-blocking, unused, duplicate, and excessive third-party code where safe.
- Optimize images, fonts, caching, compression, and critical resources.
- Preserve analytics, consent, forms, and required integrations while optimizing.
- Evaluate changes on representative page templates and mobile networks/devices.

## 11. Metadata and Head Integrity

- Keep `<head>` valid so Google can process later metadata.
- Maintain one descriptive title and intended meta description.
- Preserve charset, viewport, canonical, robots, hreflang, social metadata, schema, verification, consent, and analytics components.
- Do not place visible or invalid elements inside `<head>`.
- Avoid using JavaScript for stable metadata unless architecture requires it and testing confirms output.

## 12. Tracking Protection

- Inventory GA4, GTM, advertising pixels, consent mode, verification tags, form events, phone/email clicks, downloads, and custom events.
- Do not delete, duplicate, reorder, or alter tracking without understanding dependencies and receiving approval.
- Prevent duplicate page views and duplicate form-submit events.
- Test consent states and event parameters after changes.
- Never expose credentials or personal data in HTML or analytics payloads.

## 13. Validation Workflow

1. Compare pre-change and post-change status, metadata, directives, content, links, schema, and tracking.
2. Validate HTML and inspect source plus rendered DOM.
3. Crawl/test changed URLs and representative templates.
4. Test mobile/desktop layouts, forms, downloads, navigation, and errors.
5. Validate structured data and international annotations.
6. Run performance diagnostics and record material regressions.
7. Confirm analytics and conversion events.
8. Report Critical, High, Medium, and Low findings with evidence and owners/dependencies.

## 14. Codex Checklist

- [ ] Pre-change baseline and dated backup exist
- [ ] Intended crawl, index, canonical, and sitemap states are documented
- [ ] Priority content and links are present in rendered HTML
- [ ] Status codes and redirects are correct with no chain or loop
- [ ] Canonical signals agree across HTML, headers, sitemap, links, hreflang, and schema
- [ ] Robots.txt, meta robots, and X-Robots-Tag do not conflict unintentionally
- [ ] Only canonical indexable URLs appear in sitemaps
- [ ] Mobile content and functionality are equivalent
- [ ] Localized pages and hreflang pairs are valid where applicable
- [ ] JavaScript routing and failure states remain crawlable and usable
- [ ] Core Web Vitals risks and representative templates were tested
- [ ] HTML head, metadata, and structured data validate
- [ ] GA4/GTM, consent, verification, forms, and events are preserved and tested
- [ ] URL or indexation changes have explicit approval
- [ ] Evidence, limitations, validation, and monitoring steps are reported

## 15. Official References

- [Crawling and indexing overview](https://developers.google.com/search/docs/crawling-indexing)
- [Canonical URL guidance](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)
- [JavaScript SEO basics](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics)
- [Google-supported meta tags](https://developers.google.com/search/docs/crawling-indexing/special-tags)
- [Core Web Vitals](https://developers.google.com/search/docs/appearance/core-web-vitals)

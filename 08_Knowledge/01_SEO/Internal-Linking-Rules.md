# Internal Linking Rules for Industrial B2B Websites

## 1. Purpose

Internal links must help buyers move from discovery to technical validation and inquiry while helping Google discover and understand the site. Links are part of information architecture, not a keyword-distribution exercise.

## 2. Required Link Architecture

Preferred relationship:

`Homepage → Category/Solution Hub → Product/Solution/Application → Case/Guide/FAQ/Resource → Inquiry`

Every priority indexable page must have:

- At least one crawlable internal link from an indexable page
- A logical parent or hub relationship
- Breadcrumb navigation when the hierarchy supports it
- Contextual links to the next relevant buyer decision
- A clear conversion or contact path

Sitemaps support discovery but do not replace internal links.

## 3. Crawlable Link Standard

Pass only when:

- The link uses an HTML `<a>` element with an `href`
- The destination is a valid intended URL
- Google can access the source and destination pages
- The link is present in rendered HTML and not dependent on an unsupported user action
- The anchor or accessible name describes the destination
- Important links are not hidden, visually deceptive, or injected only after unnecessary interaction

Buttons used only for UI actions should remain buttons; navigation to another URL should use a link.

## 4. Page-Type Linking Rules

### Homepage

Must link to priority product categories, solution/application hubs, company trust pages, and contact/inquiry paths. Do not link every SKU from the homepage unless the catalog and buyer journey justify it.

### Product category

Must link to child products, useful selection guidance, relevant solutions/applications, and inquiry paths. Product listings require descriptive product names and stable destination URLs.

### Product detail

Must link to its parent category, relevant sibling products only when useful, applicable solutions, verified case studies, technical downloads, FAQs, and an inquiry route.

### Solution/application

Must link to products used in the solution, related industries or applications, supporting cases/resources, and project consultation or RFQ paths.

### Case study

Must link to the relevant solution, products, industry/application, and a suitable inquiry page. Links must not expose confidential or unverified customer information.

### Blog/guide/FAQ

Must link to the relevant pillar or hub, related supporting content, and the appropriate product/solution next step. Informational pages must not end without a buyer path.

### Contact/RFQ

Should be reachable from navigation and relevant commercial pages. Anchor and surrounding copy should explain the action, such as discussing an application or requesting a quote.

## 5. Anchor Text Rules

Use anchor text that is concise, natural, and specific enough to predict the destination.

Preferred:

- Product or category name
- Solution/application name
- A buyer task such as “compare enclosure materials”
- A resource description such as “download the technical datasheet”

Avoid:

- Repeated exact-match commercial anchors across large numbers of pages
- Generic anchors such as “click here” when context is unclear
- Keyword lists or unnatural sentence construction
- Anchors that promise specifications, certifications, pricing, or cases absent from the destination
- Different anchors that misleadingly imply different destinations

Image links require meaningful `alt` text when the image is the only accessible link name.

## 6. Link Placement and Relevance

- Place essential navigation and contextual links where buyers naturally need the next information
- Prefer links in relevant explanatory content over unrelated footer blocks
- Do not add a link solely because two pages share a keyword
- Link from high-level pages to detailed pages and back to the hub
- Link laterally only when the alternative genuinely supports comparison or the same application
- Avoid excessive repeated sitewide links that do not serve navigation
- Keep primary content links visible and usable on mobile

There is no fixed internal-link count. Judge sufficiency by discovery, hierarchy, relevance, buyer progression, and usability.

## 7. URL and Status Rules

- Link directly to the preferred canonical HTTPS URL
- Do not intentionally link through redirects
- Remove or repair internal links to 3xx chains, 4xx, 5xx, soft 404s, blocked pages, or unintended noindex pages
- Keep host, case, trailing slash, locale, and URL parameters consistent
- Do not link indexable navigation to staging, preview, internal search, or duplicate filter URLs
- URL changes, redirects, canonical changes, and large-scale link removals require impact review and approval

## 8. Multilingual and Regional Rules

- Link users to the equivalent language/region page when available
- Do not send users automatically to a different language without a usable choice
- Language switchers should use crawlable links
- Hreflang targets must be canonical, indexable, and reciprocal
- Do not link to a translated shell whose main content remains in another language
- Use natural terminology for each market rather than mechanically translating anchors

## 9. Orphan and Depth Audit

For each crawl, report:

- Indexable pages with zero internal inlinks
- Priority pages deeper than the intended hierarchy
- Pages linked only from sitemap, search, JavaScript interaction, or pagination gaps
- Pages with high internal links but low business value
- Dead-end pages with no onward buyer path
- Hubs missing child pages and child pages missing parents
- Broken links, redirect chains, inconsistent canonical targets, and blocked destinations

Do not declare a page non-orphan based only on XML sitemap inclusion.

## 10. Internal-Link Change Workflow

1. Confirm page types, hierarchy, and priority conversion paths.
2. Crawl or inventory current links and status codes.
3. Identify orphans, dead ends, broken paths, and competing internal targets.
4. Map each proposed link to a buyer need and destination intent.
5. Specify source URL, anchor/context, destination URL, and placement.
6. Check canonical, index, locale, and status alignment.
7. Implement without removing navigation, tracking, or functional integrations.
8. Re-crawl and test rendered desktop/mobile pages.
9. Monitor affected pages in GSC and GA4.

## 11. Codex Recommendation Format

Use this table:

| Source URL | Source page type | Placement/context | Recommended anchor | Destination URL | Buyer purpose | Issue/priority |
|---|---|---|---|---|---|---|

Also report:

- Orphan pages
- Broken or redirected internal links
- Canonical/index mismatches
- Missing parent/child relationships
- Cannibalization caused by competing anchors
- Conversion dead ends

## 12. Acceptance Checklist

- [ ] Every priority page has an indexable, crawlable inlink
- [ ] Parent, child, breadcrumb, and contextual relationships are logical
- [ ] Links move buyers toward useful technical or commercial decisions
- [ ] Anchors describe destinations naturally
- [ ] Links resolve directly to canonical HTTPS URLs
- [ ] No priority link ends at broken, blocked, noindex, or unintended duplicate URLs
- [ ] Product, solution, case, resource, and inquiry pages are connected appropriately
- [ ] Mobile users can see and use essential links
- [ ] Multilingual links and hreflang targets are consistent where applicable
- [ ] Re-crawl and functional validation are completed after changes

## 13. Official Google References

- [Make links crawlable](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Sitemaps overview](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)
- [Canonical URL guidance](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)

# Schema Markup Rules for Codex HTML Changes

## 1. Purpose

Structured data must describe visible, verified page content and help machines understand real entities and relationships. It must never be added solely to obtain a rich result or to introduce claims that the buyer cannot see on the page.

## 2. Mandatory Workflow

1. Identify the page type and visible primary entity.
2. Check Google’s current supported structured-data features and required properties.
3. Inventory existing JSON-LD, Microdata, RDFa, CMS output, and plugin output.
4. Confirm the authoritative source for every property.
5. Choose the smallest applicable schema graph.
6. Prefer JSON-LD unless the project requires another supported format.
7. Implement without duplicating or contradicting existing entities.
8. Validate syntax, Google eligibility, rendered output, and visible-content parity.
9. Record warnings, unsupported properties, and monitoring requirements.

Do not remove existing markup until its source, purpose, and consumers are understood.

## 3. General Implementation Rules

- Use `https://schema.org` vocabulary.
- Use stable absolute URLs and consistent `@id` values.
- Connect related nodes through `@id` rather than duplicating inconsistent objects.
- Keep names, URLs, images, descriptions, breadcrumbs, offers, and organization details consistent with visible content and canonical URLs.
- Include only properties supported by evidence.
- Do not mark hidden, misleading, irrelevant, expired, or user-inaccessible content.
- Structured data eligibility does not guarantee a Google rich result.
- Preserve valid custom schema used by other systems unless a conflict is proven.

## 4. Page-Type Mapping

Use schema only when the page and visible content qualify:

| Page | Common applicable types | Notes |
|---|---|---|
| Homepage | `Organization`, `WebSite` | Define business/site identity once and consistently |
| Category | `BreadcrumbList`, `ItemList` | Do not invent product data in list items |
| Product detail | `Product`, `BreadcrumbList` | Offers/reviews require real visible data and eligibility review |
| Solution/application | `Service` or appropriate entity, `BreadcrumbList` | Avoid treating a generic solution as a purchasable product |
| Case study/article | `Article` or subtype, `BreadcrumbList` | Author, date, image, and claims must be visible/verified |
| Blog article | `Article`/`BlogPosting`, `BreadcrumbList` | Use accurate author and publication/update dates |
| FAQ | `FAQPage` only when current Google and content rules permit | Visible company-authored Q&A must match markup |
| Contact/location | `Organization` or suitable local type | Use only verified public contact/location data |

Schema.org availability is not the same as Google rich-result support.

## 5. Product Rules

- Mark one clearly identifiable product or justified variant group per page.
- Match visible product name, description, image, model, SKU/MPN, brand, and category.
- Use `Offer` only when real price, currency, availability, condition, and URL data are visible and maintainable.
- Do not invent ratings, reviews, prices, stock, shipping, warranty, GTIN, or identifiers.
- Do not copy category-wide certification or company capability into a product property misleadingly.
- Variant implementation must reflect actual selectable products and Google’s current variant guidance.
- B2B “request quote” pages without visible price must not publish fake offer data.

## 6. Organization and Website Rules

- Maintain one authoritative identity with a stable homepage-based `@id`.
- Use the legal or approved public name, site name, logo, URL, contact points, and social profiles.
- Do not list directories, resellers, or unrelated profiles as `sameAs`.
- Contact and location data must match visible and maintained website information.
- `WebSite` site-name data belongs on the homepage and must match site branding.

## 7. Breadcrumb Rules

- Breadcrumbs must represent a normal user path, not merely mirror URL segments.
- Mark up the same hierarchy visible to users.
- Use ordered positions and canonical destination URLs.
- Keep labels concise and consistent with navigation.
- Do not include broken, noindex, redirected, or misleading breadcrumb destinations.

## 8. Article, Case, and FAQ Rules

- Article title, author, dates, image, and publisher must be visible or clearly supported.
- `dateModified` must reflect a meaningful content update, not automatic page rendering.
- Case results and customer identity must not be introduced only through schema.
- FAQ questions and answers must be visible, accurate, and identical in meaning to markup.
- Do not mark marketing claims as reviews or user-generated content.
- Do not add self-serving aggregate ratings without valid underlying reviews and policy eligibility.

## 9. Multilingual and Canonical Consistency

- Each language page uses schema values in that page’s language where appropriate.
- `url`, `@id`, breadcrumbs, and main entity must resolve to the page’s canonical version.
- Do not combine different regional offers or organization facts incorrectly.
- Hreflang and schema do different jobs; schema does not replace hreflang.

## 10. Validation Standard

Required checks:

- JSON parses without syntax errors
- Schema Markup Validator checks vocabulary structure
- Google Rich Results Test checks relevant Google-supported eligibility
- Rendered HTML contains the intended markup
- Required properties are present and warnings are reviewed
- Markup matches visible content and canonical URL
- No duplicate/conflicting entities are produced by templates or plugins
- Representative templates and variants are tested, not only one URL
- Search Console enhancement reports are monitored after release when applicable

## 11. Prohibited Actions

- Fabricating offers, reviews, ratings, stock, prices, identifiers, certifications, or results
- Marking content invisible to users
- Applying an ineligible page type only to seek a search feature
- Duplicating plugin/CMS schema without checking the existing graph
- Using a staging, parameter, redirected, or noncanonical URL as the main entity
- Treating validation warnings as errors automatically or ignoring real errors
- Promising rich-result display

## 12. Codex Checklist

- [ ] Page type and visible primary entity are confirmed
- [ ] Current Google feature eligibility was checked
- [ ] Existing schema sources and duplicates were inventoried
- [ ] Every property has a verified visible or authoritative source
- [ ] Type selection matches the page rather than the desired rich result
- [ ] Canonical URL, `@id`, language, entity names, and breadcrumbs agree
- [ ] Product offers, reviews, ratings, identifiers, and availability are not invented
- [ ] FAQ, article, case, and organization facts match visible content
- [ ] JSON syntax and schema vocabulary validate
- [ ] Relevant Google rich-result validation is completed
- [ ] Rendered output and template variants were checked
- [ ] Errors, warnings, assumptions, and monitoring plan are reported

## 13. Official References

- [Structured data general guidelines](https://developers.google.com/search/docs/appearance/structured-data/sd-policies)
- [Search Gallery and supported features](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)
- [Product structured data](https://developers.google.com/search/docs/appearance/structured-data/product)
- [Breadcrumb structured data](https://developers.google.com/search/docs/appearance/structured-data/breadcrumb)


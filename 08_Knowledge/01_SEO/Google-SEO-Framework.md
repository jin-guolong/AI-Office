# Google SEO Framework for Industrial B2B Websites

## 1. Purpose and Scope

This document defines the mandatory workflow Codex must use when auditing or planning Google SEO for an overseas industrial manufacturing website. It applies to homepages, product categories, product details, solution and application pages, case studies, blogs, FAQs, and technical resources.

SEO work must support qualified discovery, technical evaluation, supplier trust, and inquiry generation. Traffic without buyer relevance is not a sufficient objective.

## 2. Required Inputs

Before analysis, collect or confirm:

- Business model, target countries, target languages, and priority industries
- Product taxonomy, product specifications, applications, certifications, and differentiators
- Priority conversions: RFQ, contact form, email, phone, distributor inquiry, download, or sample request
- Current URLs, sitemap, robots.txt, CMS or framework, and analytics implementation
- GSC data: queries, pages, countries, devices, clicks, impressions, CTR, and average position
- GA4 data: landing pages, channels, engagement, events, key events, and lead quality where available
- Approved claims and evidence; never invent missing technical or commercial facts

If inputs are unavailable, explicitly label the analysis as limited and separate verified findings from hypotheses.

## 3. Business and Buyer Model

For every priority topic, define:

| Field | Required decision |
|---|---|
| Buyer | Engineer, procurement manager, project owner, distributor, OEM, or other role |
| Need | Product sourcing, specification comparison, problem solving, compliance, installation, or supplier validation |
| Stage | Discover, understand, compare, validate, specify, or inquire |
| Market | Country, language, standards, units, and industry conventions |
| Page type | Homepage, category, product, solution, application, case, blog, FAQ, or resource |
| Conversion | The next useful buyer action |

Reject a proposed topic when it has no credible connection to a real product, solution, buyer question, or business objective.

## 4. Search Intent and Page Mapping

Assign one primary intent and one preferred canonical page to each keyword or query cluster.

| Intent pattern | Preferred page type | Required value |
|---|---|---|
| Broad product family | Product category | Range, selection logic, variants, applications |
| Specific product or model | Product detail | Specifications, options, fit, proof, RFQ path |
| Problem, process, or industry need | Solution/application | Challenge, requirements, solution, products, evidence |
| Supplier/manufacturer sourcing | Homepage, category, or capability page | Manufacturing capability, QA, capacity, support, trust |
| Comparison or selection | Guide, category, or solution | Decision criteria, trade-offs, selection method |
| How-to or troubleshooting | Blog, guide, or FAQ | Accurate procedure, limits, safety, next step |
| Brand or company | Homepage/about/contact | Identity, capability, locations, contact path |

Do not create multiple pages for trivial keyword variations. Create a separate page only when the buyer intent, product entity, application, market, or required answer is materially different.

## 5. Site Architecture Standard

The preferred hierarchy is:

`Homepage → Product Category / Solution Hub → Product Detail / Solution / Application → Supporting Case / Blog / FAQ → Inquiry`

Mandatory checks:

- Every indexable priority page is reachable through crawlable HTML links
- Priority commercial pages are normally within three logical clicks of the homepage
- Breadcrumbs reflect the visible hierarchy
- Product categories link to included products and relevant solutions
- Product pages link back to their category and to relevant solutions, cases, resources, and contact paths
- Solution pages link to the products used and supporting evidence
- Informational content links to the appropriate commercial next step
- Orphan pages, dead ends, circular navigation, and uncontrolled faceted URLs are flagged

## 6. Page-Level Content Standard

Each priority page must have:

- One clear purpose and primary buyer intent
- A unique, descriptive title and H1 aligned with the page content
- A visible opening section that identifies the product, solution, or problem addressed
- Sufficient original information for the buyer to evaluate fit
- Technical details supported by approved source material
- Relevant applications, operating conditions, limits, options, or compatibility where applicable
- Evidence such as standards, certifications, testing, process controls, downloads, or verified cases
- Clear internal links and a context-appropriate CTA
- Unique metadata; no keyword lists or ranking language

Industrial product and solution pages should be treated as incomplete when buyers cannot determine suitability, differentiation, evidence, and the next inquiry step.

## 7. Technical SEO Gate

A page cannot pass SEO review until the following are checked:

### Crawl and index

- Returns the intended HTTP status
- Is not unintentionally blocked by robots.txt
- Has the intended robots meta or X-Robots-Tag directive
- Is accessible without login, internal search, or form submission when intended for Search
- Has crawlable `<a href>` internal links
- Important content and links are present in rendered HTML

### Canonical and URL

- Uses one preferred HTTPS URL
- Self-references canonical when appropriate
- Redirect, canonical, sitemap, and internal-link signals do not conflict
- Parameter, filter, print, protocol, host, trailing-slash, and case variants are controlled
- Only canonical, indexable URLs are included in XML sitemaps
- URL changes require approval and a redirect/migration plan

### Rendering and mobile

- Google can render primary content, navigation, links, and metadata
- Mobile and desktop provide equivalent primary content and structured data
- Essential content is not dependent on user interaction to load
- Layout, forms, tables, and downloads are usable on mobile
- Performance issues affecting Core Web Vitals are recorded with field data when available

### Markup

- HTML contains a valid title, meta description, canonical, language signals, and viewport settings as applicable
- Structured data matches visible content and uses an eligible type
- Hreflang is reciprocal and points to canonical, equivalent-language pages when used
- Tracking, consent, verification, and form integrations are preserved during changes

## 8. Authority and Trust Requirements

Codex must look for evidence that reduces industrial purchasing risk:

- Clear company identity and contact information
- Manufacturing or sourcing role stated accurately
- Quality process, certifications, standards, and audit evidence
- Engineering, customization, OEM/ODM, logistics, and after-sales capabilities where verified
- Datasheets, drawings, manuals, test reports, and declarations where approved
- Authorship or technical review for expert guidance where appropriate
- Case evidence with no fabricated customers, numbers, or outcomes

Generic claims such as “high quality,” “best,” or “leading manufacturer” do not count as evidence.

## 9. Measurement Framework

Use page type and buyer stage when interpreting results.

| Layer | Examples |
|---|---|
| Visibility | Valid indexed pages, impressions, query coverage, target-country visibility |
| Acquisition | Organic clicks, CTR, organic landing sessions |
| Engagement | Engaged sessions, scroll or download events, product/solution path progression |
| Conversion | RFQs, qualified forms, calls, emails, sample or distributor inquiries |
| Business quality | Qualified-lead rate, opportunity value, target-market fit when CRM data exists |

Every recommendation must specify a baseline, the page or page type affected, the expected observable change, and the review period. Do not promise rankings, traffic, or leads.

## 10. Audit Workflow and Priority

1. Confirm scope, markets, buyers, products, conversions, and data period.
2. Validate tracking and data limitations.
3. Inventory indexable URLs by page type and business value.
4. Check crawling, indexing, canonicalization, rendering, mobile, and performance risks.
5. Map GSC queries and topic clusters to preferred pages.
6. Review priority pages for intent fit, information completeness, trust, linking, and conversion.
7. Identify cannibalization, orphan pages, content gaps, and low-value indexable pages.
8. Compare relevant SERP competitors for structure and buyer value, without copying.
9. Prioritize findings and define implementation dependencies.
10. Define measurement and recheck dates.

Priority definitions:

- **Critical:** blocks crawling, indexing, tracking, conversion, or core functionality
- **High:** affects priority commercial pages or creates material intent/content gaps
- **Medium:** improves supporting coverage, usability, or internal distribution
- **Low:** optional refinement or controlled test

## 11. Deliverable Standard

Every Codex SEO analysis must output:

1. Objective, scope, market, and date range
2. Data sources and limitations
3. Executive summary
4. Findings with URL-level evidence
5. Prioritized actions with owner/dependency where known
6. Proposed page map or content structure when relevant
7. Validation criteria
8. Measurement plan and review timing

Use “observed,” “inferred,” and “requires validation” labels where evidence levels differ.

## 12. Pass/Fail Checklist

A strategy passes only when all are true:

- [ ] Priority products and solutions map to defined buyers, intents, and pages
- [ ] Each topic cluster has one preferred canonical landing page
- [ ] Priority pages are crawlable, indexable, canonical, and internally linked
- [ ] Page content provides technical and commercial decision value
- [ ] Claims are supported and missing facts are disclosed
- [ ] Informational content connects to relevant commercial pages
- [ ] Conversion paths and tracking are defined
- [ ] Actions are prioritized by business impact and implementation risk
- [ ] Baselines and review metrics are documented

## 13. Official Google References

- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Crawling and indexing overview](https://developers.google.com/search/docs/crawling-indexing)
- [Canonicalization](https://developers.google.com/search/docs/crawling-indexing/canonicalization)
- [Sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)
- [Google Search spam policies](https://developers.google.com/search/docs/essentials/spam-policies)


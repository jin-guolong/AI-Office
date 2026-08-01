# Internal Linking System for Industrial B2B Websites

> Codex internal execution rules. Use this file to analyze HTML internal links, design topic clusters, identify missing or competing relationships, and produce an implementation plan for industrial manufacturing websites.

## Scope

Apply to overseas English-language websites for industrial machinery, electrical equipment, industrial equipment, industrial components, Solutions, Applications, Case Studies, Blog/Knowledge, and technical resources.

Internal links must serve three purposes:

1. Help buyers navigate from discovery to selection, validation, and inquiry.
2. Help crawlers discover canonical pages through valid HTML links.
3. Clarify the relationship between company, product, application, solution, evidence, and knowledge topics.

Internal linking is not a fixed link-count or keyword-density tactic. Codex must not claim that a number of links or exact-match anchors guarantees rankings.

## Required Inputs

Before analysis, collect or derive:

- Site/domain and target language/market
- URL inventory and page-type classification
- Product taxonomy and priority categories/models
- Solution, Application, Case, Blog, FAQ, and resource relationships
- HTML source and rendered DOM where JavaScript may change links
- Status, redirects, canonical, robots, hreflang, sitemap, and index state
- Existing navigation, breadcrumbs, contextual links, cards, CTA, and footer links
- GSC query/page and GA4 buyer-path data when available
- Pages with conversions, backlinks, strategic business value, or approved retirement plans

URL, redirect, canonical, noindex, merge, removal, navigation, or large-scale internal-link changes require impact review and approval.

# Website Topic Cluster Model

## Pillar Page

### Definition

A Pillar Page is the primary canonical hub for a broad, commercially important product family, Solution family, Application domain, or major technical decision area.

Typical Pillars:

- Product Category
- Solution hub
- Application/industry hub
- Comprehensive selection guide only when informational intent cannot be owned by a commercial page

### Required role

A Pillar must:

- Own one broad and distinct primary intent
- Define the topic and buyer task
- Provide selection or navigation value beyond a link list
- Link to all priority child and Supporting Pages
- Receive relevant links back from child and supporting content
- Connect buyers to evidence and a conversion path
- Be crawlable, indexable, canonical, and maintained

### Required Pillar relationships

| Pillar type | Links to | Receives links from |
|---|---|---|
| Product Category | Models, subcategories, Applications, Solutions, guides, FAQ, RFQ | Homepage, Products, Applications, Blog, Case, related hubs |
| Solution hub | Industry/problem Solutions, Products, Applications, Cases, guides, consultation | Homepage, Solution pages, Products, Blog, Case |
| Application hub | Industry/process/environment pages, Products, Solutions, Cases | Homepage, Product, Solution, Blog, Case |
| Knowledge pillar | Supporting guides, commercial hub, resources, CTA | Homepage/resource hub, supporting articles, commercial pages where useful |

### Pillar failures

- Thin grid with no definition or selection logic
- Multiple Pillars compete for the same broad intent
- Blog Pillar replaces the correct commercial Category/Solution page
- Child pages do not link back
- Links point to redirects, duplicate parameters, blocked, or noncanonical URLs

## Supporting Page

### Definition

A Supporting Page answers a narrower buyer question, covers a specific entity, or provides evidence within a Pillar topic.

Examples:

- Product/model page
- Application page
- Specific Solution page
- Case Study
- Comparison/selection guide
- Technical article or FAQ
- Datasheet, drawing, manual, certificate, test, or capability evidence

### Required Supporting Page relationships

Every Supporting Page must normally link to:

1. Its primary Pillar or commercial hub
2. The most relevant Product, Category, Solution, or Application next step
3. Closely related supporting evidence/content when it advances the buyer task
4. A stage-appropriate conversion path

### Supporting Page rules

- The primary Pillar relationship must be visible through breadcrumb and/or contextual content.
- Supporting content must target a narrower task than the Pillar.
- Evidence must link to the Product/Solution claim it supports.
- PDFs and downloads should have an HTML context page when buyers need model, revision, or navigation information.
- A Supporting Page must not be an orphan or a buyer dead end.
- Do not link unrelated Products only to increase link count.

## Product Cluster

### Model

```text
Homepage
  → Product Category Pillar
      → Subcategory / Product Model
          → Application / Solution
              → Case / Technical Evidence / FAQ
                  → RFQ / Selection Support
```

Links should also return from Product models and Supporting Pages to the Category Pillar.

### Category-to-Product rules

- Link to every current priority Product through a crawlable product/model name or card.
- Use real classification and buyer selection logic.
- Include distinguishing link context such as type, rating, material, or Application when verified.
- Link directly to canonical HTTPS Product URLs.
- Keep pagination/load-more implementations capable of exposing priority Product links.
- Do not link unintentionally to discontinued, redirected, duplicate, filtered, or tracking-parameter URLs.

### Product-to-Category rules

- Link to the canonical parent Category through breadcrumb and/or contextual navigation.
- Use taxonomy consistent with H1, Title, schema, and navigation.
- Do not assign unrelated high-level Categories to a Product only to distribute weight.

### Product-to-Product rules

Link laterally only for a real buyer reason:

- Adjacent model/rating/size
- Alternative type or technology
- Compatible accessory or component
- Replacement or successor model
- Required upstream/downstream equipment

The source text must explain the relationship. Avoid unexplained “Related Products” grids.

### Product-to-evidence rules

- Product links to applicable datasheets, drawings, manuals, certifications, tests, Cases, Applications, and Solutions.
- Evidence links back to the exact Product or Product family it supports.
- Company-level certification must not be linked or labeled as if it certifies every Product.

## Solution Cluster

### Model

```text
Homepage
  → Solution Pillar
      → Industry / Process / Problem Solution
          → Products / Components / Services
              → Application / Case / Guide / FAQ
                  → Project Consultation
```

### Solution Pillar rules

- Organize Solution links by real industry, process, problem, system, or environment.
- Use buyer terminology rather than internal department names.
- Do not create many Solution pages that differ only by industry label.

### Solution Page rules

Every Solution page should link to:

- Parent Solution hub
- Product/Category pages used in the Solution
- Application pages providing operating context
- Case Studies and technical evidence
- Supporting Blog/FAQ/resources
- Project consultation or requirement-submission path

### Product–Solution reciprocal rules

- Product page explains where and why the Product fits the Solution/Application.
- Solution page explains what function the Product performs.
- Link only when fit is verified by specifications and operating conditions.
- Do not link every Product to every industry.

### Solution Cluster failures

- Solution page is only a Product list
- Product cards have no role explanation
- No Application, Case, evidence, project process, or consultation route exists
- Solution and Category compete for the same Product-family intent
- Unsupported outcome anchors imply guaranteed savings, safety, compliance, or performance

# Internal Link Direction

## Homepage →

The Homepage should link to:

- Priority Product Category Pillars
- Priority Solution and Application hubs
- Manufacturing capability and Quality pages
- Selected Case Studies and Knowledge resources
- Contact, RFQ, or consultation paths

Rules:

- Keep main navigation focused on business priorities.
- Do not link every Product model from Homepage unless catalog size and buyer behavior justify it.
- Do not use a large keyword footer as a substitute for architecture.
- Homepage links must use canonical destinations and accurate labels.

## Category →

Category pages should link to:

- Child subcategories and Product/model pages
- Selection, filter, and comparison support
- Relevant Applications and Solutions
- Applicable Case Studies, FAQs, downloads, and technical guides
- Product-selection support or Category-level RFQ

Rules:

- Broad Product intent remains on Category.
- Exact model intent moves to Product pages.
- Strategic subcategories use stable crawlable URLs; ordinary filter combinations require controlled index behavior.
- Product cards need descriptive names and useful selection context.

## Product →

Product pages should link to:

- Canonical parent Category
- Verified Applications and Solutions
- Related models, alternatives, accessories, and replacements where useful
- Product-specific Case Studies and evidence
- Datasheet, drawing, manual, certificate, test, FAQ, and technical guides
- Product-specific RFQ or engineering support

Rules:

- Preserve Product/model context in CTA, form, download, and event links.
- Do not link to technically incompatible Products.
- Do not send exact model buyers back only to Homepage.
- Direct all internal links to canonical Product URLs.

## Solution →

Solution pages should link to:

- Parent Solution/industry hub
- Products and Categories involved
- Applications and operating-context pages
- Cases, diagrams, standards, guides, FAQs, and resources
- Project process and consultation CTA

Rules:

- Explain Product roles in link context.
- Link to Product pages rather than duplicating complete specifications.
- Link to evidence near the claim it supports.
- Do not use Category anchors for Solution intent or vice versa.

## Blog →

Blog/Knowledge pages should link to:

- Their Pillar or topic hub
- The relevant Category, Product, Solution, or Application page
- Prerequisite or next-step Supporting Pages
- Relevant Case, FAQ, datasheet, manual, or technical resource
- Stage-appropriate CTA

Rules by buyer stage:

- Awareness → Category, Application, or Solution context
- Consideration → Comparison, Product options, evidence, and selection support
- Decision → Product details, documents, RFQ, or consultation

Do not force the first commercial link into the opening sentence if it disrupts the answer. Place it where the Product/Solution becomes relevant.

## Bidirectional relationship requirements

- Category ↔ Product
- Product ↔ verified Application/Solution
- Solution ↔ Product
- Application ↔ relevant Product/Solution
- Case ↔ Product/Solution/Application
- Blog/FAQ ↔ Pillar and commercial next step
- Evidence/resource ↔ Product/Solution it supports

Reciprocal linking is required only when the relationship is useful and verified—not mechanically for every page pair.

# Anchor Text Rules

## Precise Anchor Text

### Definition

Uses the exact natural name of the destination entity or page task.

Examples:

- `industrial rotary screw compressors`
- `AC-90 rotary screw air compressor`
- `electrical protection solution for chemical plants`
- `download the AC-90 technical datasheet`

### Use when

- Naming a Product, model, Category, Solution, Application, document, or clear buyer task
- The wording is grammatically natural in context
- Destination Title/H1 and visible content use the same entity terminology

### Rules

- Precise anchors are acceptable when they are the natural page name.
- Do not repeat the same commercial exact-match anchor mechanically across many pages.
- Do not insert exact anchors into irrelevant paragraphs.
- Model, rating, material, standard, and Application terms must be verified.

## Partial-Match Anchor Text

### Definition

Uses a descriptive phrase containing part of the destination topic plus meaningful context.

Examples:

- `compare available industrial compressor types`
- `review selection criteria for molded case circuit breakers`
- `see how the coupling performs in washdown equipment`
- `learn about our packaging-line integration approach`

### Use when

- Explaining a relationship, decision, comparison, or next step
- Avoiding repetitive exact anchors naturally
- Linking from Blog, Solution, Application, or Case context

### Rules

- Context must remain accurate and specific.
- Do not manufacture awkward synonyms solely to vary anchors.
- Partial match must not imply an attribute absent from the destination.

## Brand Anchor Text

### Definition

Uses the approved company, brand, or Product-brand name.

Examples:

- `Example Brand`
- `Example Brand product catalog`
- `contact Example Brand engineering`

### Use when

- Linking to Homepage, company, official catalog, brand hub, contact, or branded resource
- Brand identity is the buyer’s primary navigation need

### Rules

- Use the approved brand spelling and capitalization.
- Do not use another company’s brand to imply authorization, compatibility, distribution, or affiliation.
- Brand-only anchors are insufficient when the destination purpose is unclear; add context.

## Generic and CTA anchors

Avoid `click here`, `read more`, or `learn more` when users cannot predict the destination. If used in a component with a clear heading and accessible name, context must remain unambiguous.

Preferred CTA anchors:

- `request Product selection support`
- `submit your Application requirements`
- `discuss this Solution with an engineer`
- `view the complete Case Study`

## Anchor technical requirements

- Link navigation must use `<a href="...">`.
- Anchor text or accessible name must be available in rendered HTML.
- Image-only links require meaningful `alt` text.
- Avoid empty anchors, URL-only anchors, duplicate IDs, hidden links, and JavaScript-only navigation.
- Anchor must not promise price, stock, certification, compatibility, document, or outcome absent from the destination.

# Product Website Special Rules

## Model Page

### Required incoming links

- Parent Category
- Relevant Application/Solution
- Comparison/selection guide
- Case, FAQ, or technical resource when applicable
- Replacement/successor page where approved

### Required outgoing links

- Canonical parent Category
- Verified Applications/Solutions
- Related model/accessory/replacement with relationship explanation
- Product-specific documents and evidence
- RFQ or engineering support preserving model context

### Special checks

- Model anchor matches approved model name.
- Variant links do not create uncontrolled duplicate URLs.
- Discontinued model strategy considers replacements, links, conversions, backlinks, and approvals.
- Specifications and compatibility are not inferred through link labels.

## Category Page

### Required incoming links

- Homepage or parent Category
- Product/model pages through breadcrumb/context
- Relevant Applications, Solutions, Blog, Case, and capability pages

### Required outgoing links

- Child categories and Products
- Selection/comparison content
- Applications and Solutions
- Evidence, FAQ, downloads, and Category-level inquiry

### Special checks

- Category owns broad Product-family intent.
- Product cards link to canonical models.
- Filters and pagination expose strategic Products without creating uncontrolled indexable combinations.
- Category is not a thin grid.

## Application Page

### Required incoming links

- Homepage/Application hub
- Relevant Categories and Products
- Solutions, Cases, and Blog/Knowledge

### Required outgoing links

- Suitable Products and Categories
- Related Solution page when system/problem logic is needed
- Case evidence and technical resources
- Application consultation

### Special checks

- Application explains operating context, requirements, fit, and limits.
- Product suitability is verified.
- Application does not duplicate a Solution page or change only an industry name.

## Case Study Page

### Required incoming links

- Relevant Solution/Application
- Products used
- Case hub, Homepage selection, or Blog when useful

### Required outgoing links

- Products/configurations used
- Related Solution and Application
- Technical evidence/resource
- Similar Project CTA

### Special checks

- Links do not reveal confidential customer or project information.
- Product/configuration anchors match the actual Case.
- Case result anchors do not imply guaranteed future outcomes.
- Customer, media, quotation, and result evidence is approved.

## Resource and document page

- HTML context page identifies Product/model, document type, revision, language, and status.
- Product page links to the current approved file.
- File/resource links back to context when technically possible and useful.
- Superseded, confidential, broken, or wrong-model documents are flagged.

## Multilingual and regional pages

- Link to equivalent language/region pages through crawlable language selectors.
- Hreflang targets must be canonical, indexable, reciprocal, and equivalent.
- Do not automatically redirect users in a way that blocks another locale choice.
- Use natural terminology for each market; do not copy English anchors onto localized pages mechanically.

# HTML Internal Link Analysis Rules

## Link extraction

For every HTML page, Codex should extract from source and rendered DOM:

- Source URL
- Link element and DOM location
- Raw `href`
- Resolved absolute destination
- Anchor text
- Accessible name/linked image alt
- Link location type: navigation, breadcrumb, body, card, CTA, footer, pagination, filter, resource
- `rel`, `target`, `hreflang`, and relevant attributes
- Visibility and interaction dependency

## Destination validation

For each internal destination, check:

- Same-site/subdomain classification
- HTTP status and redirect chain
- Final URL
- Canonical target
- Robots/index state where available
- Language/region
- Page type and cluster role
- Presence in sitemap
- Whether source links directly to the preferred canonical HTTPS URL

## Page-level metrics

Calculate or report:

- Total internal outgoing links
- Unique internal destinations
- Internal inlink count by page
- Unique linking pages
- Anchor distribution
- Links by location type
- Click depth from Homepage/Pillar
- Orphan and dead-end status
- Broken, redirected, blocked, noindex, duplicate, parameter, and staging links
- Links to noncanonical URLs
- Missing parent, child, reciprocal, evidence, and CTA relationships

Counts are diagnostic. Do not approve or reject a page based on link count alone.

## Automated classifications

Classify each link as:

- Valid contextual
- Valid navigation/breadcrumb
- Valid CTA
- Duplicate but acceptable template link
- Broken/error
- Redirected
- Noncanonical destination
- Blocked/noindex destination
- Parameter/filter risk
- Staging/external-domain risk
- Empty/generic/misleading anchor
- Unverified Product/Application relationship
- Potential internal competition
- Requires manual review

## Internal competition detection

Flag potential competition when multiple indexable destinations:

- Receive the same precise or partial commercial anchors
- Have similar Titles, H1s, and content roles
- Target the same primary buyer task
- Alternate for the same valuable GSC queries
- Lack a distinct Product, model, Solution, Application, market, standard, or stage

Do not declare cannibalization from anchor overlap alone. Require page-role and intent review.

# Codex Checklist

## Crawlability and destination integrity

- [ ] Internal navigation uses crawlable `<a href>` links
- [ ] Source and rendered DOM links were compared where JavaScript is involved
- [ ] Internal links resolve directly to canonical HTTPS URLs
- [ ] Broken, redirect-chain, loop, blocked, noindex, staging, and unintended parameter links are reported
- [ ] Image-only links have meaningful accessible names
- [ ] Mobile users can see and use priority links

## Topic cluster model

- [ ] Every priority topic has one Pillar Page
- [ ] Pillar owns a broad distinct intent and provides selection/navigation value
- [ ] Supporting Pages target narrower tasks and link back to the Pillar
- [ ] Product and Solution Clusters connect buyers to evidence and conversion
- [ ] Priority pages are not orphaned or dead ends
- [ ] XML sitemap is not treated as a substitute for internal links

## Link direction

- [ ] Homepage links to priority Categories, Solutions, Applications, proof, knowledge, and contact
- [ ] Category links to child Products, selection, Applications, Solutions, and inquiry
- [ ] Product links to Category, verified Applications/Solutions, evidence, documents, and RFQ
- [ ] Solution links to Products, Applications, Cases, knowledge, and project consultation
- [ ] Blog links to Pillar, appropriate commercial page, supporting resources, and stage-based CTA
- [ ] Required bidirectional relationships exist where useful and verified

## Anchor text

- [ ] Precise anchors use accurate natural entity/page names
- [ ] Exact commercial anchors are not repeated mechanically at scale
- [ ] Partial-match anchors provide truthful decision context
- [ ] Brand anchors use approved identity and do not imply false affiliation
- [ ] Generic anchors have sufficient visible/accessibility context or are replaced
- [ ] No anchor promises unsupported price, stock, document, compatibility, certification, or outcome

## Product-site relationships

- [ ] Model pages connect to Category, verified Applications/Solutions, evidence, documents, and RFQ
- [ ] Category pages expose canonical Products and useful selection paths
- [ ] Application pages connect operating context to verified Products and Solutions
- [ ] Case pages connect actual configuration to Product/Solution/Application and similar-project CTA
- [ ] Document links identify correct Product/model and revision
- [ ] Multilingual links and hreflang relationships are valid where applicable

## Competition and approvals

- [ ] Competing anchors, Titles, H1s, GSC queries, and page roles were reviewed
- [ ] One preferred canonical page is assigned to each primary intent
- [ ] Broad Category anchors are not assigned mainly to one model
- [ ] Solution/Application anchors are not redirected to generic Product pages incorrectly
- [ ] URL, redirect, canonical, noindex, merge, removal, and navigation changes have approval

## Required Codex output

### Link-level table

| Source URL | Source page type | Link location | Anchor type | Anchor/accessibility text | Destination URL | Final/canonical URL | Destination page type | Cluster role | Status | Issue | Priority/action |
|---|---|---|---|---|---|---|---|---|---|---|---|
|  |  | Nav/Breadcrumb/Body/Card/CTA/Footer | Precise/Partial/Brand/Generic/Image |  |  |  |  | Pillar/Supporting/Product/Solution/Application/Case/Resource/CTA |  |  |  |

### Page/cluster summary

| Page/cluster | Pillar | Inlinks | Unique linking pages | Outgoing internal links | Click depth | Missing relationships | Competition risk | Recommended action |
|---|---|---:|---:|---:|---:|---|---|---|
|  |  |  |  |  |  |  |  |  |

Also report:

- Orphan and dead-end pages
- Broken, redirected, blocked, noindex, noncanonical, parameter, staging, and wrong-language links
- Missing Pillar/Supporting relationships
- Missing Category–Product, Product–Solution/Application, Case–Product/Solution, and Blog–commercial links
- Empty, generic, misleading, overrepeated, and unverified anchors
- Potential internal competition requiring manual intent review
- Approval requirements and post-change crawl/functional validation plan

## Official Google References

- [Crawlable links and link best practices](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Sitemaps overview](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)
- [Canonical URL guidance](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)

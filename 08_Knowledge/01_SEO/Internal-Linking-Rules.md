# Internal Linking Rules for Industrial B2B Websites

> Internal execution rules for Codex. Apply to overseas independent websites operated by industrial manufacturers.

## Operating Principle

Internal links must help industrial buyers move from problem discovery to product or solution evaluation, technical validation, and inquiry. They must also help search engines discover pages and understand site hierarchy, entities, and topic relationships.

Internal linking is not a method for distributing exact-match keywords mechanically. Every proposed link must have:

- A buyer purpose
- A clear source-page context
- A relevant destination
- A descriptive anchor or accessible name
- A canonical, crawlable destination URL
- A defined role in the topic or conversion path

XML sitemaps support discovery but do not replace internal links.

## Required Inputs

Before auditing or designing internal links, Codex must identify:

- Product taxonomy and priority product families
- Priority industries, applications, problems, and solutions
- Target countries, languages, and buyer roles
- Current URL inventory by page type
- Canonical, robots, status, redirect, and sitemap state
- Existing navigation, breadcrumbs, contextual links, footer links, and anchor text
- GSC query/page data and GA4 buyer paths when available
- Conversion pages and primary inquiry routes
- Pages with backlinks, conversions, or business importance

Do not recommend large-scale link removal, URL change, redirect, canonical, or indexation action without impact review and approval.

## 1. Website Topic Weight Model

### 1.1 Model objective

The site must concentrate navigation, contextual links, supporting evidence, and buyer progression around the manufacturer’s real commercial priorities. “Topic weight” is an internal planning concept, not a measurable Google score.

Codex must not invent numeric authority values or claim that a fixed number of internal links guarantees ranking.

### 1.2 Topic hierarchy

Preferred structure:

`Homepage → Pillar/Commercial Hub → Cluster Pages → Supporting Evidence → Inquiry`

Industrial B2B hierarchy normally includes:

`Homepage → Product Category → Product Detail → Application/Solution/Case/Technical Resource`

and:

`Homepage → Solution Hub → Solution/Application → Relevant Products → Case/Guide/FAQ → Project Inquiry`

### 1.3 Priority tiers

| Tier | Typical pages | Link treatment |
|---|---|---|
| Tier 1 | Homepage, priority product-category pillars, priority solution pillars | Main navigation and strong contextual support |
| Tier 2 | Product details, solution/application pages, capability pages | Linked from relevant Tier 1 pages and supporting content |
| Tier 3 | Case studies, technical guides, comparison pages, FAQs, resources | Support the appropriate pillar/product/solution and buyer stage |
| Utility | Contact, legal, account, search, filters, policies | Linked for function and trust; not treated as topical pillars |

Tier assignment must reflect business priority, buyer demand, conversion role, and content completeness—not only existing traffic.

### 1.4 Weight signals Codex must inspect

- Presence in primary and secondary navigation
- Breadcrumb hierarchy
- Number and quality of relevant internal inlinks
- Source-page relevance and business importance
- Anchor diversity and clarity
- Click depth from homepage or hub
- Links from product, solution, case, blog, FAQ, and resource pages
- Orphan, dead-end, or overlinked status
- Canonical consistency and direct status resolution
- Buyer progression and CTA paths

### 1.5 Required allocation rules

- Priority pillars must receive links from their homepage route, child pages, and relevant supporting content.
- Child pages must link back to their logical pillar.
- Supporting pages must link to the commercial page that owns the buyer’s next decision.
- Cross-cluster links are permitted only when products, applications, standards, or buyer tasks genuinely overlap.
- Sitewide footer links must not be used to manufacture topic relevance.
- Important pages should normally be reachable within three logical clicks, subject to catalog size and usability.

## 2. Pillar Page Rules

### 2.1 Definition

A Pillar Page is the primary hub for a commercially important product family, solution family, application domain, or technical decision area. It owns the broad intent and routes buyers to more specific pages.

Common Pillar Pages:

- Product category
- Solution hub
- Application/industry hub
- Comprehensive selection or technical guide when no commercial page can own the informational intent

### 2.2 Pillar acceptance criteria

A page can be treated as a pillar only when it:

- Has a distinct primary intent and canonical URL
- Defines the topic and buyer need clearly
- Links to all important child/cluster pages
- Provides comparison, selection, or navigation value beyond a link list
- Receives links back from child and supporting pages
- Connects to a meaningful conversion path
- Is crawlable, indexable, internally discoverable, and maintained

### 2.3 Required pillar links

A pillar should link to, where relevant:

- Child categories or product details
- Solution/application pages
- Comparison and selection guides
- Case studies and technical proof
- FAQs and resources
- Inquiry, quotation, or consultation route

### 2.4 Prohibited pillar patterns

- Thin hub containing only cards or tags
- Multiple pillars targeting the same broad intent
- A blog pillar competing with the correct category/solution page
- Links to every unrelated product or article
- Child links generated only by JavaScript without crawlable `<a href>` markup

## 3. Supporting Page Rules

### 3.1 Definition

A Supporting Page answers a narrower buyer question, provides evidence, or completes a decision step within a pillar topic.

Examples:

- Selection or comparison guide
- Technical explanation
- Installation or maintenance guide
- FAQ
- Case study
- Datasheet, drawing, manual, certificate, or test resource
- Capability page relevant to the cluster

### 3.2 Required supporting-page links

Every supporting page must normally link to:

1. Its primary pillar or hub
2. The most relevant product, category, or solution page
3. Closely related supporting content when it advances the buyer task
4. A stage-appropriate CTA or contact path

### 3.3 Supporting-page rules

- The link to the pillar must be contextually clear, not hidden only in breadcrumbs.
- Narrow content must not target the same primary intent as the pillar.
- Evidence pages must link to the product/solution whose claim they support.
- PDFs and downloads should have an HTML context page when buyers need explanation and navigation.
- A supporting page must not end with no onward path.
- Do not force commercial links into safety instructions where they interrupt critical understanding.

## 4. Product Cluster Rules

### 4.1 Product cluster model

`Product Category Pillar → Subcategory/Product Detail → Application/Solution → Case/Technical Support → RFQ`

### 4.2 Category-to-product links

Category pages must:

- Link to every current priority child product through crawlable product names or cards
- Group products by real buyer selection logic
- Include distinguishing attributes in link context
- Link to relevant selection guides and applications
- Avoid linking to discontinued, redirected, blocked, or duplicate variants unintentionally

### 4.3 Product-to-category links

Product pages must:

- Link to the canonical parent category through breadcrumb and/or contextual navigation
- Use the same product taxonomy as navigation and schema
- Avoid linking back to an unrelated high-level category solely for “authority”

### 4.4 Product-to-product links

Link products laterally only when the buyer may reasonably compare:

- Alternative type or technology
- Adjacent size/rating/model
- Compatible accessory or component
- Replacement/successor model
- Required upstream/downstream equipment

Explain the relationship. Avoid generic “Related Products” lists without selection context.

### 4.5 Product-to-solution and evidence links

- Product pages link to verified applications and solutions.
- Solution pages link back to each product’s function in the solution.
- Product claims link to applicable case, certificate, test, datasheet, drawing, or guide where available.
- Company-level certification must not be presented as product certification through link context.

### 4.6 Product cluster failure conditions

- Product orphaned from its category
- Category links through redirects or parameters instead of canonical URLs
- All products use identical vague anchors
- Product recommendations are unrelated or technically incompatible
- Model pages compete because variants lack a canonical/content strategy
- Product page has no RFQ or selection-support path

## 5. Solution Cluster Rules

### 5.1 Solution cluster model

`Solution Hub → Industry/Application/Problem Solution → Products/Components → Case/Technical Guide/FAQ → Project Inquiry`

### 5.2 Solution hub links

The hub must link to solution pages based on:

- Industry or process
- Operating problem
- System requirement
- Application environment
- Project or integration need

Labels must describe buyer problems or applications, not internal department names.

### 5.3 Solution-page links

Every solution page should link to:

- Parent solution/application hub
- Products and components used, with the role of each explained
- Relevant cases, diagrams, standards, guides, and FAQs
- Related solution only when requirements overlap meaningfully
- Project consultation or requirements-submission path

### 5.4 Product-to-solution reciprocity

Use reciprocal links when the relationship is verified:

- Product page: where and why the product fits the application
- Solution page: what function the product performs

Do not link every product to every industry. Application claims must be supported by product capability and operating conditions.

### 5.5 Solution cluster failure conditions

- Solution page is only a product list
- Many industry pages differ only by industry name
- Products are linked without explaining selection or system role
- Solution outcome is unsupported or guaranteed
- No case, technical proof, implementation information, or consultation path
- Solution and category pages compete for the same product-family intent

## 6. Blog Linking Strategy

### 6.1 Blog role

Blog and guide content must support awareness, consideration, validation, specification, implementation, maintenance, or sourcing tasks. It must connect informational discovery to the correct commercial and technical next step.

### 6.2 Required blog links

Each article must normally include:

- One link to its pillar/hub
- One link to the most relevant product/category/solution page
- Supporting links to related guides, FAQs, cases, or resources when useful
- One stage-appropriate CTA

There is no fixed link count. Use only links that improve understanding or buyer progression.

### 6.3 Link placement

- Add the first commercial/context link where the product or solution becomes relevant, not automatically in the opening sentence.
- Place selection-guide links near criteria or comparison sections.
- Place datasheet/manual/case links near the claim or task they support.
- Provide a clear next step in the conclusion.
- Avoid large unrelated “recommended article” blocks.

### 6.4 Blog-to-blog links

Link supporting articles when they represent the next or prerequisite buyer question. Do not form circular chains merely to increase link counts.

### 6.5 Blog-to-commercial boundary

- Awareness articles link to category, application, or solution context.
- Consideration articles link to comparison, product options, evidence, and selection support.
- Decision articles link to product details, technical resources, RFQ, or consultation.
- A blog ranking for strong commercial intent should support the preferred commercial page; if the commercial page is weak, improve it rather than forcing the blog to replace it.

## 7. Anchor Text Rules

### 7.1 Anchor standard

Anchor text must be concise, natural, and descriptive enough for a buyer to predict the destination.

Preferred anchor types:

- Product/category name: `industrial rotary screw compressors`
- Application/solution: `compressed air solution for food processing`
- Buyer task: `compare circuit breaker selection criteria`
- Technical resource: `download the AC-90 technical datasheet`
- Evidence: `review the washdown conveyor case study`
- Action: `submit your application requirements`

### 7.2 Anchor rules

- Use terminology consistent with the destination Title, H1, and visible content.
- Vary anchors naturally when context differs; do not manufacture synonyms.
- Exact-match anchors are permitted when they are the natural product or page name, but must not be repeated mechanically at scale.
- Generic anchors such as `click here`, `learn more`, or `read more` require enough surrounding context; prefer descriptive wording.
- Image links need meaningful alt text when the image is the only accessible link name.
- CTA anchors must describe the actual action and destination.

### 7.3 Prohibited anchors

- Keyword lists or hidden links
- Unsupported claims such as `best certified machine supplier`
- Product/standard/material anchors that do not match the destination
- Identical commercial anchors inserted across unrelated pages
- Misleading anchors that imply price, stock, download, certification, or compatibility absent from the destination

## 8. Internal Competition Prevention Rules

### 8.1 Competition indicators

Flag internal competition when two or more indexable pages:

- Target the same primary buyer intent
- Receive impressions for the same valuable query cluster
- Have similar Titles, H1s, introductions, and content structures
- Receive competing internal anchors from similar source pages
- Alternate in GSC performance without a clear page-role reason
- Lack a distinct product, model, application, solution, market, standard, or buyer task

### 8.2 Link-based prevention

- Choose one preferred page for each primary intent.
- Point relevant internal anchors consistently to that preferred page.
- Use supporting pages for narrower questions and link them to the preferred page.
- Keep category, product, solution, and blog roles distinct.
- Do not link a broad category phrase primarily to a product model.
- Do not link a solution phrase primarily to a generic product category when a complete solution page exists.
- Do not create navigation or footer links to duplicate/filter/parameter variants.

### 8.3 Resolution workflow

1. Verify that the pages actually serve the same intent.
2. Identify the preferred page using business role, content completeness, links, conversions, backlinks, and canonical suitability.
3. Decide whether to differentiate, consolidate, redirect, canonicalize, noindex, or retire.
4. Obtain approval for URL, redirect, canonical, indexation, or content-removal changes.
5. Update navigation, breadcrumbs, contextual links, sitemap, schema, and metadata consistently.
6. Re-crawl and monitor GSC/GA4 after implementation.

Do not declare competition based only on keyword overlap. Related pages may rank for similar terms while satisfying different buyer tasks.

## 9. Codex Checklist

### Architecture and priority

- [ ] Product taxonomy, solution hierarchy, buyer journey, and priority tiers are defined
- [ ] Every priority topic has one Pillar Page or commercial hub
- [ ] Pillars link to all relevant cluster pages and receive links back
- [ ] Important pages are reachable through logical crawlable paths
- [ ] XML sitemap is not treated as a substitute for internal links

### Pillar and supporting pages

- [ ] Pillar owns a broad distinct intent and provides selection/navigation value
- [ ] Supporting pages answer narrower tasks and link to the pillar
- [ ] Supporting evidence links to the product/solution it supports
- [ ] No supporting page is an orphan or buyer dead end

### Product cluster

- [ ] Categories link to canonical child products with useful context
- [ ] Products link to their correct parent category
- [ ] Product-to-product links represent real alternatives, accessories, or system relationships
- [ ] Product/application links are technically verified
- [ ] Product pages connect to evidence and RFQ/selection support

### Solution cluster

- [ ] Solution hub organizes real industries, applications, problems, or systems
- [ ] Every solution explains and links the role of relevant products
- [ ] Product pages link back to verified solutions where useful
- [ ] Solution pages connect to cases, guides, FAQs, resources, and project inquiry
- [ ] Solution and category pages do not compete for the same primary intent

### Blog strategy

- [ ] Every article links to its pillar and relevant commercial next step
- [ ] Blog links match Awareness, Consideration, or Decision stage
- [ ] Blog-to-blog links follow real prerequisite or next questions
- [ ] Link count is based on usefulness, not a fixed target

### Anchors and technical integrity

- [ ] Anchors are descriptive, natural, accurate, and accessible
- [ ] Exact-match anchors are not repeated mechanically at scale
- [ ] Links use crawlable `<a href>` markup
- [ ] Destinations resolve directly to canonical HTTPS URLs
- [ ] Broken, redirected, blocked, noindex, staging, and parameter destinations are repaired or flagged
- [ ] Mobile users can see and use essential links

### Competition and conversion

- [ ] Competing Titles, H1s, GSC queries, anchors, and page roles were reviewed
- [ ] One preferred page is assigned to each primary intent
- [ ] Any merge, redirect, canonical, noindex, or removal action has approval
- [ ] Every cluster provides a measurable buyer progression and conversion path

### Required Codex output

Use this implementation table:

| Source URL | Source page type | Cluster | Placement/context | Recommended anchor | Destination URL | Destination role | Buyer purpose | Technical status | Priority/action |
|---|---|---|---|---|---|---|---|---|---|
|  |  | Product/Solution/Blog |  |  |  | Pillar/Supporting/Product/Solution/Evidence/CTA |  |  |  |

Also report:

- Orphan pages
- Dead-end pages
- Missing parent/child and reciprocal relationships
- Broken links, redirects, canonical/index mismatches, and parameter links
- Overlinked low-value pages
- Competing anchors and suspected cannibalization
- Missing product, solution, evidence, and conversion paths
- Approval requirements and post-change validation plan

## Official Google References

- [Crawlable links and link best practices](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Sitemaps overview](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)
- [Canonical URL guidance](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)

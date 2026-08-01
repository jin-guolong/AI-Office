# Industrial B2B Product Category Page Standard

> Internal execution rules for Codex. Apply to overseas English-language product category pages for machinery, electrical equipment, industrial equipment, and related components.

## Operating Principle

A product category page is a commercial selection hub. It must help an industrial buyer understand the product family, distinguish available types, narrow options using real technical criteria, and reach a suitable product or assisted-selection path.

A category page must provide more value than a product grid. It owns broad product-family intent; individual product/model specifications belong on product detail pages.

## Required Inputs

Before analyzing, creating, or optimizing a category page, Codex must confirm:

- Approved category name and parent/child taxonomy
- Products, models, variants, status, and canonical URLs included in the category
- Target countries, English variant, industries, applications, and buyer roles
- Selection criteria used by engineering, procurement, and sales teams
- Verified product attributes, parameter ranges, standards, and compatibility
- Available filters, comparison data, downloads, and inquiry requirements
- Relevant Solution, Application, Case, Blog, FAQ, and resource pages
- Existing metadata, schema, navigation, tracking, forms, and technical dependencies

Do not infer specifications, range-wide capability, certification, compatibility, or product availability from incomplete source data.

## 1. Category Positioning

### Objective

The page must define:

- What product family it covers
- Which products/types are included
- Which buyer needs and applications it serves
- How buyers should distinguish and select options
- What technical or commercial next step is available

### Buyer roles

- Engineers: compare types, specifications, standards, interfaces, and operating fit
- Procurement teams: review range, supplier capability, quality evidence, documentation, and sourcing path
- Project owners/integrators: connect products to systems, applications, and solutions
- Distributors/OEMs: understand portfolio, variants, customization, supply, and support

### Search and page role

- Own broad product-family and category-level commercial intent.
- Route exact model intent to product detail pages.
- Route problem/system intent to Solution pages.
- Route environment/process intent to Application pages where dedicated context is required.
- Route detailed comparisons or procedures to guides when they exceed category scope.

### Positioning pass criteria

- [ ] Category is distinct from its parent, children, products, and solutions
- [ ] Included product scope is clear
- [ ] Buyer and primary selection task are defined
- [ ] Page has a measurable product-selection or inquiry objective
- [ ] Category name matches navigation, taxonomy, breadcrumb, and internal links

## 2. H1 Rules

### Objective

The H1 must identify the complete product family in terminology used by target industrial buyers.

### Recommended patterns

`[Product Category]`

`[Product Category] for [Primary Application]`

`[Verified Technology/Material] [Product Category]`

### Examples

- `Industrial Tube Bending Machines`
- `Molded Case Circuit Breakers for Power Distribution`
- `Stainless Steel Flexible Couplings`

Examples are structural only; all product and application claims require verification.

### Rules

- Use one clear H1.
- Match the primary category intent and remain consistent with Title and breadcrumb.
- Do not include every product subtype, rating, industry, country, or synonym.
- Do not use “manufacturer” unless it accurately describes the company and supports the intended query.
- Do not make a product-specific rating or certification appear category-wide.
- Supporting H2/H3 headings must organize selection, products, applications, advantages, FAQ, and CTA logically.

## 3. Hero Area

### Required components

- Breadcrumb
- H1
- Concise category definition
- Primary buyer value or selection context
- Primary CTA
- Optional secondary CTA
- Accurate category/product visual

### Hero content formula

`Product family → suitable needs/applications → meaningful range or capability → next selection action`

### Hero rules

- Explain the category in two or three useful sentences, not a generic company introduction.
- State verified category-level value such as available types, application scope, or selection support.
- Do not repeat homepage slogans.
- Use a visual representing the category rather than one misleading model unless labeled.
- Keep the product-list route and selection-support CTA visible.
- Optimize image loading and mobile layout.

### CTA examples

- View Product Range
- Compare Product Types
- Request Selection Support
- Discuss Your Requirements

## 4. Product List

### Product-card requirements

Each card should include, where applicable:

- Exact product/model name
- Product type or subtype
- Representative approved image
- Two to four distinguishing attributes
- Primary application or selection context
- Availability/status when maintained accurately
- Crawlable link to the canonical product URL
- Optional compare or shortlist action

### Product-list rules

- Include only products that belong to the category.
- Use consistent attribute labels and units.
- Explain differences; do not repeat identical generic copy.
- Link directly to canonical HTTPS product pages without redirects or tracking parameters.
- Preserve product context through compare, inquiry, and analytics actions.
- Product cards must remain usable by keyboard and on mobile.
- Pagination or load-more behavior must not prevent crawlable discovery of priority products.
- Handle discontinued and unavailable products intentionally; do not silently remove valuable URLs.

### Ordering options

Choose an ordering logic based on buyer needs:

- Product type
- Application
- Capacity/rating/size
- Technology
- Material or environment
- Standard/default versus custom
- Popularity or priority only when not misleading

Do not use arbitrary ordering that hides the selection logic.

## 5. Classification Logic

### Objective

Classification must reflect how buyers distinguish products, not the company’s internal department structure.

### Valid classification dimensions

#### Machinery

- Process or machine function
- Material/product handled
- Output/capacity
- Automation level
- Configuration or production-line position

#### Electrical equipment

- Protection, control, switching, distribution, or connection function
- Voltage/current/power class
- Pole, phase, breaking capacity, duty, or enclosure
- Standard or system compatibility

#### Industrial equipment/components

- Function and interface
- Material and manufacturing method
- Size, load, speed, pressure, or temperature range
- Environment, medium, sealing, or protection
- Standard, custom, replacement, or accessory role

### Classification rules

- Use one primary hierarchy and secondary facets where needed.
- Keep parent, child, and sibling categories mutually understandable.
- Avoid categories containing only one product unless a distinct intent and roadmap justify them.
- Avoid the same product appearing in unrelated categories without clear application logic.
- Do not create separate indexable categories for close synonyms or trivial attribute combinations.
- Document which category owns the canonical product-family intent.

## 6. Parameter Filtering

### Objective

Filters must help buyers narrow a large catalog using verified, decision-relevant parameters without creating uncontrolled duplicate URLs.

### Filter selection rules

Use only attributes that materially affect fit, such as:

- Product type/model family
- Capacity, output, size, rating, power, voltage, current, speed, load, pressure, or temperature
- Material, finish, sealing, protection, environment, or medium
- Standard, connection, interface, pole/phase, mounting, or configuration
- Application or industry when technically verified

### UX requirements

- Use consistent labels, units, ranges, and option names.
- Show active filters and provide a clear reset action.
- Display result count when reliable.
- Do not allow impossible or incompatible combinations without explanation.
- Preserve accessibility, keyboard use, focus, and mobile operation.
- Retain useful buyer context when a filtered product is opened.

### Technical SEO requirements

- Define whether filtered URLs are crawlable, indexable, canonicalized, or blocked based on real demand and unique value.
- Do not allow every parameter combination to become an indexable page.
- Use stable crawlable links for strategic subcategories; use controlled UI filters for the remaining facets.
- Keep canonical, robots, sitemap, internal links, and parameter handling consistent.
- Do not canonicalize a valuable distinct subcategory to a generic page without review.
- Test empty, single-result, multi-filter, reset, pagination, and no-JavaScript/failure states.

## 7. Comparison Function

### Objective

Comparison must enable buyers to evaluate equivalent products using consistent criteria.

### Required comparison fields

Depending on the category:

- Product/model identity
- Primary function/application
- Key specifications and units
- Materials and options
- Standards and ratings
- Dimensions/interfaces
- Operating environment and limitations
- Downloads and inquiry action

### Comparison rules

- Compare only products that buyers can reasonably evaluate together.
- Use equivalent attribute definitions, units, and conditions.
- Mark unavailable, optional, custom, and not-applicable values clearly.
- Do not convert missing data into zero, “No,” or a guessed value.
- Explain trade-offs rather than declaring a universal winner.
- Limit default comparison columns to a usable number and support mobile presentation.
- Provide links to full product details and selection support.
- Preserve selected products during inquiry when possible.

### Comparison failure conditions

- Specifications come from different revisions or test conditions
- Product attributes are misaligned across rows
- Missing values are concealed
- Comparison table is an image or unusable on mobile
- “Best” labels are unsupported
- Compare tool has no product-detail or assisted-selection path

## 8. Application Scenarios

### Objective

Explain where the category is used and which factors determine product suitability.

### Required content

- Industry, process, machine, system, environment, or medium
- Application requirements and risks
- Relevant product types
- Selection considerations and limitations
- Link to the dedicated Application or Solution page

### Rules

- Do not list industries without explaining product fit.
- Use verified product-to-application relationships.
- Distinguish Application from Solution:
  - Application explains operating context and suitability.
  - Solution explains a problem/system approach and how products work together.
- Include environmental and regulatory factors where relevant.
- Avoid claiming the entire category suits every listed scenario.
- Provide an engineering-review CTA for complex or safety-critical applications.

## 9. Technical Advantages

### Objective

Explain category-level technical and manufacturing strengths using evidence and buyer consequences.

### Recommended structure

`Verified feature/capability → evidence → buyer value → applicable scope/condition`

### Suitable advantage areas

- Design or technology
- Material and manufacturing process
- Performance range
- Accuracy, consistency, reliability, protection, or maintainability
- Customization and engineering
- Testing, quality control, traceability, and documentation
- Integration, accessories, compatibility, and support

### Rules

- Separate category-wide advantages from model-specific attributes.
- Support claims with product data, tests, standards, quality processes, or verified cases.
- Use “high quality,” “reliable,” and “cost-effective” only when replaced or supported by concrete evidence.
- State conditions behind performance data.
- Do not imply company-system certification applies to every product.
- Link to detailed capability, quality, case, and technical-resource pages.

## 10. FAQ

### Suitable category FAQ topics

- How do the main product types differ?
- Which parameters determine selection?
- Which applications or environments are supported?
- What standards, ratings, materials, or options are available?
- When is a custom configuration required?
- What information is needed for selection or quotation?
- Which technical documents and support services are available?

### Rules

- Answer category-level selection questions; keep model-specific questions on product pages.
- Use approved technical and commercial facts.
- Explain dependent variables immediately.
- Do not confirm compatibility, compliance, price, MOQ, or lead time without verified conditions.
- Link to deeper guides, products, solutions, and selection support.
- Visible questions and answers must match structured data when markup is used.
- FAQ markup does not guarantee a search-result feature.

## 11. CTA

### Buyer paths

#### Direct product path

`Category → Product Detail → Datasheet/Specifications → RFQ`

#### Assisted selection path

`Category → Selection Criteria/Compare → Submit Requirements → Product Recommendation`

#### Application path

`Category → Application/Solution → Products/Case/Evidence → Project Inquiry`

### Primary CTA options

- Compare Products
- Request Selection Support
- Request a Quote
- Discuss Your Application

### Secondary CTA options

- Download Category Catalog
- View Applications
- Review Technical Resources
- Contact an Engineer

### CTA rules

- Match CTA to category complexity and buyer stage.
- Place product-detail links on every valid product card.
- Place assisted-selection CTAs near comparison and technical criteria.
- Repeat a clear final CTA after FAQ or evidence.
- Preserve category, filtered criteria, compared products, and source URL in inquiry context.
- Ask for parameters required for qualification, not unnecessary personal data.
- Track product clicks, filters, compare actions, downloads, CTA clicks, form starts, errors, and submissions.
- Do not promise instant price or selection when engineering review is required.

## 12. SEO Checklist

### Positioning and intent

- [ ] Category has one clear product-family intent and canonical URL
- [ ] Buyer, market, application scope, and conversion path are defined
- [ ] Category is distinct from parent, child, product, Solution, Application, and Blog pages
- [ ] GSC/SERP evidence and internal keyword competition were checked where available

### H1 and Hero

- [ ] H1 names the complete category accurately
- [ ] Title, H1, breadcrumb, taxonomy, and opening use consistent terminology
- [ ] Hero defines the category, selection context, and next step
- [ ] Visual represents the category accurately and is optimized
- [ ] No unsupported manufacturer, leadership, certification, or performance claim appears

### Product list and classification

- [ ] Every listed product belongs to the category and has verified current data
- [ ] Product cards contain useful distinguishing attributes
- [ ] Product links resolve directly to canonical URLs
- [ ] Classification follows buyer selection logic
- [ ] Parent, child, sibling, and product relationships are understandable
- [ ] Pagination/load-more behavior preserves discovery
- [ ] Discontinued and unavailable products are handled intentionally

### Filters and comparison

- [ ] Filters use verified decision-relevant parameters and consistent units
- [ ] Active, reset, empty, incompatible, mobile, keyboard, and failure states work
- [ ] Strategic subcategory URLs and nonstrategic parameter URLs have intentional index rules
- [ ] Canonical, robots, sitemap, internal links, and parameter behavior agree
- [ ] Comparison uses equivalent attributes, units, revisions, and conditions
- [ ] Missing, optional, custom, and not-applicable data are labeled accurately
- [ ] Compare selections can progress to product details or assisted inquiry

### Applications and advantages

- [ ] Application entries explain requirements and product fit
- [ ] Product-to-application relationships are verified
- [ ] Application and Solution roles are distinct
- [ ] Category-wide advantages are separated from model-specific claims
- [ ] Technical advantages include evidence, buyer value, and scope/conditions
- [ ] Capability, quality, case, and resource links support claims

### FAQ and CTA

- [ ] FAQ answers recurring category-level selection questions
- [ ] Product-specific questions remain on product pages
- [ ] CTA supports direct selection, assisted selection, and application journeys
- [ ] Category/filter/compare context is preserved through inquiry
- [ ] Key interactions and conversion events are measurable

### Technical integrity

- [ ] Intended status, robots, canonical, and sitemap state are correct
- [ ] Primary content, products, and links exist in rendered HTML
- [ ] Mobile and desktop provide equivalent product access and content
- [ ] One valid Title and unique Description accurately represent the category
- [ ] Breadcrumb and applicable ItemList/Product schema match visible content
- [ ] Images, tables, cards, filters, compare, forms, and downloads are accessible
- [ ] Broken, redirected, blocked, noindex, staging, and duplicate parameter links are absent from priority paths
- [ ] Tracking, consent, verification, forms, and integrations are preserved

### Required Codex output

For every category-page analysis or optimization, provide:

1. Category objective, buyer, scope, and preferred intent
2. Existing taxonomy, products, filters, comparison, content, and CTA inventory
3. Identified problems and affected URLs/templates
4. Proposed module order and classification logic
5. Required product data, filters, comparison fields, evidence, and missing inputs
6. Internal-link and conversion-path map
7. Critical, High, Medium, and Low recommendations
8. Indexation/parameter strategy and approval requirements
9. Validation plan for desktop, mobile, crawlability, links, filters, comparison, forms, schema, tracking, and performance

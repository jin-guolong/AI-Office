# Industrial B2B Product Category Page Standard

> Codex internal execution rules for overseas English-language Product Category pages in machinery, electrical equipment, industrial equipment, and industrial components.

## Scope and Required Inputs

Before analyzing, creating, or modifying a Category page, Codex must confirm:

- Approved Category name, parent/child taxonomy, and canonical URL
- Included Products, models, variants, lifecycle status, and canonical Product URLs
- Target countries, English variant, buyer roles, industries, and Applications
- Buyer selection criteria and priority Product attributes
- Verified specifications, ranges, units, standards, options, and limitations
- Filter, comparison, download, and inquiry requirements
- Related Solution, Application, Case, Knowledge, FAQ, and capability pages
- Existing Title, H1, URL, metadata, schema, navigation, tracking, forms, and technical dependencies

Do not infer Category-wide specifications, certification, compatibility, Product availability, or manufacturing capability from incomplete data.

# Page Positioning

The Product Category page has three primary roles.

## Product Collection

The page must present a coherent Product family and help buyers understand which Products, types, or models belong together.

Required outcomes:

- Define the Product family
- Show available types/models
- Explain meaningful differences
- Link to canonical Product Detail pages
- Preserve an understandable parent/child taxonomy

The page must provide more than an unexplained Product grid.

## Keyword Entry

The Category page owns broad Product-family commercial intent, including:

- Product category and type terms
- Product range and manufacturer/supplier intent where accurate
- Category-level technology, material, rating, and Application concepts
- Comparison and selection terms that apply across the range

Exact model/specification/document intent belongs to Product Detail pages. Problem/system intent belongs to Solution pages. Distinct operating-context intent may belong to Application pages.

## Selection Entry

The page must help engineers, procurement teams, OEMs, integrators, distributors, and project buyers narrow the range.

Selection support may include:

- Classification
- Decision-relevant parameters
- Filters
- Product comparison
- Technical advantages and limitations
- Application mapping
- Selection Guide and FAQ
- Direct Product route or assisted-selection CTA

## Positioning acceptance criteria

- [ ] Category owns one distinct broad Product-family intent
- [ ] Included Product scope and taxonomy are clear
- [ ] Page is distinct from parent, child, Product, Solution, Application, and Knowledge pages
- [ ] Buyer, selection task, target market, and conversion path are defined
- [ ] Page contains enough selection value beyond Product cards

# Standard Structure

## Hero

### Purpose

Identify the Product family, its main use or selection context, and the buyer’s next action.

### Required content

- Breadcrumb
- One H1 naming the Category
- Concise Category definition
- Primary Application or selection context
- Primary CTA and optional secondary CTA
- Accurate Category/Product visual

Recommended formula:

`Product family → suitable needs/Applications → verified range/capability → selection action`

### Rules

- Do not use generic company slogans.
- Do not list every Product subtype or keyword.
- Use a visual that represents the range or label a specific model clearly.
- Do not make one Product’s rating or certification appear Category-wide.
- Optimize the primary image and preserve mobile readability.

### Conversion role

- Direct Product-aware buyers to the Product List.
- Route complex buyers to Compare Products or Request Selection Support.

## Introduction

### Purpose

Explain what the Category includes, how Products differ, where they are used, and what determines selection.

### Required content

- Product-family definition
- Main types or classification logic
- Core functions and Applications
- Important selection factors
- Range-wide capability and limitations
- Link/anchor to Product List or Selection Guide

### Rules

- Use buyer terminology and approved Product taxonomy.
- Keep Category-wide facts separate from model-specific data.
- Avoid copying Homepage or Product introductions.
- Explain unfamiliar technical terms.
- State when engineering review is required.

### SEO and conversion role

- Confirms broad Product intent after H1.
- Provides natural coverage of types, Applications, parameters, and buyer language.
- Helps buyers choose the correct navigation or selection path.

## Product List

### Purpose

Present current Products in a consistent format so buyers can identify suitable candidates and reach exact Product pages.

### Required functions

- Logical Product grouping/order
- Product cards using standardized data
- Crawlable links to canonical Product Detail pages
- Optional filters, shortlist, or compare action
- Pagination/load-more implementation that preserves discovery
- Empty, unavailable, and discontinued states handled intentionally

### Ordering logic

Use one or more buyer-relevant dimensions:

- Product type
- Capacity, rating, size, power, voltage, load, speed, pressure, or temperature
- Material, environment, medium, or protection
- Technology or configuration
- Application
- Standard/default versus custom

Do not hide selection logic behind arbitrary ordering.

### Technical rules

- Include only Products belonging to the Category.
- Use consistent attribute labels, units, and data revisions.
- Link directly to canonical HTTPS Product URLs.
- Avoid tracking/parameter variants as Product-card destinations.
- Maintain keyboard, mobile, and assistive-technology usability.
- Do not silently remove valuable discontinued pages without impact review.

## Comparison

### Purpose

Enable buyers to compare equivalent Products using consistent attributes and conditions.

### Required fields where applicable

- Product/model identity
- Product type and function
- Core specifications and units
- Materials, ratings, standards, and options
- Dimensions, interfaces, and mounting
- Applications, environment, and limitations
- Documents and inquiry actions

### Rules

- Compare only Products a buyer can reasonably evaluate together.
- Use equivalent definitions, units, document revisions, and test conditions.
- Label missing, optional, custom, and not-applicable values accurately.
- Do not convert missing values to zero, `No`, or guesses.
- Explain trade-offs rather than declaring a universal winner.
- Make tables usable on mobile and accessible.
- Preserve selected Products in the inquiry context where possible.

### Conversion role

- Move buyers from range exploration to Product Detail or assisted selection.
- Track compare starts, Product additions/removals, detail visits, and inquiry actions.

## Technical Advantage

### Purpose

Explain verified Category-level engineering, Product, manufacturing, quality, or support strengths.

### Required structure

`Feature/capability → mechanism/evidence → buyer value → scope/condition`

### Suitable topics

- Design or technology
- Material and manufacturing process
- Performance range
- Accuracy, protection, reliability, maintainability, or integration
- Customization and engineering
- Testing, quality control, traceability, and documentation
- Accessories, compatibility, and support

### Rules

- Separate Category-wide advantages from Product-specific attributes.
- Replace “high quality,” “advanced,” “reliable,” and “cost-effective” with concrete evidence.
- State conditions behind quantitative performance.
- Distinguish company-system certification from Product certification.
- Link to capability, Quality, Case, test, and technical-resource pages.

### Conversion role

- Reduce engineering and supplier risk.
- Route buyers to technical proof, Product pages, selection support, or RFQ.

## Applications

### Purpose

Show where the Product family is used and which conditions determine Product suitability.

### Required content

- Industry, process, machine, system, environment, material, or medium
- Application requirements and risks
- Suitable Product types
- Selection conditions and limitations
- Link to dedicated Application or Solution page

### Rules

- Do not list industries without explaining fit.
- Verify Product-to-Application relationships.
- Application explains operating context; Solution explains problem/system approach.
- Avoid claiming every Product supports every Application.
- Flag hazardous, safety-critical, high-load, pressure, thermal, electrical, chemical, or regulatory Applications for qualified review.

### SEO and conversion role

- Supports Product + Application search behavior.
- Connects Category to Application/Solution clusters.
- Routes complex buyers to Application consultation.

## Selection Guide

### Purpose

Translate Product data into a repeatable selection process for engineers and procurement teams.

### Required content

1. Buyer inputs required
2. Product-type decision logic
3. Core parameters and ranges
4. Material, rating, standard, environment, and interface criteria
5. Options and incompatible combinations
6. Trade-offs and limitations
7. When engineering review is required
8. Next Product or inquiry action

### Industry-specific criteria

#### Machinery

- Process/material, capacity, output, accuracy, automation, utilities, footprint, integration, safety, maintenance

#### Electrical equipment

- Voltage, current, power, frequency, phase, fault level, protection, coordination, derating, enclosure, standard, installation

#### Industrial components

- Material, dimension, tolerance, load, speed, pressure, temperature, medium, fit, interface, sealing, wear, compatibility

### Rules

- Use verified data and consistent units.
- Do not provide unsafe or incomplete calculations.
- Distinguish general guidance from project-specific engineering approval.
- Provide a comparison table, flow, or checklist only when it improves the decision.
- Link selection steps to relevant Product pages.

### Conversion role

- Converts uncertain buyers into qualified Product candidates or a structured selection-support inquiry.

## FAQ

### Purpose

Resolve recurring Category-level selection, range, Application, documentation, customization, and sourcing questions.

### Suitable questions

- How do Product types differ?
- Which parameters determine selection?
- Which Applications and environments are supported?
- Which materials, ratings, standards, and options are available?
- When is a custom configuration required?
- What information is needed for selection or quotation?
- Which documents and support services are available?

### Rules

- Product/model-specific questions belong on Product pages.
- Give a direct answer, followed by conditions and limitations.
- Do not confirm compatibility, compliance, price, MOQ, lead time, or warranty without approved conditions.
- Link to Product, Solution, Application, guide, document, or selection support.
- Visible FAQ must match structured data when used.

### Conversion role

- Removes final selection and sourcing friction.
- Routes buyers to Products, documents, comparison, RFQ, or engineering support.

## CTA

### Purpose

Move buyers from Category exploration to Product Detail, comparison, assisted selection, or quotation.

### Buyer paths

```text
Direct Product:
Category → Product Detail → Specifications/Download → RFQ

Assisted Selection:
Category → Comparison/Selection Guide → Submit Requirements → Recommendation

Application:
Category → Application/Solution → Product/Case/Evidence → Consultation
```

### Primary CTA options

- Compare Products
- Request Selection Support
- Request a Quote
- Discuss Your Application

### Secondary CTA options

- View Product Details
- Download Category Catalog
- View Applications
- Review Technical Resources

### Rules

- Match CTA to Category complexity and buyer stage.
- Place Product-detail CTA on every Product card.
- Put assisted-selection CTA near Comparison and Selection Guide.
- Preserve Category, filter, compared Products, and source context through forms/CRM.
- Ask only for qualification inputs required at that stage.
- Track Product clicks, filters, comparison, downloads, CTA, form starts, errors, and submissions.
- Do not promise instant price, compatibility, delivery, or engineering approval.

# Product Card Rules

Every Product card must help the buyer identify the Product, understand one or more meaningful differences, and reach the canonical Product page.

## Image

Requirements:

- Approved image of the actual Product/model or a clearly labeled representative configuration
- Consistent aspect ratio and sufficient resolution
- Optimized file size and reserved dimensions
- Meaningful alternative text when the image conveys Product information
- No stock/competitor/unavailable configuration presented as actual Product

Checks:

- Image matches Product name/model.
- Variants are not visually misrepresented.
- Image link and Product-name link share the correct canonical destination.

## Model

Requirements:

- Exact approved Product/model name
- Product type when model code alone is unclear
- Consistent spelling, punctuation, capitalization, and taxonomy
- Product lifecycle/status handled accurately

Rules:

- Do not abbreviate in a way buyers cannot understand.
- Do not change model codes for keyword placement.
- Do not show one family name as several Products without real differences.

## Core Parameters

Requirements:

- Two to four selection-critical attributes
- Consistent labels and units across cards
- Correct source and document revision
- Optional/custom/range data labeled clearly

Examples:

- Machinery: capacity, process, automation, accuracy, power
- Electrical: voltage, current, breaking/protection rating, poles, enclosure
- Components: material, size, load, speed, pressure, temperature, interface

Rules:

- Do not choose attributes only because they contain keywords.
- Do not mix incomparable attributes across cards.
- Do not guess missing values.

## Application

Requirements:

- One concise verified use case or operating context
- Important environmental/selection qualifier where necessary
- Link to Application/Solution only when a deeper page exists

Rules:

- Avoid generic `widely used in many industries` copy.
- Do not claim food-grade, hazardous-area, washdown, chemical, high-temperature, or other suitability without evidence.
- Avoid implying all configurations support the stated Application.

## CTA

Required primary card CTA:

- View Product Details
- View Specifications
- Configure/Compare where the function truly exists

Optional secondary action:

- Add to Compare
- Request Quote
- Ask About This Model

Rules:

- Use a crawlable `<a href>` for Product navigation.
- Preserve Product/model context in RFQ/compare actions.
- Use accessible labels; avoid repeated ambiguous `Learn More` links without card context.
- Test keyboard, mobile, error, and analytics behavior.

# SEO Rules

## H1

- Use one H1 naming the complete Product Category.
- Align with Title, Category definition, breadcrumb, taxonomy, and internal anchors.
- Do not place one Product model in Category H1.
- Do not list every subtype, parameter, industry, country, or synonym.
- Use `manufacturer` only when the company actually manufactures the Category.
- Do not imply a Category-wide rating, material, standard, or certification based on one Product.

Recommended patterns:

`[Product Category]`

`[Product Category] for [Primary Application]`

`[Verified Technology/Material] [Product Category]`

## URL

- Use one stable, readable canonical URL for the Category.
- Follow approved site taxonomy and language structure.
- Avoid dates, session IDs, tracking parameters, and unnecessary keyword repetition.
- Do not change an existing URL without approval and a migration plan.
- Control Product filters, sort, pagination, and parameter combinations intentionally.
- Strategic subcategories may have indexable URLs when they provide distinct buyer value; ordinary filter combinations should not create unlimited indexable pages.
- Keep canonical, redirects, internal links, sitemap, hreflang, schema, and navigation consistent.

## Title

Title must represent Product-family commercial intent and one useful verified qualifier.

Recommended patterns:

`[Product Category] for [Primary Application] | [Brand]`

`[Product Category] – [Verified Range/Technology] | [Brand]`

`[Product Category] Manufacturer | [Brand]`

Rules:

- Keep Title unique from parent, child, and Product pages.
- Do not list every subtype or keyword variant.
- Do not use Product-specific specifications as Category-wide claims.
- Do not treat fixed character count as a Google rule; preview likely desktop/mobile display.

## Internal Link

Required incoming links:

- Homepage or parent Category
- Child Product pages through breadcrumb/context
- Relevant Application, Solution, Blog, Case, and capability pages

Required outgoing links:

- Child Categories and canonical Product pages
- Comparison and Selection Guide
- Applications and Solutions
- Cases, FAQ, documents, and technical resources
- Category-level selection/RFQ path

Rules:

- Use crawlable `<a href>` links.
- Link directly to canonical HTTPS URLs.
- Use precise or natural partial-match anchors describing the destination.
- Do not point broad Category anchors mainly to one Product model.
- Avoid broken, redirected, blocked, noindex, staging, and unintended parameter destinations.
- Ensure Category is neither orphaned nor a buyer dead end.

# Checklist

## Positioning and structure

- [ ] Category has one distinct broad Product-family intent and canonical URL
- [ ] Product collection, keyword entry, and selection entry roles are fulfilled
- [ ] Buyer, target market, Applications, and conversion path are defined
- [ ] Category is distinct from parent, child, Product, Solution, Application, and Knowledge pages
- [ ] Hero, Introduction, Product List, Comparison, Technical Advantage, Applications, Selection Guide, FAQ, and CTA exist as needed

## Product List and cards

- [ ] Every listed Product belongs to the Category and is current
- [ ] Product grouping/order follows buyer selection logic
- [ ] Product card contains approved image, exact model/name, core parameters, Application, and CTA
- [ ] Card attributes use consistent labels, units, sources, and revisions
- [ ] Product links resolve directly to canonical Product URLs
- [ ] Card image, name, parameters, and Application describe the same Product/configuration
- [ ] Pagination/load-more exposes priority Product links
- [ ] Discontinued/unavailable Products have an intentional strategy

## Comparison and selection

- [ ] Compared Products are meaningfully comparable
- [ ] Attributes, units, revisions, and conditions are equivalent
- [ ] Missing, optional, custom, and not-applicable values are accurate
- [ ] Trade-offs and limitations are explained
- [ ] Selection Guide states required buyer inputs and decision logic
- [ ] Safety-critical or project-specific selection boundaries are clear
- [ ] Compare/selection context persists through Product visits and inquiry

## Technical, Application, and trust content

- [ ] Technical advantages include mechanism/evidence, buyer value, and scope
- [ ] Category-wide facts are separated from Product-specific claims
- [ ] Product-to-Application relationships are verified
- [ ] Application and Solution roles are distinct
- [ ] Capability, quality, standard, certification, Case, and document evidence is approved
- [ ] No specification, compatibility, certification, performance, or availability is invented

## SEO

- [ ] One H1 accurately names the Category
- [ ] URL is stable, canonical, readable, and aligned with taxonomy/language
- [ ] Title is unique and aligned with Category intent
- [ ] Meta Description accurately summarizes range, selection value, and next step
- [ ] Parent, child, Product, Solution, Application, Blog, Case, resource, and CTA links are logical
- [ ] Filter, sort, pagination, and parameter URLs have an intentional crawl/index strategy
- [ ] Canonical, redirects, internal links, sitemap, hreflang, schema, and navigation agree
- [ ] No internal keyword competition or duplicate Category role remains unresolved

## UX, conversion, and technical integrity

- [ ] Product cards, filters, comparison, tables, FAQ, and forms work on mobile and keyboard
- [ ] Primary content and Product links exist in rendered HTML
- [ ] CTA supports direct Product, assisted selection, and Application paths
- [ ] Forms ask only for useful qualification data
- [ ] Category/filter/compare/Product/source context persists through inquiry
- [ ] Product click, filter, comparison, download, CTA, form, call, and email events are measurable
- [ ] Tracking, consent, verification, uploads, CRM, and integrations are preserved
- [ ] Broken, redirected, blocked, noindex, staging, duplicate, and unintended parameter links are absent from priority paths

## Required Codex output

For every Category analysis or optimization, provide:

1. Page positioning, buyer, intent, Product scope, and conversion objective
2. Existing structure, Product inventory, cards, comparison, and selection functions
3. H1, URL, Title, metadata, canonical, schema, and internal-link findings
4. Proposed module order and Product-card field standard
5. Product classification, comparison, and selection criteria
6. Filter/parameter crawl and index strategy
7. Critical, High, Medium, and Low findings
8. Missing Product data, evidence, dependencies, and approval requirements
9. Validation plan for facts, desktop/mobile rendering, Product links, filters, comparison, forms, metadata, schema, tracking, accessibility, and performance

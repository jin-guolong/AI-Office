# Industrial B2B Product Detail Page Standard

> Codex internal execution rules for overseas English-language Product pages for machinery, electrical products, industrial equipment, and industrial components.

## Scope and Required Inputs

Before analyzing, writing, or modifying a Product page, Codex must confirm:

- Approved Product name, model, parent Category, lifecycle status, and canonical URL
- Target countries, English variant, buyer roles, industries, and Applications
- Current datasheet, drawing, manual, catalog, and document revisions
- Verified specifications, units, ranges, ratings, tolerances, options, and limitations
- Materials, standards, certifications, testing, and quality evidence
- Working principle and technical-review source
- Production, installation, commissioning, operation, maintenance, and safety information
- Required RFQ fields, downloads, forms, tracking, consent, CRM, and integrations

Missing facts must be marked internally for validation. Codex must not infer Product specifications, materials, ratings, compatibility, certification, performance, lifespan, price, stock, MOQ, lead time, warranty, or Application suitability.

# First-Screen Structure

The first screen must enable the buyer to identify the Product, understand its verified value, review essential selection data, and choose the next action.

## Product Name

### Purpose

Identify the exact Product or configurable family represented by the page.

### Requirements

- One H1 using the approved Product/model name
- Product type when model code alone is unclear
- Consistency with Title, breadcrumb, Product data, schema, documents, and inquiry context
- Correct spelling, punctuation, unit notation, and model revision

### Rules

- Use `[Model] [Product Type]` when the page represents one exact model.
- Use the approved family name when one page represents multiple configurable models.
- Do not place one model in H1 while displaying incompatible multi-model specifications as if they belong to it.
- Do not rename the Product for keyword insertion.
- State discontinued, successor, or replacement status accurately when applicable.

## Value Proposition

### Purpose

Explain the Product’s primary function and verified decision value in the target Application.

### Recommended formula

`Product function → suitable Application/condition → verified differentiator → buyer value`

### Requirements

- One concise Product definition
- Primary use or operating context
- One or two verified differentiators
- Technical, operational, maintenance, integration, procurement, or lifecycle value
- Important condition or limitation where necessary

### Rules

- Replace `high quality`, `advanced`, `reliable`, and `cost-effective` with evidence.
- Do not claim universal suitability.
- Do not promise guaranteed performance, savings, safety, compliance, service life, or ROI.
- Keep Company capability separate from Product-specific value.

## Key Specs

### Purpose

Provide a small set of selection-critical values for rapid Product validation.

### Requirements by Product type

#### Machinery and industrial equipment

- Capacity/output/process
- Accuracy/speed/automation where relevant
- Power/utility/configuration
- Size/footprint or material handled

#### Electrical products

- Voltage/current/power/frequency
- Poles/phases/duty/protection or breaking rating
- Enclosure/environment/standard where relevant

#### Industrial components

- Material/grade
- Size/tolerance/interface
- Load/speed/pressure/temperature
- Medium/environment where relevant

### Rules

- Display only three to six truly critical values.
- Use approved units, definitions, and document revisions.
- Distinguish rated, nominal, typical, tested, minimum, and maximum values.
- Keep values consistent with the full Technical Parameters table.
- Do not display optional/custom values as standard.
- Never guess missing values.

## CTA

### Purpose

Give Product-aware buyers a direct route to Product Detail, technical validation, selection support, or quotation.

### Primary CTA options

- Request a Quote
- Confirm Product Selection
- Discuss This Product
- Contact an Engineer

### Secondary CTA options

- Download Datasheet
- View Technical Drawing
- Compare Models
- View Application Solution

### Rules

- Preserve Product/model, selected variant, source URL, and campaign context.
- Match CTA commitment to Product complexity.
- Do not promise instant price, stock, delivery, compatibility, or engineering approval.
- Make CTA, form, upload, error, consent, and confirmation states accessible.
- Track CTA clicks, form starts, errors, submissions, downloads, calls, and emails.

## First-screen media

- Use an approved image/drawing of the actual Product or a clearly labeled representative configuration.
- Do not use a system/Application image that implies an unavailable configuration.
- Provide accurate alternative text.
- Optimize the likely LCP image, reserve dimensions, and maintain mobile usability.

# Content Modules

## Introduction

### Purpose

Define the Product, explain its role, identify suitable buyers/Applications, and set the scope for the page.

### Content requirements

- Product definition and primary function
- Product type/category relationship
- Suitable Application or operating context
- Main Product scope and options
- Key selection factors
- Link to Category, Application, or Solution where useful

### Rules

- Confirm the first-screen promise immediately.
- Avoid repeating Company history or Category copy.
- Explain technical terms when needed.
- State when Product selection requires project-specific review.

## Features

### Purpose

Translate verified Product characteristics into buyer value.

### Required structure

`Feature → mechanism/evidence → buyer value → scope/condition`

### Suitable feature groups

- Performance/process control
- Accuracy/consistency
- Reliability/durability
- Safety/protection
- Efficiency/resource use
- Integration/compatibility
- Maintenance/serviceability
- Configuration/customization
- Documentation/traceability

### Rules

- Do not repeat Technical Parameters without interpretation.
- Separate Product features from Manufacturing capability.
- State test/operating conditions behind quantitative benefits.
- Do not use unsupported superlatives or universal comparisons.

## Technical Parameters

### Purpose

Provide complete structured data needed to validate fit and compare configurations.

### Machinery and industrial equipment fields

- Process/material handled
- Capacity, output, speed, accuracy, cycle
- Dimensions, weight, footprint, environment
- Power, voltage, frequency, air, water, and utilities
- Automation, control, interface, safety, and line integration
- Standard configuration and options

### Electrical product fields

- Rated voltage, current, power, frequency
- Poles, phases, duty, fault/breaking/protection characteristics
- Insulation, enclosure, IP/NEMA, temperature, altitude, and derating
- Connection, mounting, communication, coordination, and accessories
- IEC, UL, regional, or Product-specific standard scope

### Industrial component fields

- Dimensions, tolerances, load, speed, pressure, temperature, or flow
- Material grade, hardness, finish, coating, or treatment
- Mounting, thread, interface, seal, lubrication, and medium
- Environmental, chemical, corrosion, and wear conditions
- Standard/custom/replacement/accessory relationships

### Parameter rules

- Use tables for comparable data.
- Maintain consistent units and verified conversions.
- State definitions and conditions.
- Separate standard, optional, custom, unavailable, and not-applicable data.
- Record source and revision internally.
- Do not convert missing data to zero, `No`, or a guess.
- Make tables readable and accessible on mobile.

## Working Principle

### Purpose

Explain how the Product performs its function so buyers can evaluate suitability, integration, protection, and operation.

### Required content

- Input: material, energy, signal, or medium
- Main components and functions
- Operating sequence or physical/electrical mechanism
- Output or controlled result
- Interfaces with other equipment/systems
- Control and protection logic where applicable
- Operating conditions, limits, and safety boundaries

### Suitable formats

- Step-by-step sequence
- Process flow
- Section/cutaway diagram
- Electrical/functional block diagram
- Component relationship table

### Rules

- Use approved engineering sources and diagrams.
- Distinguish general principle from model-specific implementation.
- Protect confidential design and trade-secret information.
- Do not oversimplify safety-critical machinery or electrical functions.
- State when system design, coordination, sizing, or approval requires qualified engineering review.

## Applications

### Purpose

Show where the Product is used, what function it performs, and which conditions determine suitability.

### Required content

- Industry, process, machine, system, environment, material, or medium
- Product function in the Application
- Operating requirements
- Suitable option/configuration
- Limitations and validation requirements
- Links to Application, Solution, and Case pages

### Rules

- Do not list industries without explaining fit.
- Verify every Product-to-Application relationship.
- State relevant load, speed, pressure, temperature, voltage, current, dust, moisture, corrosion, washdown, hazardous-area, or duty conditions.
- Do not imply one configuration supports every Application.
- Use Application for context and Solution for integrated problem/system logic.

## Materials

### Purpose

Explain materials, grades, treatments, and selection implications affecting Product performance and sourcing.

### Required content

- Material and exact grade where claimed
- Product part/location using the material
- Surface treatment, coating, plating, heat treatment, insulation, or seal material
- Mechanical, electrical, thermal, chemical, corrosion, wear, hygiene, or safety relevance
- Standard versus optional materials
- Restricted/incompatible environments or media
- Material documentation/traceability availability

### Rules

- Do not use a generic material family when claiming an exact grade.
- Do not claim food-grade, medical, hazardous-area, flame, RoHS, REACH, or other compliance without applicable evidence.
- Do not infer compatibility from appearance or common reputation.
- Link approved material certificates/declarations only when current and applicable.

## Production Process

### Purpose

Show how the Product is manufactured, assembled, configured, or integrated in a way that supports Product consistency and customization.

### Required content where applicable

- Material/input control
- Design and engineering review
- Tooling, forming, machining, molding, winding, fabrication, surface treatment, assembly, or integration
- Process controls and critical checkpoints
- Customization, prototyping, samples, or first-article process
- Traceability and change control
- Packaging and preservation

### Required structure

`Process step → control/evidence → Product relevance → buyer-risk reduction`

### Rules

- Use real approved production evidence.
- Distinguish in-house, partner-operated, and outsourced processes.
- Do not expose confidential tooling, drawings, parameters, customers, capacity, or trade secrets.
- Do not present stock factory images as company evidence.
- Explain why the process matters to the Product rather than listing machines.

## Quality Control

### Purpose

Demonstrate how Product requirements are verified and documented.

### Required content

- Incoming-material/document checks
- In-process inspection and process controls
- Final dimensional, functional, electrical, pressure, performance, or visual checks
- Test equipment and method
- Sampling/full-inspection basis where approved
- Calibration, traceability, nonconformance, and documentation
- Applicable quality-system and Product certification scope

### Quality evidence table

| Requirement | Inspection/test | Method/equipment | Acceptance basis | Record/document |
|---|---|---|---|---|
|  |  |  |  |  |

### Rules

- Distinguish company-system certification from Product certification.
- Do not imply every test applies to every Product/configuration.
- State relevant standards and test conditions accurately.
- Do not display expired, unrelated, copied, or unapproved certificates.
- Protect sensitive certificate, report, and customer data.

## Installation

### Purpose

Provide verified planning information and direct buyers to the current approved installation/manual resources.

### Required content where applicable

- Site, foundation, space, access, utilities, and environmental requirements
- Mounting, alignment, connection, wiring, piping, guarding, and integration
- Pre-installation checks
- Commissioning and verification boundaries
- Tools, skills, PPE, permits, and qualified personnel
- Maintenance access and document links

### Rules

- Follow approved manuals and applicable standards.
- Do not publish dangerous shortcuts or advise bypassing guards, interlocks, grounding, isolation, protection, or lockout/tagout.
- Electrical work requires qualified personnel and local-code review where applicable.
- Heavy equipment, lifting, pressure, thermal, chemical, and stored-energy risks require appropriate warnings and technical review.
- A short webpage summary must not replace the official manual.

## FAQ

### Purpose

Resolve model-specific selection, compatibility, documentation, installation, customization, maintenance, and ordering questions.

### Suitable questions

- Is this model suitable for a defined Application or operating condition?
- How should rating, size, material, or configuration be selected?
- Which options, accessories, interfaces, and documents are available?
- Which standards/certifications apply to this exact Product?
- What inputs are required for compatibility or engineering confirmation?
- What information is required for quotation?

### Rules

- Keep Category-level questions on Category pages.
- Answer directly, then state conditions and limitations.
- Do not guarantee compatibility, performance, service life, compliance, price, stock, lead time, MOQ, or warranty.
- Link to the relevant section, document, Application, Solution, or support route.
- Visible FAQ must match structured data when used.
- Safety-sensitive answers require qualified review.

## Download

### Purpose

Provide approved Product documents required for technical validation, integration, installation, and procurement.

### Download types

- Datasheet
- Technical drawing
- Installation/operation/maintenance manual
- CAD/3D file
- Product catalog
- Certificate/declaration
- Test report or technical note
- Selection/configuration guide

### Required metadata

- Document title
- Product/model scope
- Document type
- Revision/date
- Language
- File type/size where useful
- Access restrictions where applicable

### Rules

- Link only current approved files.
- Keep file data consistent with visible Product information.
- Do not expose confidential or superseded documents.
- Use descriptive file names and anchor text.
- Track downloads with Product/model and document context.
- Important Product content must also exist in HTML.

# Buyer Decision Path

Before purchasing or submitting an RFQ, an industrial buyer must resolve the following questions.

## 1. Product identity

- Is this the correct Product type and model?
- Does the page represent one model or a configurable family?
- Is the Product current, replaced, or discontinued?

Required modules: Product Name, Introduction, Category/breadcrumb, related-model links.

## 2. Application fit

- Is the Product suitable for the intended industry, process, machine, medium, or environment?
- What operating conditions and limitations apply?
- Is project-specific engineering review required?

Required modules: Value Proposition, Applications, Materials, FAQ, Solution/Application links.

## 3. Technical fit

- Do capacity, rating, dimensions, load, voltage, current, pressure, temperature, tolerance, interface, and other parameters meet requirements?
- Which values are rated, nominal, tested, optional, or custom?

Required modules: Key Specs, Technical Parameters, Working Principle, drawings/downloads.

## 4. Configuration and compatibility

- Which material, option, accessory, connection, mounting, control, or variant is required?
- What Products/systems are compatible?
- Which combinations are incompatible or subject to confirmation?

Required modules: Technical Parameters, Materials, Features, Comparison/related Products, FAQ.

## 5. Standards, safety, and documentation

- Which standards, certifications, test methods, installation rules, and documents apply to this exact Product?
- Does the buyer need local code, system-level, or qualified professional review?

Required modules: Quality Control, Installation, Download, FAQ.

## 6. Supplier and manufacturing confidence

- Can the supplier manufacture, control, customize, document, and support the Product consistently?
- Which processes are in-house, partner-operated, or outsourced?

Required modules: Production Process, Quality Control, Manufacturing/capability links, Case evidence.

## 7. Commercial and project readiness

- What information is required for selection and quotation?
- Is a drawing, sample, specification, quantity, destination, or project schedule required?
- What is the next technical/commercial step?

Required modules: FAQ, Download, CTA, Product-specific form.

## Recommended decision flow

```text
Identify Product
  → Confirm Application fit
  → Review Key/Full Specs
  → Validate Configuration and Materials
  → Verify Principle, Quality, Standards, and Documents
  → Review Installation and Supplier Proof
  → Request Selection Support or RFQ
```

The page is incomplete when the buyer cannot resolve a required decision or reach a qualified next step.

# SEO Rules

## H1

- Use one H1 identifying the exact Product/model or approved configurable family.
- Include model when the page represents one exact model and buyers use it for validation/sourcing.
- Include Product type when the model code is not self-explanatory.
- Do not use Category-wide scope for a single Product.
- Align H1 with Title, Product data, breadcrumb, schema, documents, and inquiry context.
- Do not list keywords, ratings, industries, and synonyms in H1.

## Title

Recommended patterns:

`[Model] [Product Type] – [Verified Attribute/Application] | [Brand]`

`[Product Name] for [Application/Operating Need] | [Brand]`

`[Product Type], [Verified Rating/Material] – [Model] | [Brand]`

Rules:

- Keep Title unique from Category and other Product pages.
- Use only verified Product-specific attributes.
- Preserve approved model spelling and units.
- Do not claim price, stock, certification, compatibility, or performance without visible evidence.
- Preview likely desktop/mobile display without treating fixed length as a Google rule.

## Description

Recommended sequence:

`Product identity → verified fit/specification/value → next action`

Rules:

- Write a unique Description for the canonical Product page.
- Include one or two useful verified Product-specific facts.
- Use natural professional English, not a keyword list.
- CTA may invite specification review, datasheet download, selection support, or RFQ.
- Do not repeat Title or introduce claims absent from visible content.
- Review likely truncation; do not treat a fixed length as a Google rule.

## Schema

Use Product structured data only when the page and visible data qualify.

Rules:

- Match visible Product name, model, description, image, brand, SKU/MPN, and canonical URL.
- Use stable canonical `url` and `@id` values.
- Do not invent price, currency, stock, availability, review, rating, GTIN, shipping, return, or Offer data.
- `Offer` is inappropriate when a B2B request-quote page has no real visible/maintained price and availability data.
- Variant schema must match actual selectable Products and page behavior.
- Breadcrumb schema must match visible hierarchy.
- Avoid duplicate/conflicting CMS/plugin/custom Product entities.
- Validate syntax, vocabulary, Google eligibility, rendered output, and visible-content parity.
- Structured data does not guarantee a rich result.

## Internal Links

Required incoming links:

- Parent Category
- Verified Application and Solution pages
- Comparison/selection guides
- Case Studies and technical resources
- Replacement/successor or related Product pages where useful

Required outgoing links:

- Canonical parent Category
- Verified Applications and Solutions
- Related models, alternatives, accessories, and replacements with context
- Product-specific Cases, documents, FAQ, and evidence
- Product-specific RFQ or engineering support

Rules:

- Use crawlable `<a href>` links.
- Link directly to canonical HTTPS URLs.
- Use accurate Product/model/Application anchors.
- Do not link to technically incompatible Products.
- Preserve Product/model context in CTA, download, compare, and form links.
- Avoid broken, redirected, blocked, noindex, staging, and unintended parameter destinations.

# Codex Checklist

## First screen

- [ ] Product/model, parent Category, buyer, market, intent, and conversion are defined
- [ ] Product Name/H1 accurately identifies the page scope
- [ ] Value Proposition explains function, fit, verified value, and condition
- [ ] Key Specs contain only selection-critical verified values
- [ ] Hero image/drawing represents the actual Product/configuration
- [ ] Primary and secondary CTA support appropriate buyer actions
- [ ] Product/model/source context persists through CTA and events

## Content completeness

- [ ] Introduction confirms Product identity, scope, Application, and selection factors
- [ ] Features connect mechanism/evidence to buyer value and limitation
- [ ] Technical Parameters use approved sources, revisions, units, definitions, and conditions
- [ ] Working Principle is accurate, technically reviewed, and appropriately scoped
- [ ] Applications state operating context, fit, limits, and relevant links
- [ ] Materials, grades, treatments, and compatibility claims are verified
- [ ] Production Process shows real Product-relevant controls and evidence
- [ ] Quality Control explains inspection/test methods and certification scope
- [ ] Installation follows approved manuals, standards, and safety boundaries
- [ ] FAQ answers model-specific recurring questions
- [ ] Downloads are current, approved, labeled, accessible, and tracked

## Buyer decision path

- [ ] Buyer can confirm Product identity and lifecycle status
- [ ] Buyer can evaluate Application and technical fit
- [ ] Buyer can select configuration/material/interface or request review
- [ ] Standards, safety, quality, and documents can be validated
- [ ] Supplier/manufacturing evidence is sufficient
- [ ] Required RFQ inputs and next action are clear
- [ ] No specification, compatibility, certification, performance, or commercial fact is invented

## SEO

- [ ] H1, Title, Description, Product data, canonical, breadcrumb, schema, and documents agree
- [ ] One preferred canonical URL serves the exact Product intent
- [ ] Product page does not compete with Category, Solution, Application, or Blog pages
- [ ] Product schema matches visible verified data and contains no fabricated Offer/review fields
- [ ] Required incoming/outgoing internal-link relationships exist
- [ ] Anchors and destinations are accurate and canonical

## UX, conversion, and technical integrity

- [ ] Main content, specifications, links, and schema exist in rendered HTML
- [ ] Mobile and desktop provide equivalent Product information and actions
- [ ] Tables, diagrams, images, media, downloads, FAQ, and forms are accessible
- [ ] CTA supports direct RFQ, assisted selection, technical validation, and alternative Product paths
- [ ] Form fields match real qualification requirements
- [ ] CTA, form, download, compare, call, and email events are measurable
- [ ] Tracking, consent, verification, CRM, upload, and anti-spam integrations are preserved
- [ ] Broken, redirected, blocked, noindex, staging, duplicate, and parameter links are absent from priority paths

## Required Codex output

For every Product-page analysis or optimization, provide:

1. Product identity, page scope, buyer, market, and conversion objective
2. Source documents, revisions, evidence, and missing inputs
3. First-screen and content-module inventory
4. Buyer-decision gap analysis
5. H1, Title, Description, Schema, canonical, and internal-link findings
6. Proposed module order and required Product data
7. Critical, High, Medium, and Low findings
8. RFQ/CTA, form fields, context, and tracking requirements
9. Affected files, dependencies, risks, and approvals
10. Validation plan for facts, desktop/mobile rendering, links, downloads, forms, metadata, schema, tracking, accessibility, and performance

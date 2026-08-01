# Industrial B2B Search Intent Analysis Model

> Codex internal execution rules. Use this model to classify industrial procurement keywords, select the correct page type, and define the content modules required to satisfy the buyer.

## Scope

Apply to overseas English-language websites for:

- Industrial machinery and production equipment
- Electrical equipment, protection, control, and power distribution
- Industrial components, replacement parts, and custom/OEM parts
- Industrial Solutions, Applications, technical resources, and supplier evaluation

Search volume alone must not determine page strategy. Every keyword must connect to a real buyer, task, product/solution, preferred page, verified content requirement, and next action.

## Required Evidence

Use available evidence in this order:

1. GSC query-to-page data for the target country/device
2. Sales inquiries, RFQs, CRM categories, support questions, and distributor feedback
3. Approved product taxonomy, technical documents, and Solution/Application scope
4. Current target-market Google result types when research is authorized
5. GA4 landing-page and buyer-path behavior
6. Third-party keyword data as directional evidence only

Record market, language, device, and date. If evidence is incomplete, label the analysis as a hypothesis and assign Medium or Low confidence.

# Buyer Journey

## Awareness

### Buyer state

The buyer recognizes a problem, process need, technology, equipment family, or component function but may not know the correct product or solution.

### Typical purposes

- Understand a technology or component
- Identify equipment for a process
- Diagnose a general industrial problem
- Learn why a failure or inefficiency occurs
- Explore possible application methods

### Query patterns

- `what is [technology/component]`
- `equipment for [process]`
- `[industrial problem] causes`
- `how to improve [process/result]`
- `[application] methods`
- `types of [equipment/component]`

### Suitable page types

- Knowledge/Blog guide
- Application overview
- Solution hub
- Product Category when the query explicitly requests equipment/product types
- FAQ for a narrow recurring question

### Required content modules

- Direct definition or problem statement
- Industrial operating context
- Relevant types, causes, methods, or product families
- Decision boundaries and safety limitations
- Link to the appropriate Category, Solution, or Application page
- Low-friction CTA: explore products, view applications, or download a guide

### Failure conditions

- Sending a broad problem query directly to an RFQ form
- Using a specific Product page with no educational context
- Publishing generic awareness content unrelated to company expertise

## Consideration

### Buyer state

The buyer understands the basic need and is comparing products, technologies, materials, applications, solution approaches, or suppliers.

### Typical purposes

- Compare product types or technical methods
- Select a product family for an application
- Evaluate a Solution for an industry/process
- Review supplier manufacturing, quality, and support capability
- Understand standards, materials, and configuration trade-offs

### Query patterns

- `[type A] vs [type B]`
- `how to choose [equipment/component]`
- `[product] for [application]`
- `[material/technology] advantages`
- `[product category] manufacturer`
- `[solution] for [industry/process]`
- `[rating/standard] selection`

### Suitable page types

- Product Category
- Solution page
- Application page
- Comparison or selection guide
- Manufacturing/quality/capability page
- Case Study as evidence

### Required content modules

- Selection inputs and evaluation criteria
- Product, technology, material, or Solution options
- Equivalent comparison data and trade-offs
- Applications, limitations, compatibility, standards, and risks
- Manufacturing, testing, quality, documentation, and case evidence
- Links to Product details, Solution/Application pages, and technical resources
- CTA: compare products, request selection support, or discuss application

### Failure conditions

- Generic benefits with no selection criteria
- Product page claims one option is always superior
- Supplier page lacks proof of capability
- Comparison uses inconsistent ratings, units, or test conditions

## Decision

### Buyer state

The buyer is validating an exact product, model, configuration, supplier, document, standard, compatibility requirement, or project fit before specification or inquiry.

### Typical purposes

- Confirm exact specifications, options, and documents
- Validate compatibility, standards, ratings, and application fit
- Request quote, sample, customization, engineering review, or distributor information
- Verify supplier identity, certification, quality, and support
- Prepare final project or RFQ inputs

### Query patterns

- `[model] specifications/datasheet/drawing/manual`
- `[material/rating/standard] [product]`
- `[product] supplier/manufacturer/quote`
- `custom/OEM [component/equipment]`
- `[brand/model] distributor`
- `[solution] consultation`
- `[product] compatibility/replacement`

### Suitable page types

- Product Detail
- Product Category for multi-product sourcing
- Solution/Application page for project validation
- Technical resource with HTML context
- Company/capability/contact page
- Case Study as supporting proof

### Required content modules

- Exact product/model or project identity
- Verified specifications, options, materials, standards, interfaces, and limitations
- Technical documents and revision information
- Manufacturing, testing, quality, certification, and case proof
- Product-specific or project-specific inquiry path
- Required RFQ inputs, upload, and next steps

### Failure conditions

- Exact model keyword mapped to Homepage
- Decision data hidden only in a PDF with an empty HTML page
- Price, stock, compatibility, certification, or delivery inferred without evidence
- Inquiry loses product/model or Solution context

# Keyword Intent Classification

Every keyword cluster must receive one primary intent. Add one secondary intent only when the query genuinely crosses two buyer tasks.

## Product Intent

### Definition

The buyer seeks a product family, subtype, model, configuration, material, rating, manufacturer, supplier, document, or quote.

### Signals

- Product/category/model name
- Material, size, rating, capacity, voltage, load, or configuration modifier
- Manufacturer, supplier, custom, OEM, price, quote, datasheet, drawing, or catalog

### Page mapping

| Query scope | Preferred page |
|---|---|
| Broad product family | Product Category |
| Defined subtype | Subcategory or Category section |
| Exact product/model | Product Detail |
| Multi-product manufacturer/supplier | Category or capability-supported commercial page |
| Exact document | Product Detail plus approved resource |

### Required decision

Determine whether the buyer expects range selection or exact product validation.

## Application Intent

### Definition

The buyer seeks product/equipment suitability for an industry, process, machine, material, medium, environment, or operating condition.

### Signals

- `[product] for [application]`
- `[equipment] for [industry/process]`
- `[component] used in [machine/system]`
- `[product] for high temperature/corrosion/washdown/hazardous environment`

### Page mapping

- Application page for operating context and suitability
- Solution page when products/process steps form an integrated approach
- Category page when the buyer wants a range for one Application
- Product page when one exact product has a verified primary Application
- Knowledge/Blog when the query asks how to evaluate or select

### Required decision

Determine whether the main task is “Where/how is this used?” or “How is the system/problem solved?”

## Solution Intent

### Definition

The buyer seeks an approach to an industrial problem, system requirement, production process, integration need, or target outcome.

### Signals

- `[problem] solution`
- `[process] automation solution`
- `[industry] production line/system solution`
- `reduce/prevent [industrial issue]`
- `[system] protection/control/monitoring solution`

### Page mapping

- Solution page for problem, architecture, workflow, product combination, and project approach
- Application page when operating context is primary and no integrated approach is required
- Knowledge/Blog for general diagnosis or method explanation
- Product page only when one product directly and completely serves the intent

### Required decision

Identify the problem, technical inputs, constraints, products, interfaces, evidence, and project consultation need.

## Technical Intent

### Definition

The buyer seeks specifications, standards, principles, calculations, compatibility, installation, testing, maintenance, troubleshooting, or engineering explanation.

### Signals

- `[product] specifications/dimensions/rating`
- `how to size/install/test/maintain [product]`
- `[standard] requirements`
- `[failure] causes/troubleshooting`
- `[material] compatibility`
- `[technology] working principle`

### Page mapping

- Product Detail for model-specific specifications and documents
- Category/Solution for selection criteria and system requirements
- Knowledge/Blog for explanation, method, procedure, maintenance, or troubleshooting
- FAQ for narrow recurring questions
- Manual/drawing/certificate as a supporting resource

### Required decision

Determine whether the query is model-specific or general and whether it requires qualified engineering, electrical, machine-safety, pressure, thermal, chemical, or regulatory review.

## Comparison Intent

### Definition

The buyer compares types, products, technologies, materials, configurations, standards, suppliers, or replacement alternatives.

### Signals

- `[A] vs [B]`
- `[product] comparison`
- `difference between [A] and [B]`
- `best type for [application]`
- `[material/technology] advantages and disadvantages`
- `[model] alternative/replacement`

### Page mapping

- Product Category for structured comparison across the range
- Comparison/selection guide for complex criteria and explanation
- Product Detail for verified adjacent models or compatible alternatives
- Solution page for comparing system approaches under defined requirements
- Case Study only as supporting evidence, not a complete comparison

### Required decision

Confirm that compared items are equivalent enough to compare and that units, conditions, source revisions, trade-offs, and limitations are available.

### Comparison rules

- Do not declare a universal winner.
- Do not compare specifications measured under different conditions without disclosure.
- Mark missing, optional, custom, and not-applicable values accurately.
- Competitor comparisons require factual, fair, approved, and legally appropriate treatment.

# Page Matching Rules

## Primary mapping matrix

| Keyword/intent | Preferred page | Supporting pages |
|---|---|---|
| Broad Product keyword | Product Category | Product Details, Applications, selection guide |
| Exact Product/model keyword | Product Detail | Category, Solution, documents, FAQ |
| Application keyword | Solution/Application Page | Products, Category, Case, technical guide |
| Solution keyword | Solution Page | Products, Applications, Cases, Blog/FAQ |
| Model-specific Technical keyword | Product Detail | Manual, datasheet, FAQ |
| General Technical keyword | Knowledge/Blog | Category, Product, Solution, resource |
| Comparison keyword | Category or comparison guide | Product Details, Solution, selection support |
| Company/supplier validation keyword | Homepage/capability page | Category, quality, cases, contact |

## Page-role rules

### Homepage

Use for company/brand and core commercial positioning. Do not use Homepage to compete for exact products, models, Applications, or technical questions.

### Product Category

Use for broad product-family discovery, classification, filtering, comparison, and selection.

### Product Detail

Use for exact product/model specifications, options, Applications, documents, proof, and RFQ.

### Solution/Application Page

Use Solution for a problem/system approach and Application for operating context/product suitability. Do not merge these roles without a clear buyer reason.

### Knowledge/Blog

Use for technical, comparison, selection, implementation, maintenance, troubleshooting, and sourcing questions. Link to the preferred commercial page.

### FAQ/Resource

Use FAQ for narrow recurring questions and Resource for approved documents/evidence. They support, rather than replace, the primary HTML page.

## Existing page, new page, or consolidation

Use an existing page when it matches the entity and buyer task and can answer the need without changing its core role.

Create a new page only when:

- Product, model, Application, Solution, standard, market, or buyer task is materially different.
- Verified source material and expertise are available.
- The page has a defined hierarchy, internal links, and CTA.
- No current page can fulfill the task without role conflict.

Consolidate or reposition when multiple pages serve the same task, overlap heavily in GSC, receive competing anchors, and provide no distinct value.

URL, redirect, canonical, noindex, merge, or removal actions require approval.

## Content module recommendation matrix

| Intent | Required content modules |
|---|---|
| Product | Identity, range/model, parameters, options, Applications, limits, proof, documents, CTA |
| Application | Context, requirements, operating conditions, suitable products, limits, Solutions, cases, CTA |
| Solution | Pain points, inputs, technical approach, products, interfaces, process, evidence, FAQ, consultation |
| Technical | Direct answer, variables, method/principle, standards, units, safety boundary, source, links |
| Comparison | Compared scope, criteria, equivalent data, trade-offs, limits, recommendation logic, next step |

# Incorrect Matching Cases

## Case 1 — Homepage competing for a specific Product keyword

**Keyword:** `250 A molded case circuit breaker`

**Wrong page:** Homepage

**Why wrong:** Decision-stage Product intent requires exact ratings, standards, options, and documents.

**Correct page:** Relevant Product Detail, supported by Category.

## Case 2 — Product Detail receiving industry Solution intent

**Keyword:** `electrical protection solution for chemical plants`

**Wrong page:** One circuit breaker Product page

**Why wrong:** Buyer expects plant requirements, system architecture, protection coordination, products, standards, and project support.

**Correct page:** Chemical-industry Solution page with linked Product details.

## Case 3 — Category keyword mapped to one model

**Keyword:** `industrial air compressors`

**Wrong page:** A single 90 kW compressor model

**Why wrong:** Buyer expects range exploration and selection.

**Correct page:** Product Category.

## Case 4 — Application keyword mapped to generic Product grid

**Keyword:** `gearbox for washdown conveyor`

**Wrong page:** Gearbox listing with no washdown requirements

**Why wrong:** Buyer needs corrosion, sealing, material, load, cleaning, and compatibility guidance.

**Correct page:** Application/Solution page or verified Application section linked to suitable Products.

## Case 5 — Technical keyword mapped to sales copy

**Keyword:** `how to size a hydraulic cylinder`

**Wrong page:** Product page with “Contact us for the best cylinder” and no method

**Why wrong:** Buyer expects variables, calculation boundaries, units, assumptions, and engineering review.

**Correct page:** Knowledge/Blog guide linked to Category/Product selection support.

## Case 6 — Comparison intent split across duplicate Blogs

**Keywords:** `MCCB vs MCB`, `difference between MCB and MCCB`, `MCCB and MCB comparison`

**Wrong layout:** Three near-duplicate articles

**Why wrong:** Same buyer task and content requirement cause internal competition.

**Correct page:** One complete comparison guide with natural variants and links to Categories.

## Case 7 — Solution keyword mapped to Product Category

**Keyword:** `automated end-of-line packaging solution`

**Wrong page:** Category containing packaging machine cards only

**Why wrong:** Buyer expects line flow, integration, controls, equipment roles, implementation, and case evidence.

**Correct page:** Solution page.

## Case 8 — Product keyword mapped to general Blog

**Keyword:** `stainless steel flexible coupling manufacturer`

**Wrong page:** “What Is a Flexible Coupling?” article

**Why wrong:** Commercial supplier-selection intent requires range, material, manufacturing, quality, and inquiry information.

**Correct page:** Category or Product/capability-supported commercial page.

## Case 9 — Specific document intent mapped to PDF only

**Keyword:** `[model] installation manual`

**Wrong page:** Uncontextualized file with no product/version page

**Why wrong:** Buyer cannot confirm model scope, revision, status, or related support.

**Correct page:** Product Detail or resource context page linking to the approved manual.

## Case 10 — Unsafe technical query answered without qualification

**Keyword:** `how to test live switchgear`

**Wrong page:** Simplified steps for unqualified readers

**Why wrong:** Electrical safety, legal, and project-context risk.

**Correct action:** Provide approved high-level boundaries and qualified-professional guidance after technical review.

# Codex Analysis Workflow

When Codex receives one keyword or a keyword list, execute the following sequence.

## Step 1 — Determine search stage

Assign:

- Awareness
- Consideration
- Decision

Record the evidence and confidence level.

Questions:

- Does the buyer know the product/model?
- Is the buyer learning, comparing, validating, specifying, or sourcing?
- Does the query include quote, supplier, model, datasheet, standard, or compatibility signals?

## Step 2 — Determine user purpose

Assign one primary intent:

- Product Intent
- Application Intent
- Solution Intent
- Technical Intent
- Comparison Intent

Record secondary intent only when necessary.

Extract:

- Product/model entity
- Application/industry/process/environment
- Standard/rating/material/technical modifier
- Supplier/custom/quote/document modifier
- Required buyer outcome

## Step 3 — Recommend page type

Choose one:

- Homepage
- Product Category
- Product Detail
- Solution
- Application
- Knowledge/Blog
- FAQ/Resource
- Capability/Contact/Case as supporting page

Then:

- Map one existing canonical URL, or
- Recommend a new page with justification, or
- Recommend consolidation/repositioning after impact review

Do not recommend a new URL for singular/plural, word order, or close variants with the same task.

## Step 4 — Recommend content modules

Define:

- Required page opening and H1 direction
- Main decision questions
- Product/specification/application/solution information
- Standards, evidence, cases, and sources needed
- Assumptions, limits, compatibility, and safety boundaries
- Internal links to parent, child, supporting, evidence, and conversion pages
- CTA appropriate to stage
- Missing inputs and technical review requirements

## Step 5 — Check competition and feasibility

- Compare existing Titles, H1s, content, canonicals, GSC queries, internal anchors, and page roles.
- Confirm that the company can produce verified differentiated content.
- Check product and business relevance.
- Flag URL/index changes for approval.

## Step 6 — Assign priority and measurement

Score 0–3 on:

- Business relevance
- Buyer intent strength
- Product/Solution fit
- Demand evidence
- Current performance gap
- Verified content capability
- Conversion-path readiness

Define baseline and KPI: visibility, target landing behavior, product/Solution progression, download, selection support, RFQ, or qualified inquiry.

## Required Codex output

| Keyword cluster | Representative queries | Buyer role | Stage | Primary intent | Secondary intent | User purpose | Recommended page type | Existing/proposed URL | Required modules | Internal links | CTA | Evidence | Confidence | Priority/risk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|  |  |  | Awareness/Consideration/Decision | Product/Application/Solution/Technical/Comparison |  |  |  |  |  |  |  |  | High/Medium/Low |  |

## Codex final checklist

- [ ] Target market, language, buyer role, device, and date are recorded where relevant
- [ ] Keyword is assigned to Awareness, Consideration, or Decision
- [ ] One primary Product, Application, Solution, Technical, or Comparison intent is assigned
- [ ] User purpose is stated as a concrete task
- [ ] Recommended page type can complete that task
- [ ] One preferred canonical URL is assigned
- [ ] GSC, SERP, sales/support, taxonomy, or technical evidence is recorded
- [ ] Existing page overlap and internal competition are checked
- [ ] Content modules match the stage and intent
- [ ] Required facts, standards, evidence, and technical review are identified
- [ ] Internal links connect the buyer to the appropriate commercial next step
- [ ] CTA matches the buyer stage
- [ ] New page recommendation has unique value and hierarchy
- [ ] Confidence, priority, risk, KPI, and validation method are stated
- [ ] URL, redirect, canonical, noindex, merge, or removal actions are flagged for approval

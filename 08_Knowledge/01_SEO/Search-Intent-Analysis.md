# Industrial Buyer Search Intent Analysis Framework

> Internal execution rules for Codex. Use this framework to analyze keyword architecture and page targeting for overseas industrial B2B websites.

## 1. Purpose and Operating Principle

Search-intent analysis must determine what an industrial buyer is trying to understand, compare, validate, specify, or source—and then assign that need to the page type capable of answering it completely.

Codex must not build keyword layouts from search volume alone. Every keyword cluster must connect to:

- A defined buyer role
- A purchasing stage
- A product, application, solution, technical task, or brand need
- One preferred canonical page
- A complete content requirement
- A relevant next buyer action

One keyword may have mixed intent. Codex must assign one primary intent, optional secondary intent, and a confidence level based on evidence.

## 2. Required Inputs

Before classifying keywords, collect or confirm:

- Target countries, languages, and regional terminology
- Product categories, product models, applications, solutions, and industries
- Buyer roles: engineer, procurement manager, project owner, OEM, integrator, distributor, maintenance, or operations
- Existing URL inventory by page type
- Current Titles, H1s, canonicals, internal links, and index status
- GSC queries, pages, countries, devices, clicks, impressions, CTR, and position
- GA4 landing-page and conversion-path data
- Sales inquiries, RFQ fields, CRM categories, support questions, and distributor feedback
- Approved product documents, standards, certifications, and technical expertise
- Target-market SERP result types when research is authorized

If data is unavailable, label the result as a hypothesis and state what is required to validate it.

## 3. Buyer Search Stages

### 3.1 Awareness

#### Buyer objective

Identify a problem, technology, equipment type, component family, or possible method. The buyer may not yet know the correct product name.

#### Typical query patterns

- `what is [technology/component]`
- `[industrial problem] causes`
- `equipment for [process]`
- `how to improve [process/result]`
- `[application] methods`
- `[system] basics`

#### Suitable page types

- Educational blog or guide
- Application overview
- Solution hub
- Product category when the query clearly requests equipment/product types
- FAQ for narrow questions

#### Required content

- Clear definition and operating context
- Problem causes, process requirements, or technology options
- Relevant terminology and selection boundaries
- Link to the appropriate product category or solution
- Low-friction CTA such as viewing applications, exploring equipment types, or downloading a guide

#### Do not

- Force an RFQ-first experience before explaining the topic
- Target a broad problem query with a thin product page
- Create generic awareness content unrelated to an actual company capability

### 3.2 Consideration

#### Buyer objective

Compare product types, technologies, configurations, materials, suppliers, or solution approaches and reduce the available choices.

#### Typical query patterns

- `[type A] vs [type B]`
- `how to choose [equipment/component]`
- `[product] for [application]`
- `[material/technology] advantages`
- `[rating/standard] selection`
- `[product category] manufacturer`
- `[solution] for [industry/process]`

#### Suitable page types

- Product category
- Solution or application page
- Comparison/selection guide
- Capability or supplier-validation page
- Case study

#### Required content

- Selection criteria and buyer inputs
- Meaningful options and trade-offs
- Applications, limitations, compatibility, and standards
- Product/solution relationships
- Manufacturing, quality, customization, or support evidence
- Links to specific products, cases, resources, and selection assistance

#### Do not

- Present every option as equally suitable
- Use generic benefits instead of comparison criteria
- Target comparison intent with a model page that cannot explain alternatives

### 3.3 Decision

#### Buyer objective

Validate a specific product, model, supplier, configuration, standard, or project fit and take a commercial or technical action.

#### Typical query patterns

- `[model] specifications`
- `[product] datasheet/drawing/manual`
- `[product] supplier/manufacturer`
- `[product] price/quote`
- `[standard/material/rating] [product]`
- `custom [component/equipment] manufacturer`
- `[brand/model] distributor`
- `[solution] consultation`

#### Suitable page types

- Product detail
- Product category for multi-product sourcing intent
- Solution/application page for project validation
- Technical resource
- Company/capability/contact page
- Case study as supporting evidence

#### Required content

- Exact product/model identity
- Verified specifications, options, standards, compatibility, and limitations
- Technical and quality evidence
- Supplier role, customization, documentation, and support capability
- RFQ requirements, drawing upload, selection support, or contact path
- Product/solution context preserved in the inquiry

#### Do not

- Send a specific model query to a generic homepage
- Claim price, stock, certification, or compatibility without verified data
- Hide all decision information inside a PDF

## 4. Keyword Classification

Every keyword cluster must receive one primary keyword type. A secondary type may be recorded when the query genuinely crosses categories.

### 4.1 Product Keyword

#### Definition

Names a product family, product type, model, configuration, material, rating, or sourcing role.

#### Common patterns

- `[product category]`
- `[product/model]`
- `[material/rating] [product]`
- `[product] manufacturer/supplier`
- `custom/OEM [product]`
- `[product] price/quote/datasheet`

#### Default page match

| Query scope | Preferred page |
|---|---|
| Broad product family | Product category |
| Defined subtype | Subcategory or category section |
| Exact model/product | Product detail |
| Multi-product supplier sourcing | Category or capability page |
| Quote for a configured item | Product detail/RFQ path |

#### Required analysis

- Is the query broad or model-specific?
- Does the buyer need selection or exact specifications?
- Is “manufacturer” factually correct for the company?
- Are material, rating, standard, and compatibility claims verified?
- Does another page already own this product intent?

### 4.2 Application Keyword

#### Definition

Connects equipment or components to an industry, process, machine, environment, medium, or operating condition.

#### Common patterns

- `[product] for [application]`
- `[equipment] for [industry/process]`
- `[component] used in [machine/system]`
- `[product] for high temperature/corrosive/washdown/hazardous environment`

#### Default page match

- Application page when the main need is context and suitability
- Solution page when several products/process steps form an approach
- Category page when the buyer wants a range for one application
- Product page when one specific product has a proven primary application
- Blog when the query requests explanation or selection guidance

#### Required analysis

- Does the page contain application-specific requirements?
- Are environment, load, medium, standards, interfaces, and limitations addressed?
- Is the application verified for the product?
- Would a separate page add unique buyer value or only duplicate another page?

### 4.3 Solution Keyword

#### Definition

Expresses a problem to solve, outcome to achieve, system/process need, or integrated industrial approach.

#### Common patterns

- `[problem] solution`
- `[process] automation solution`
- `[industry] production line solution`
- `reduce/prevent [industrial issue]`
- `[system] protection/control solution`

#### Default page match

- Solution page for a defined problem, architecture, workflow, or integrated approach
- Application page when the focus is operating context rather than system design
- Blog/guide for educational diagnosis or method comparison
- Product page only when one product directly and completely serves the intent

#### Required analysis

- What problem or requirement is being solved?
- What inputs, constraints, products, processes, and evidence are required?
- Does the page explain an approach or merely list products?
- Are outcome claims conditional and verified?
- Is project consultation the correct next step?

### 4.4 Technical Keyword

#### Definition

Requests specifications, standards, calculations, compatibility, installation, testing, maintenance, failure diagnosis, or engineering explanation.

#### Common patterns

- `[product] specifications/dimensions/rating`
- `how to size/select/install/test [product]`
- `[standard] requirements`
- `[type A] vs [type B]`
- `[failure] causes/troubleshooting`
- `[material] compatibility`

#### Default page match

- Product detail for model-specific specifications
- Category/solution for selection criteria
- Technical guide/blog for explanation, comparison, calculation, or procedure
- FAQ for narrow recurring questions
- Datasheet/manual/drawing as supporting resource, not the only indexable answer where HTML content is needed

#### Required analysis

- Is the query product-specific or general?
- Does answering it require calculations, standards, safety review, or project inputs?
- Can the company provide approved technical evidence?
- What limitations and professional-review boundaries must be stated?
- Could the query have dangerous consequences if answered incompletely?

### 4.5 Brand Keyword

#### Definition

Includes the company, product brand, model family, competitor, or supplier identity.

#### Common patterns

- `[brand/company]`
- `[brand] products/catalog/contact`
- `[brand] [product/model]`
- `[brand] distributor/supplier`
- `[brand A] vs [brand B]`

#### Default page match

- Homepage for company/brand navigation
- Category or product detail for branded products/models
- Contact, distributor, catalog, or capability page for the stated task
- Comparison content only when accurate, fair, supportable, and legally appropriate

#### Required analysis

- Is the brand owned, distributed, supplied, or merely mentioned?
- Is the company authorized to make distributor/compatibility claims?
- Does the query require company validation, product information, or contact?
- Could competitor targeting create trademark, accuracy, or reputation risk?

Do not create misleading pages implying affiliation with another brand.

## 5. Page Matching Rules

### 5.1 Intent-to-page matrix

| Buyer need | Primary keyword type | Stage | Preferred page | Required next step |
|---|---|---|---|---|
| Understand an industrial problem | Solution/Technical | Awareness | Guide or solution hub | Explore solution/application |
| Explore a product family | Product | Awareness/Consideration | Category | Compare types/products |
| Find equipment for an application | Application/Product | Consideration | Application, solution, or category | Review fit/select product |
| Compare technologies or types | Technical/Product | Consideration | Comparison guide/category | Use selection support |
| Validate a specific model | Product/Technical | Decision | Product detail | Download data/request quote |
| Solve a system/process requirement | Solution | Consideration/Decision | Solution page | Discuss project |
| Verify a supplier | Brand/Product | Consideration/Decision | Homepage/capability/category | Contact/review capability |
| Find installation/maintenance help | Technical | Decision/post-purchase | Guide/manual/FAQ | Technical support |

### 5.2 Matching workflow

For every cluster:

1. Normalize obvious variants without losing model numbers, standards, or regional terminology.
2. Identify entities and modifiers.
3. Assign buyer role and Awareness, Consideration, or Decision stage.
4. Assign Product, Application, Solution, Technical, or Brand as the primary keyword type.
5. Review SERP result types and GSC page/query behavior when evidence is available.
6. Define the complete buyer task.
7. Select the page type able to complete that task.
8. Map one preferred canonical URL or identify a genuine page gap.
9. Check competing internal URLs.
10. Define content requirements, internal links, CTA, and KPI.

### 5.3 Existing page, new page, or consolidation

Use an existing page when its primary entity and intent match and it can answer the full need without changing its core purpose.

Create a new page only when:

- The intent, product entity, application, solution, standard, market, or buyer task is materially distinct.
- Verified content and technical evidence are available.
- The page has a defined place in the hierarchy.
- Internal links and a conversion path are planned.

Consolidate or reposition pages when several URLs serve the same intent, provide similar answers, or compete in GSC without a clear business distinction.

URL, redirect, canonical, or indexation changes require approval.

## 6. Content Coverage Rules

### 6.1 Coverage by buyer stage

#### Awareness coverage

- Problem or technology definition
- Operating context and terminology
- Common causes, approaches, or product families
- Decision boundaries and links to commercial hubs

#### Consideration coverage

- Selection criteria
- Type, technology, material, configuration, or supplier comparison
- Applications, limitations, compatibility, and standards
- Evidence, cases, and manufacturing/support capability

#### Decision coverage

- Exact product/model specifications
- Options, drawings, standards, tests, documentation, and quality evidence
- Customization, ordering inputs, selection support, and inquiry path
- Project-specific validation requirements

### 6.2 Coverage by keyword type

| Keyword type | Mandatory coverage |
|---|---|
| Product | Definition, range/model, specifications, options, applications, limitations, proof, CTA |
| Application | Environment, process, requirements, suitable products, limitations, cases, next step |
| Solution | Challenge, inputs, approach, products, implementation, evidence, assumptions, consultation |
| Technical | Direct answer, variables, method, standards, units, safety boundaries, source, deeper resource |
| Brand | Identity, role, product/capability scope, trust evidence, official navigation/contact |

### 6.3 Industrial content requirements

Address relevant factors:

- Machinery: material/process, output, accuracy, capacity, utilities, integration, safety, commissioning, maintenance
- Electrical equipment: voltage, current, power, frequency, protection, derating, enclosure, standards, installation, qualified safety review
- Industrial components: material, dimensions, tolerances, load, speed, pressure, temperature, medium, fit, compatibility, wear, quality control

Do not invent missing specifications, compatibility, certification, performance, or project results.

### 6.4 Cluster completeness rule

A keyword cluster is incomplete when:

- It attracts awareness traffic but has no category/solution path.
- It has commercial pages but no selection or validation support for complex products.
- Product pages lack applications and technical proof.
- Solution pages lack products, implementation logic, and evidence.
- Technical content lacks safety boundaries or review.
- Pages do not connect to a measurable next action.

## 7. Search Intent Error Cases

### Case 1 — Broad category keyword assigned to a model page

**Keyword:** `industrial air compressors`

**Wrong page:** One specific 90 kW model.

**Why wrong:** The buyer expects a product-family overview and selection options.

**Correct match:** Product category; link to individual models.

### Case 2 — Specific model keyword assigned to homepage

**Keyword:** `[model] circuit breaker datasheet`

**Wrong page:** Company homepage.

**Why wrong:** Decision-stage technical intent requires exact model data.

**Correct match:** Product detail plus current datasheet resource.

### Case 3 — Application keyword treated as a generic product category

**Keyword:** `gearbox for washdown conveyor`

**Wrong page:** Generic gearbox grid with no environment information.

**Why wrong:** The buyer needs washdown, corrosion, sealing, material, and compatibility guidance.

**Correct match:** Application/solution or a category section with verified washdown selection content.

### Case 4 — Solution keyword assigned to a product list

**Keyword:** `packaging line automation solution`

**Wrong page:** Cards for unrelated packaging machines.

**Why wrong:** The query expects system requirements, workflow, integration, controls, products, and implementation.

**Correct match:** Solution page with linked product details.

### Case 5 — Technical selection query assigned to a sales page

**Keyword:** `MCCB vs MCB for industrial panel`

**Wrong page:** MCCB product page claiming it is always better.

**Why wrong:** The buyer expects an objective comparison with ratings, protection needs, standards, and limitations.

**Correct match:** Qualified comparison guide linking to relevant categories/products.

### Case 6 — Brand keyword used misleadingly

**Keyword:** `[competitor brand] distributor`

**Wrong page:** Page implying authorization that does not exist.

**Why wrong:** Misleading affiliation and trust risk.

**Correct action:** Do not target unless the relationship is verified and approved.

### Case 7 — Awareness query forced directly to RFQ

**Keyword:** `why conveyor belts mistrack`

**Wrong page:** Contact form with no explanation.

**Why wrong:** The buyer needs causes, inspection boundaries, and corrective options before inquiry.

**Correct match:** Technical guide with appropriate support CTA.

### Case 8 — Same intent split across multiple blogs

**Keywords:** `how to choose an industrial motor`, `industrial motor selection guide`, `selecting motors for industry`

**Wrong layout:** Three near-duplicate articles.

**Why wrong:** Same buyer task and content requirement; creates internal competition.

**Correct match:** One comprehensive preferred guide with natural variants.

### Case 9 — Product keyword assigned to a Blog despite strong commercial intent

**Keyword:** `stainless steel flexible coupling manufacturer`

**Wrong page:** Generic “What Is a Flexible Coupling?” blog.

**Why wrong:** Buyer is evaluating a product/supplier, not seeking a basic definition.

**Correct match:** Category or capability-supported product page.

### Case 10 — Unsafe technical intent answered without qualification

**Keyword:** `how to test live switchgear`

**Wrong page:** Simplified step-by-step instructions for unqualified users.

**Why wrong:** Electrical safety and legal risk; context and qualifications are missing.

**Correct action:** Provide safe high-level boundaries, applicable standards, and qualified-professional guidance after technical review.

## 8. Codex Keyword Layout Output

Codex must use this table:

| Keyword cluster | Representative queries | Buyer role | Stage | Primary type | Secondary type | Intent/task | Preferred page type | Existing/proposed URL | Required coverage | Internal links | CTA | Evidence | Confidence | Risk/action |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|  |  |  | Awareness/Consideration/Decision | Product/Application/Solution/Technical/Brand |  |  |  |  |  |  |  |  | High/Medium/Low |  |

### Confidence definitions

- **High:** supported by consistent GSC, SERP, product taxonomy, and buyer evidence
- **Medium:** supported by some evidence but needs page/query validation
- **Low:** preliminary hypothesis with limited or conflicting evidence

### Priority scoring

Score 0–3 for:

- Business relevance
- Buyer intent strength
- Product/solution fit
- Demand evidence
- Current performance gap
- Ability to provide verified differentiated content
- Conversion-path readiness

Search volume alone cannot make a keyword high priority.

## 9. Codex Final Checklist

- [ ] Target market, language, buyer role, and terminology are defined
- [ ] Every cluster is assigned to Awareness, Consideration, or Decision
- [ ] Every cluster has one primary Product, Application, Solution, Technical, or Brand type
- [ ] Primary and secondary intent are separated
- [ ] GSC, SERP, sales/support, or product-taxonomy evidence is recorded
- [ ] One preferred canonical page is assigned to each primary intent
- [ ] Page type can complete the buyer’s task
- [ ] Existing pages and cannibalization were checked
- [ ] New page recommendations have verified content, hierarchy, links, and conversion plans
- [ ] Content requirements cover the correct stage and keyword type
- [ ] Machinery, electrical, or component-specific factors are included where relevant
- [ ] Technical claims, standards, compatibility, and safety boundaries are verified
- [ ] CTA matches the buyer stage
- [ ] Confidence, risk, and validation requirement are stated
- [ ] URL, redirect, canonical, or index changes are flagged for approval

# Search Intent Analysis for Industrial B2B Websites

## 1. Purpose

This rule converts search queries into buyer needs, appropriate page types, and measurable actions. Codex must not classify intent from one keyword alone; use the query pattern, SERP, target market, product context, GSC data, and buyer journey together.

## 2. Required Evidence

Use available evidence in this order:

1. GSC query-to-page data for the target country and device
2. Current Google SERP composition and recurring result types
3. Website product taxonomy and technical source documents
4. Sales inquiries, RFQs, CRM categories, support questions, and distributor feedback
5. Competitor page patterns as secondary evidence only
6. Third-party volume or difficulty data as directional, not definitive

Record market, language, device, and date because SERPs and terminology vary.

## 3. Industrial Buyer Intent Model

| Intent | Typical signals | Buyer need | Preferred page |
|---|---|---|---|
| Brand/navigation | brand, company, contact, location | Find or verify supplier | Homepage, about, contact |
| Product discovery | product family, types, manufacturer | Understand available range | Category |
| Product specification | model, size, material, standard, datasheet | Validate technical fit | Product detail/resource |
| Application/solution | for [industry/process], problem, system | Solve an operational need | Solution/application |
| Comparison/selection | vs, difference, selection, sizing | Choose between alternatives | Category, guide, solution |
| Supplier validation | factory, OEM, certification, capacity | Reduce sourcing risk | Capability, about, category |
| Implementation | installation, configuration, maintenance | Use product correctly | Guide, manual, FAQ |
| Troubleshooting | failure, cause, repair, issue | Resolve a problem | Technical guide/FAQ |
| Transaction/inquiry | quote, supplier, price, custom, bulk | Contact or source | Product/category/contact |

A single query may have mixed intent. Mark one primary intent, any secondary intent, and the confidence level.

## 4. Buyer Journey Stages

| Stage | Buyer question | Required content |
|---|---|---|
| Discover | What products or methods address this need? | Clear definitions and solution context |
| Understand | How does it work and where is it used? | Technical explanation and applications |
| Compare | Which type, material, or supplier is suitable? | Criteria, options, trade-offs |
| Validate | Does it meet specifications, standards, and risk requirements? | Data, certificates, testing, cases |
| Specify | What exact model/configuration should be selected? | Tables, drawings, compatibility, support |
| Inquire | Can the supplier deliver, customize, and support the project? | Capability, form, required RFQ fields, response path |

## 5. Query Analysis Workflow

For each query or cluster:

1. Normalize spelling and obvious variants without losing model numbers or standards.
2. Identify entities: product, material, standard, industry, application, problem, geography, brand, or model.
3. Identify modifiers: manufacturer, supplier, custom, price, specification, size, comparison, installation, or troubleshooting.
4. Review the target-market SERP and record dominant page/result types.
5. Identify buyer role and journey stage.
6. Assign primary intent, secondary intent, and confidence: high, medium, or low.
7. Select the page type able to satisfy the complete need.
8. Map to one existing canonical URL or mark a genuine content gap.
9. Check whether another internal URL targets the same intent.
10. Define the next buyer action and measurement signal.

## 6. SERP Review Standard

Record, where visible:

- Dominant result types: category, product, guide, marketplace, video, PDF, local, or brand
- Whether Google interprets the query as commercial, informational, mixed, or navigational
- Repeated subtopics, attributes, applications, standards, and questions
- Rich-result or visual features that affect the result format
- Geographic or language bias
- Major mismatch between the planned page and dominant user need

Do not copy competitors’ wording or assume the highest-ranking page is technically correct.

## 7. Page Mapping Rules

### Use an existing page when

- Its primary entity and intent match the cluster
- It can answer the full buyer need without changing its core purpose
- It is or can become the canonical preferred URL

### Improve or merge pages when

- Several URLs serve the same intent with overlapping content
- A blog ranks for a commercial query that a weak product/category page should satisfy
- Country or language variants are substantially duplicated without a real localization need
- Thin product pages differ only by trivial wording and lack independent buyer value

### Create a new page when

- Intent, product entity, application, industry, standard, or buyer task is materially distinct
- The business can provide verified and useful information
- No current page can satisfy the need without confusing its existing purpose
- The page has a defined place in site architecture and an internal-link plan

Do not create pages only to capture plural/singular, word order, or close synonym variations.

## 8. Cannibalization Test

Flag potential cannibalization when two or more indexable URLs:

- Receive impressions for the same high-value query cluster
- Have substantially similar titles, H1s, and main content
- Alternate in GSC performance without a clear page-type reason
- Receive competing internal anchor text
- Have no distinct buyer intent or canonical strategy

Before recommending merge, redirect, canonical, noindex, or repositioning, check backlinks, conversions, language/market purpose, existing rankings, and URL dependencies. URL changes require approval.

## 9. Content Requirement Output

For every approved cluster, define:

| Field | Required output |
|---|---|
| Query cluster | Representative queries and variants |
| Evidence | GSC, SERP, sales/support, or product taxonomy |
| Buyer | Role and market |
| Primary intent | One intent |
| Secondary intent | Optional |
| Journey stage | One primary stage |
| Preferred page | Page type and canonical URL |
| Required sections | Buyer questions the page must answer |
| Proof required | Specs, standards, tests, cases, certifications |
| Internal links | Parent, child, supporting, and conversion links |
| CTA | Appropriate next action |
| KPI | Visibility, engagement, or conversion measure |

## 10. Opportunity Prioritization

Score each cluster from 0–3 on:

- Business relevance
- Buyer intent strength
- Product/solution fit
- Evidence of demand
- Current performance gap
- Ability to create verified differentiated content
- Conversion path readiness

Prioritize high combined value, but downgrade opportunities with weak product fit, missing evidence, unclear ownership, or major technical dependencies. Search volume alone cannot create a high priority.

## 11. Acceptance Checklist

- [ ] Target country, language, device, and review date are recorded
- [ ] Query cluster is supported by evidence
- [ ] Buyer role and journey stage are defined
- [ ] Primary and secondary intent are separated
- [ ] SERP page types have been reviewed
- [ ] One preferred canonical page is assigned
- [ ] Cannibalization and page overlap are checked
- [ ] Required technical and commercial content is specified
- [ ] Claims and proof requirements are identified
- [ ] Internal links, CTA, and measurement are defined
- [ ] Recommendation is based on business value, not volume alone

## 12. Official Google References

- [How Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works)
- [Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)


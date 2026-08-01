# Industrial B2B Product Category Page Standard

## 1. Page Objective

A product category page must help buyers understand a product family, compare relevant types, and reach the correct product or inquiry path. It should serve broad commercial and product-family intent without duplicating individual product pages.

The page must answer:

- What products are included in this category?
- How do the types differ?
- Which applications and operating requirements do they support?
- What selection criteria matter?
- Where can the buyer find detailed specifications or request assistance?

Primary success signals include product-detail visits, filter or comparison use, datasheet/catalog engagement, and qualified inquiry actions.

## 2. Buyer Decision Path

Recommended path:

`Confirm category fit → Understand product types → Compare selection criteria → Validate capability → Select product or request guidance`

Buyer-stage support:

- Discovery: category definition, use cases, major types
- Comparison: differences, selection criteria, materials, standards, ranges
- Validation: manufacturing/quality evidence, supporting resources
- Selection: product list and specifications
- Inquiry: selection support or RFQ

## 3. Required Modules

### 3.1 Breadcrumb and category header

- Logical parent path
- Specific H1 naming the category
- Concise definition and primary application/value
- Optional category-level CTA

### 3.2 Product type navigation

- Subcategories or meaningful type groups
- Descriptive labels and representative images
- Crawlable links to canonical subcategory or product URLs
- Filters only when they reflect real buyer criteria

### 3.3 Product listing

Each product card should include, when applicable:

- Product/model name
- Product type
- Key differentiating specification or application
- Representative image
- Link to product details
- Optional compare/select action

### 3.4 Category comparison or selection guide

- Key differences between types
- Materials, standards, sizes, performance ranges, or compatibility
- Selection factors and limitations
- Clear path to engineering help when selection requires review

### 3.5 Applications

- Relevant industries, systems, processes, or environments
- Short explanation of product fit
- Links to solution or application pages

### 3.6 Category capabilities and proof

- Relevant manufacturing, customization, testing, quality, or supply capability
- Applicable certifications and standards
- Links to approved supporting evidence

### 3.7 Resources and FAQ

- Category catalog, selection guide, datasheets, manuals, or FAQs
- Questions that support category comparison rather than repeat product details

### 3.8 Conversion section

- Product selection support or category-level RFQ
- Required technical inputs such as application, medium, dimensions, standards, quantity, or drawings when relevant

## 4. Content Requirements

- Define the category in buyer language
- Explain meaningful differences, not only display a product grid
- Use verified technical attributes and consistent units
- Separate category-wide properties from product-specific specifications
- Link claims to evidence or source documents
- Explain which operating conditions require engineering confirmation
- Use original category content; do not reuse the same introduction across categories
- Provide enough information for a buyer to narrow the range
- Keep filters, product names, headings, and URLs consistent with the taxonomy

Do not claim every product supports every application. State limitations and selection dependencies where known.

## 5. CTA Design

Primary CTA options:

- Select a Product
- Request Selection Support
- Request a Quote

Secondary CTA options:

- Compare Product Types
- Download Category Catalog
- View Applications

CTA rules:

- Offer selection assistance when a direct quote requires technical inputs
- Place product-detail links on every valid product card
- Repeat the category CTA after the selection content
- Preserve buyer context when moving to a form
- Track product clicks, filter use, downloads, CTA clicks, and submissions

## 6. Common Errors

- Thin category page containing only product cards
- Category copy duplicated from the homepage or product pages
- Mixed product types with no taxonomy or selection explanation
- Filters creating uncontrolled indexable parameter URLs
- Product cards missing differentiating information
- Category page competing with a product detail page for the same intent
- Specifications applied incorrectly to the whole category
- Every product linked with the same vague anchor
- No links to applications, solutions, or selection resources
- Pagination or load-more implementation preventing product discovery
- Empty categories or discontinued products returning misleading success pages
- Generic CTA that does not support selection

## 7. Codex Checklist

### Page purpose

- [ ] Category has a defined product-family intent
- [ ] Category is distinct from its parent, children, and product pages
- [ ] H1 and introduction clearly define the included range

### Product discovery and selection

- [ ] Product types are grouped logically
- [ ] Product cards include useful distinguishing information
- [ ] Selection criteria, differences, and limitations are explained
- [ ] All listed products link to valid canonical detail pages
- [ ] Filters and pagination remain crawlable and controlled

### Content and evidence

- [ ] Category-wide facts are separated from product-specific data
- [ ] Specifications, standards, and capability claims are verified
- [ ] Relevant applications and solutions are linked
- [ ] Supporting downloads and FAQs are current and useful

### Conversion

- [ ] Direct selection and assisted-selection paths are available
- [ ] RFQ requests appropriate technical information
- [ ] CTA context is preserved through the form journey
- [ ] Key interactions are measurable

### Technical quality

- [ ] Breadcrumb, headings, title, description, and canonical are consistent
- [ ] Category and product links use crawlable HTML anchors
- [ ] Indexable filter/parameter duplication is controlled
- [ ] Structured data, if used, matches visible products
- [ ] Desktop and mobile product discovery are equivalent


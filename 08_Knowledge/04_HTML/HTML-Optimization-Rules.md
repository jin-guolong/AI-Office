# HTML Page Optimization Rules for Codex

## 1. Purpose

These rules govern every Codex change to an industrial B2B HTML page. The objective is to improve buyer experience, content structure, conversion, accessibility, maintainability, and search-engine usability without damaging URLs, tracking, integrations, verified content, or existing functionality.

## 2. Mandatory Change Workflow

### Before editing

1. Identify the source file, page URL, page type, target buyer, primary intent, and conversion goal.
2. Inspect the complete HTML, CSS, JavaScript, assets, forms, links, metadata, schema, analytics, consent code, and dependencies.
3. Record structural, content, UX, conversion, accessibility, and technical problems with evidence.
4. Explain proposed changes, expected value, risks, and assumptions.
5. Create a dated backup before the first modification.
6. Preserve the original and produce a separate optimized version unless replacement is explicitly approved.

### During editing

- Make the smallest maintainable change that fulfills the objective.
- Preserve verified facts, important content, URLs, anchors, form targets, query parameters, tracking, pixels, verification tags, consent tools, and integrations.
- Never invent product specifications, standards, certifications, results, customer cases, or commercial promises.
- Mark missing internal information for review; never publish internal placeholders.

### After editing

1. Validate markup and inspect the rendered page.
2. Compare source and optimized versions for unintended loss.
3. Test desktop and mobile layouts, navigation, links, forms, downloads, media, and interactive states.
4. Recheck metadata, canonical, robots, hreflang, schema, analytics, and consent behavior.
5. Report files changed, validation performed, remaining risks, and approval needs.

Codex must not publish or deploy without explicit authorization.

## 3. Document and Head Standard

Required where applicable:

- Correct `<!doctype html>`
- One `<html>` root with valid `lang`
- Valid `<head>` containing only permitted head elements
- Early `<meta charset="utf-8">`
- Responsive viewport meta tag
- One descriptive `<title>`
- Unique meta description
- Absolute canonical URL
- Intended robots directives
- Hreflang only for real equivalent regional/language pages
- Required favicon, social metadata, verification, consent, and tracking code

Do not place invalid elements such as visible content, `<img>`, or `<iframe>` inside `<head>`. Avoid JavaScript-generated title, robots, or canonical data when stable server-rendered HTML is possible.

## 4. Semantic Page Structure

- Use `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` according to meaning.
- Use one primary `<main>`.
- Use one clear page H1; subsequent headings must represent content hierarchy, not visual size.
- Do not skip heading logic merely for styling.
- Use lists for lists, tables for structured comparisons, and definition lists when appropriate.
- Use `<button>` for actions and `<a href>` for navigation.
- Keep essential product and solution content in rendered HTML.
- Avoid duplicate IDs and invalid nesting.

The DOM order should remain understandable without CSS.

## 5. Industrial B2B Content Modules

Match HTML structure to page type:

- Homepage: positioning, product routes, solutions, capabilities, proof, resources, inquiry
- Category: definition, product groups, selection criteria, applications, proof, inquiry
- Product detail: identity, applications, specifications, options, evidence, downloads, RFQ
- Solution: challenge, requirements, approach, products, implementation, proof, project inquiry
- Case study: context, challenge, solution, implementation, verified results, related pages, CTA

Do not hide critical specifications or buyer-decision information only inside PDFs, images, tabs requiring scripts, or decorative components.

## 6. Accessibility Standard

- Provide meaningful alternative text for informative images; use empty alt text for decorative images.
- Give every form control a programmatically associated label.
- Maintain visible keyboard focus and logical keyboard order.
- Ensure menus, dialogs, accordions, tabs, and forms work by keyboard.
- Use native elements before ARIA; ARIA must match actual behavior.
- Provide clear form instructions, errors, and success states.
- Do not rely on color alone to communicate status.
- Maintain readable contrast, zoom behavior, target size, and responsive text.
- Give tables headers and accessible structure.
- Provide captions/transcripts when required for meaningful media.

## 7. Links, Navigation, and Forms

- Important links must use crawlable `<a href>` markup.
- Link directly to the intended canonical HTTPS destination.
- Preserve URL parameters needed by functional or tracking systems.
- Use descriptive anchor text and accessible names.
- Identify downloads and external destinations when useful.
- Test navigation, breadcrumbs, language selectors, pagination, CTAs, and footer links.
- Preserve form action, method, hidden fields, anti-spam, validation, upload, CRM, and analytics behavior.
- Do not add required fields without a buyer or qualification reason.
- Never expose secrets, private endpoints, or personal data in client code.

## 8. Media and Performance

- Use correct image dimensions and reserve layout space.
- Choose suitable formats and responsive images (`srcset`/`sizes`) where useful.
- Lazy-load below-the-fold media; do not delay the likely LCP image unnecessarily.
- Avoid autoplay, oversized backgrounds, and decorative video that harms usability.
- Defer or remove only verified noncritical scripts; preserve functional and tracking dependencies.
- Reduce unused CSS/JS and duplicated inline code when safe.
- Use font loading and fallbacks that minimize blocking and layout shift.
- Prefer field data for performance decisions; use lab tests for diagnosis.

Performance targets for good Core Web Vitals are LCP ≤ 2.5 s, INP ≤ 200 ms, and CLS ≤ 0.1 at the 75th percentile where field data is available. Treat these as experience targets, not guarantees of search performance.

## 9. Responsive and Cross-Browser Rules

- Start from content priority, not a desktop-only layout.
- Ensure equivalent primary content, metadata, links, and schema across mobile and desktop.
- Make technical tables, drawings, cards, menus, forms, and CTAs usable on small screens.
- Prevent horizontal overflow except controlled data-table behavior.
- Test representative viewport widths and current supported browsers.
- Do not remove important mobile content merely to shorten the page.

## 10. Code Quality and Security

- Follow existing project conventions and avoid unnecessary dependencies.
- Do not duplicate libraries or initialize plugins twice.
- Escape or sanitize untrusted output according to the application context.
- Avoid inline event handlers when maintainable project patterns exist.
- Use `rel="noopener"` where required for new browsing contexts.
- Do not weaken CSP, consent, validation, authentication, or anti-spam controls without approval.
- Keep comments useful and free of internal SEO strategy or sensitive information.

## 11. Prohibited Actions

- Deleting or changing tracking, consent, verification, schema, forms, URLs, or redirects without approval
- Overwriting the only source copy
- Removing important content without documenting and approving the change
- Adding hidden keyword text or visible internal SEO language
- Changing product facts or claims without an approved source
- Using placeholder links, fake testimonials, fake certification logos, or fabricated results
- Publishing, deploying, or changing production systems without authorization

## 12. Codex Validation Checklist

- [ ] Existing structure and dependencies were analyzed before editing
- [ ] Problems and proposed changes were documented
- [ ] Dated backup and separate optimized version exist
- [ ] URL, tracking, consent, forms, and important content are preserved
- [ ] HTML is valid and semantic with one main and clear H1 hierarchy
- [ ] Title, description, canonical, robots, hreflang, and schema are correct
- [ ] Important content and links exist in rendered HTML
- [ ] Links, buttons, forms, downloads, and interactive states work
- [ ] Accessibility labels, focus, keyboard, alternatives, errors, and contrast are checked
- [ ] Product facts, claims, standards, and evidence are verified
- [ ] Desktop and mobile layouts were visually inspected
- [ ] Performance regressions and Core Web Vitals risks were checked
- [ ] No secrets, internal notes, or placeholders are exposed
- [ ] Changed files, tests, limitations, and next actions are reported

## 13. Official References

- [Valid page metadata](https://developers.google.com/search/docs/crawling-indexing/valid-page-metadata)
- [Google-supported meta tags](https://developers.google.com/search/docs/crawling-indexing/special-tags)
- [Crawlable links](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [Core Web Vitals](https://developers.google.com/search/docs/appearance/core-web-vitals)


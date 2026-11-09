# Web Quality Standard

Starting defaults. A project's brief may raise them. Lowering one requires an entry in `decisions.md`.

## Performance

Measured on the main landing page at mobile width:

- Largest Contentful Paint: 2.5 seconds or less
- Interaction to Next Paint: 200 ms or less
- Cumulative Layout Shift: 0.1 or less
- Images have explicit dimensions, modern formats and lazy loading below the fold

## Accessibility

Target WCAG 2.2 AA:

- Text and controls meet contrast requirements
- All functions work by keyboard, with visible focus
- Images have useful alt text; form fields have labels
- Headings are in logical order

## SEO

- One H1 and a unique title and meta description per page
- Correct canonical tags, plus sitemap and robots rules
- Old URLs redirect with a 301
- Structured data matches visible content
- Preview environments are not indexable

## Security

- HTTPS everywhere
- No secrets in client-side code or Git
- Forms validate on the server and have spam protection
- Dependencies have no known critical vulnerabilities at launch

## Launch readiness

- The main conversion flow works on current mobile and desktop browsers
- Error and 404 pages exist
- Forms deliver to the right destination, confirmed end to end with test data and an acknowledgment from the receiving system
- Privacy policy and consent controls are live where required
- A way to roll back the deployment is known

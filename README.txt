# South India Home Nursing Services — Website Starter Pack

## Included
- `index.html` — homepage
- `services.html` — service directory
- `air-ambulance.html` — dedicated air ambulance page
- `about.html` — company overview and locations
- `contact.html` — contact details and enquiry form demo
- `style.css` — shared responsive styles
- `site-content.json` — editable business information and service list
- `elementor-starter-template.json` — editable Elementor starter landing-page template
- `assets/` — supplied logo and air ambulance photo

## Preview as a static website
Keep the HTML files, `style.css`, and `assets` folder together. Open `index.html` in a browser. For a live site, upload the folder to your web host.

## WordPress / Elementor
1. Back up your WordPress site and install/activate Elementor.
2. In WordPress, open **Templates → Saved Templates** (or **Templates → Import Templates**, depending on your Elementor version).
3. Import `elementor-starter-template.json`. If your Elementor version rejects the starter JSON, create a new page and use the HTML/CSS version as the design/content reference; Elementor's export schema can vary by version.
4. Rebuild the remaining pages as separate WordPress pages (`Services`, `Air Ambulance`, `About Us`, `Contact`) using Elementor containers and widgets. Static HTML files are not automatically converted into editable Elementor pages.
5. Upload the logo and air ambulance photo through **Media → Add New**, then replace image references in Elementor.
6. Set the homepage under **Settings → Reading** and create navigation links to each page.
7. Connect the contact form to a real form plugin (Elementor Pro Forms, WPForms, Fluent Forms, etc.) and set the correct recipient email. The included HTML form is a demo and uses a placeholder mailto address.

## Important publishing checks
- Verify phone numbers, company legal name, service areas, operating hours and service availability before launch.
- Do not publish claims of guaranteed availability, clinical outcomes or fixed prices unless confirmed by your organisation.
- Air ambulance and home medical services require case-specific clinical and operational assessment. For emergencies, visitors should contact local emergency services.
- Update page titles, SEO metadata, privacy policy, terms, accessibility, cookie notices (where required), and form consent before launch.

## Brand design
Navy and teal healthcare palette with gold accents drawn from the supplied logo. Layout is responsive for desktop, tablet and mobile.

## Elementor page templates
The `elementor-templates/` folder contains separate editable starter page templates for Home, Services, Air Ambulance, About Us and Contact. Import each JSON file via Elementor's template import flow, then place/publish the template on the matching WordPress page. Elementor versions can differ; if a version rejects a JSON file, use the included HTML pages as a reference and rebuild with native Elementor widgets. The page templates use editable Heading, Text Editor and Button widgets; images, global header/footer, menu, form delivery and final styling should be configured in WordPress/Elementor.

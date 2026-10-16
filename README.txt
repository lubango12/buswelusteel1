FORGE WEBSITE — LATEST EDITABLE SOURCE

QUICK START
Extract the entire ZIP. Open the folder in VS Code.
Open index.html in your browser to preview the design.
For form testing, use a local server or an HTTPS static host rather than file://.
No package installation or build step is required.

EDIT THESE FILES
index.html — page content, links, sections, industry cards and contact details.
styles.css — layout, colors, animations and responsive/mobile styles.
script.js — products, product filters, enquiry form and navigation behavior.
forge-symbol.png — image logo.
steel-work.jpg — hero/workshop photo.
about-workshop.jpg — About Us illustration.
director-portrait.jpg — illustrative executive portrait.

COMMON CUSTOMIZATIONS
Search for FORGE to change the company name.
Brand colors: #190f6e indigo, #afeb00 lime, #ffffff white.
CSS contains successive customizations; the later rules override earlier ones.
Update the products array in script.js to change product descriptions/specifications.
Search index.html for Buzuruga to change office details and the map link.
Search for 255747297155 to change phone/WhatsApp links.
Replace image files with the same filenames, or update references in HTML/CSS.

EMAIL FORMS
All enquiry entry points use one shared form.
Recipient: lubangobenson@gmail.com.
FormSubmit handles delivery; one-time recipient activation is required.
After the first submission, check the recipient inbox/spam for its activation email.
Delivery has not been independently verified.
To change recipient, update BOTH the form action in index.html AND the fetch URL
in script.js. Activate the new recipient with FormSubmit as required.
The UI shows pending, service-accepted success, and failure messages.
An accepted submission does not guarantee arrival in the recipient inbox.
Internet access and availability of the external email service are required.

LOCAL SERVER (OPTIONAL)
If Python is installed, run this command in the extracted folder:
python -m http.server 8000
Then visit http://localhost:8000.
Alternatively use VS Code Live Server.

HOSTING
Upload this folder's contents to a static hosting service, preserving filenames.
Editing this download does not automatically update the existing hosted website.
Google Fonts, Maps, WhatsApp and email submission use external services.
The director portrait and About Us image are AI-generated illustrations.
The director message and company information are draft content for customization.

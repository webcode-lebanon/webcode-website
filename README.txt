WEBCODE — MAIN WEBSITE
======================

Project files
-------------
- index.html   Main Arabic/English website structure and metadata.
- styles.css   Responsive dark navy / electric blue design.
- script.js    Language toggle, mobile navigation, service selection and email draft form.
- favicon.svg  Custom WebCode W monogram.
- robots.txt   Basic crawler instructions.

Run locally
-----------
Keep all files in the same folder and open index.html in a modern browser.
No build step or package installation is required.

Contact details
---------------
Email: webcode.connect@gmail.com
WhatsApp: Shown as “Coming soon”. No phone number or inactive link is published.

Form behavior
-------------
The contact form validates the fields and prepares an email using mailto:.
It opens the visitor's configured email application; it does not submit to a
server and this static website does not store visitor information.

Portfolio disclosure
--------------------
The three portfolio cards are illustrative concepts / demonstration layouts.
They are not represented as completed projects for real clients.

Cloudflare Pages deployment
---------------------------
1. Put these six files in the root of a GitHub repository.
2. In Cloudflare, open Workers & Pages and create a Pages project connected to
   that repository.
3. For a plain static site, leave the build command empty.
4. Set the build output directory to / (repository root) or . as requested by
   the Cloudflare setup screen.
5. Deploy, then test the generated pages.dev address on desktop and mobile.

Notes
-----
- The site supports Arabic (default) and English using the language toggle.
- Google Fonts are loaded remotely; system fallback fonts are defined.
- A custom domain, canonical URL and sitemap can be added later when a domain
  is selected. No domain or paid service is required for the static site itself.

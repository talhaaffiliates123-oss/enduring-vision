# ENDURING VISION website

This folder is a complete static website. It does not require Node.js, a database, or a web server application.

## Preview

Open `index.html` in a modern browser. For the most accurate local preview, serve this folder with any simple static-file server and open the local URL it provides.

## Deploy to Hostinger

1. Open Hostinger hPanel and go to **Files → File Manager**.
2. Open the domain’s `public_html` directory.
3. Remove Hostinger’s default placeholder page if one is present.
4. Upload the contents of this folder—or upload the supplied ZIP and extract it directly inside `public_html`.
5. Confirm that `index.html` sits directly inside `public_html`, not inside an extra nested folder.
6. Open the domain in a browser and verify the navigation, contact links, and mobile menu.

The supplied sitemap uses the published preview URL. After the final Hostinger domain is connected, replace that preview URL in `sitemap.xml` with the final production URL and update the absolute sitemap URL in `robots.txt`.

## Contact form

The form intentionally uses a transparent `mailto:` workflow. Submitting it opens the visitor’s email application with a prepared message addressed to `zarq.khan@enduringvision.eu`; it does not claim to send data from the website.

To connect a hosted form service later, replace the form’s `action` in `index.html`, update the submission handler in `assets/js/main.js`, and review the service’s privacy and spam-protection requirements before publishing the change.

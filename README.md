# Clock Scenery

Static product website for Clock Scenery, a macOS desktop clock and weather app.

## Hosting

Upload the contents of this repository to the web root of the selected domain.
The entry point is `index.html`. No build command, package installation, backend,
or runtime environment variables are required.

Keep `index.html`, `style.css`, `app.js`, and `assets/` together. Asset paths are
relative, so the site also works from a subdirectory. Configure HTTPS on the host.
No SPA fallback or server-side routing is required.

### Local preview

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`. Use an HTTP server rather than opening the HTML file
directly to match deployed browser behavior.

## Contents

- Gallery with full-screen screenshot previews
- Features and free/full-version comparison
- Roadmap: 100+ styles, time/weather-aware backgrounds, animated styles, broader compatibility
- FAQ and link to the company website
- Seven languages: Russian, English, German, French, Spanish, Simplified Chinese, Japanese
- Five localized screenshots for each language
- Responsive layout and reduced-motion support

The language preference is stored locally in the browser. Google Fonts supplies
Manrope and Prata, with system-font fallbacks. No analytics or contact form is
included. App screenshots use demonstration weather data.

## Before public release / App Store submission

1. Replace the draft application-privacy notice with the final privacy policy
   and give it a stable public URL.
2. Confirm the public support channel. No personal email is included in the site.
3. When the app is publicly available, replace the release-preparation text and
   add the verified Mac App Store download link.
4. Check the final domain on desktop and mobile, all seven languages, gallery,
   full-screen dialogs, FAQ, and support link.

Roadmap entries are plans, without promised release dates. Domain/DNS deployment
is handled separately from this source repository.

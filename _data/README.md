Page copy lives in `caffeine/en.yml`, `caffeine/fr-fr.yml`,
`feedback/en.yml`, and `feedback/fr-fr.yml`. The locale filename matches
the page's `lang` value in lowercase. Titles and descriptions live here too;
an omitted description uses the site's default description.

Edit `_layouts/caffeine.html` or `_layouts/feedback.html` to change the
structure for both languages. Paragraphs, notes, and contribution links support
Markdown; feature and privacy-summary lists contain plain text.

`caffeine/shared.yml` contains the app name, English slogan, and English
review descriptions shared by both languages. The slogan stays in English.
Navigation and footer copy stays in English in `_layouts/default.html`.

The root Markdown pages and the English directory entry points contain only
routing, language, layout, and copy-source settings. Keep both English entry
points so existing `.html` and directory URLs continue to work. French
redirects and language-alternate links are handled by the default layout.

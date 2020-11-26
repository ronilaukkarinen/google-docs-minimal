# Minimal app for Google Docs

When I write, I won't tolerate any distractions. Google Docs is great, but by default has too many panels visible. Even full screen won't hide them all. So I created this small app for distraction free writing experience.

My preferred fonts are: **Helvetica Neue** for headings, **Gill Sans** or **Libre Baskerville** on paragraphs.

OR **Avenir** for everything. Avenir is awesome!

### Installation on macOS

1. Download this repo and unpack CSS.
2. Get [nativefier](https://github.com/jiahaog/nativefier/)
3. Run command `nativefier --name 'Google Docs' 'https://docs.google.com/document/d/YOURDOCUMENT/edit' --internal-urls '.*' --browserwindow-options '{ "webPreferences": { "spellcheck": true } }' -e 10.1.0 --inject /Users/YOURUSERNAME/Projects/google-docs-minimal/styles.css --user-agent 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.102 Safari/537.36' --full-screen` (edit doc link and the CSS path to the place you unpacked the CSS, for dark theme use styles-dark.css)
4. Move Google Docs.app to Applications

![Light theme](https://i.imgur.com/ex1D3RQ.png "Screenshot")

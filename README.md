# Minimal app for Google Docs

When I write, I won't tolerate any distractions. Google Docs is great, but by default has too many panels visible. Even full screen won't hide them all. So I created this small app for distraction free writing experience.

My preferred fonts are: **Helvetica Neue** for headings, **Gill Sans** or **Libre Baskerville** on paragraphs.

### Installation on macOS

1. Download this repo and unpack CSS.
2. Get [nativefier](https://github.com/jiahaog/nativefier/)
3. Run command `nativefier --name 'Google Docs' 'https://docs.google.com/document/d/YOURDOCUMENT/edit' --internal-urls '.*' --browserwindow-options '{ "webPreferences": { "spellcheck": false } }' -e 9.1.0 --inject /Users/rolle/Projects/google-docs-minimal/styles.css` (edit doc link and the CSS path to the place you unpacked the CSS)
4. Move Google Docs.app to Applications

![Screenshot 1](https://i.imgur.com/ex1D3RQ.png "Screenshot")

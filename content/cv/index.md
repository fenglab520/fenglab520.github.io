---
title: Curriculum Vitae
summary: "Curriculum Vitae — Yen-Chen Anne Feng"
share: false
commentable: false
editable: false
---

<style>
/* Stop the page from rubber-banding when a scroll flick reaches the bottom.
   The PDF viewer sits in an iframe, and the CV page has a little scroll of its
   own below it (the footer). On touch tablets — especially in landscape, where
   that outer scroll is larger — flicking to the bottom made the whole document
   bounce a few times. `overscroll-behavior: none` disables that boundary bounce.
   (This <style> only loads on the CV page, so it doesn't affect other pages.) */
html,
body {
  overscroll-behavior: none;
}

.cv-embed {
  width: 100%;
  height: 85vh;
  border: 1px solid rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  margin-bottom: 1.5rem; /* breathing room above the footer bar */
}
</style>

<!-- Render the CV with the bundled PDF.js viewer on EVERY device. A native
     <iframe> PDF embed only shows the first page on iOS/iPadOS Safari (WebKit),
     and iPads can't be singled out by a CSS width breakpoint (their widths
     overlap laptops, and iPadOS reports its UA as macOS). PDF.js shows all pages
     everywhere, so it's the reliable cross-device choice. -->
<iframe class="cv-embed" src="/pdfjs/web/viewer.html?file=%2Fuploads%2FCV_YAFeng-Aug2026-distr.pdf#zoom=page-width" title="Curriculum Vitae — Yen-Chen Anne Feng" allow="fullscreen">
  <p>Your browser cannot display the PDF inline. <a href="/uploads/CV_YAFeng-Aug2026-distr.pdf">Download the CV instead</a>.</p>
</iframe>

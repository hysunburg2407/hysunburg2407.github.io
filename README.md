# Shubham Dixit — academic website

Personal academic website for stochastic hydrology, rainfall extremes and climate-informed hydrological risk.

## Website

GitHub Pages is configured to publish the `main` branch, from the repository root.
The intended website address is https://hysunburg2407.github.io/ . The current deployment status is shown in Settings → Pages.

## Editing

The complete website is in `index.html`. It is self-contained: the CSS, JavaScript, portrait and decorative landscape are embedded, so there are no packages to install and no build step.

- Search for the section IDs `about`, `research`, `publications`, `teaching`, or `contact` to edit the corresponding content.
- Search for `class="publication"` to update papers. Each article has a `data-type` and `data-year` used by the publication filters.
- The styles are inside the `<style>` element in the head. Interactive behavior is inside the `<script>` element near the end.
- The two CV links point to the public Google Drive document already used on the original Google Site. Update both when replacing the CV.
- Portrait and illustration are embedded as data URLs. A new portrait can instead be uploaded to the repository and referenced by a relative URL.
- `.nojekyll` tells GitHub Pages to serve the static site directly.

The original multi-file source version is also provided to the owner separately, with HTML, CSS, JavaScript and assets in separate files.

## Content

Prepared 14 October 2026 from the user's existing Google Site and academic information supplied in conversation. The PhD timeline reflects the completed September 2026 defence. Publications and patent application statuses follow the existing public list. Preprints remain labelled separately; patent applications are not described as grants.

The most recently mentioned additional accepted ASCE paper is not listed until its exact title and final bibliographic details are supplied.

The watershed banner is a decorative illustration, not a map or dataset. The portrait comes from the owner's existing website.

Sources: https://sites.google.com/view/shubham-dixit/home and its publications, experience, education, curriculum-vitae and get-in-touch pages.

There are no analytics, trackers, external font dependencies, or form backends. Email links open the visitor's email application.

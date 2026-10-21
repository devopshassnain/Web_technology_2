# Hussnain Sarwar - Personal Portfolio (Web Technologies Assignment #2)

BS Computer Science | Web Developer and UI Designer | hassnainsarwar478@gmail.com

Three-page website: `index.html` (inline CSS), `information.html` (embedded CSS), `registration.html` (external `style.css`).

## Short Explanation

CSS (Cascading Style Sheets) controls how HTML looks. Its benefits are separation of content from design, consistent styling across pages, easier maintenance, and smaller, faster pages.

In the rule `h2 { color: #1f3a5f; }`, `h2` is the selector, `color` is the property and `#1f3a5f` is the value.

Inline CSS uses the `style` attribute on one element; it is quick but hard to reuse (used on the Home page). Embedded CSS sits in a `<style>` element in the `<head>` and styles a single page (Information page). External CSS is a separate `.css` file linked with `<link>`, which can style many pages and is easiest to maintain (Form page).

CSS1 (1996) introduced basic fonts, colors and margins. CSS2/2.1 (1998/2011) added positioning, media types and table styling. Modern CSS is split into modules (Selectors, Flexbox, Grid, Colors) that evolve separately, so new features arrive faster.

Browser support matters because browsers may render or support features differently, so a site must be tested to work for all users. I tested this website in Google Chrome and Mozilla Firefox and recorded the small differences in the table below.

Semantic HTML example: `<article id="featured-project">` clearly describes self-contained content. Non-semantic HTML example: `<div class="option-row">` only groups a radio button and its label for styling.

## Browser Testing

| Feature | Chrome | Firefox | Differences |
|---|---|---|---|
| Navigation and layout | Pass | Pass | None noticed |
| Audio and video playback | Pass | Pass | Control bar looks different |
| Form validation messages | Pass | Pass | Message wording and style differ |
| Date picker | Pass | Pass | Different calendar pop-up design |

## Form Validation Tests
- Empty required fields: browser blocks submission and highlights the field.
- Invalid email (`abc`): rejected with an email format message.
- Password shorter than 8 characters: rejected.

## Files
`index.html`, `information.html`, `registration.html`, `style.css`, `images/`, `audio/`, `video/`, `screenshots/`

WORLD COMMUNITY CHURCH — WEBSITE
=================================

HOW TO PREVIEW
- Double-click index.html to open the site in any browser.
- Click through the nav to see all 8 pages: Home, About, Ministries,
  Connect, Messages, Events, Give, Contact.

FILES
- index.html, about.html, ministries.html, connect.html,
  messages.html, events.html, give.html, contact.html — the pages
- css/style.css — all styling (colors, fonts, layout) in one place
- js/main.js — mobile menu toggle
- images/ — placeholder graphics (see below)

SWAP IN YOUR REAL LOGO
- images/logo.svg is a placeholder monogram ("WCC" on navy).
- Since you already have a real logo, replace images/logo.svg with
  your logo file. Easiest option: save your real logo as
  images/logo.svg (or logo.png) and update the <img src="..."> in
  the header of each HTML page to match. It's the same tag near the
  top of every page:
      <img src="images/logo.svg" alt="World Community Church logo">
- Also update images/favicon.svg the same way (shows in the browser tab).

SWAP IN REAL PHOTOS
- Every photo on the site is a placeholder SVG with a dashed border
  and a label (e.g. "Hero Photo", "Kids Ministry Photo") so you can
  see exactly what each image is for.
- To replace one: save your real photo using the SAME filename as
  the placeholder it replaces (e.g. export your hero photo as
  images/hero-home.jpg, or just reuse the .svg name and use a .jpg
  instead — if you change the extension, update that one line in
  the HTML where it's referenced).

FILL IN THE BLANKS
Search each page for text in [square brackets] — these are the
details I didn't have, and need your real information:
  - [Service Time]              — your actual Sunday service time
  - [Street address]            — your building's address in Tantra Hills
  - [Phone number] / [Email address]
  - [Leader Name] / [Role]      — About > Leadership
  - [Message Title]             — Messages page
  - [Event Name] / [Date] / [Time] — Events page
  - Mobile Money / Bank details — Give page

There's also placeholder body copy in a few spots (the About page
"Our Story" section, leadership bios, sample events/messages) —
each is flagged with a small note in the page itself
("Placeholder — replace with...") so you know what to personalize.

CONTACT FORM & MAP
The "Send a message" and "Plan your visit" forms don't submit
anywhere yet — they need to be connected to an email address, a
form service (e.g. Formspree, Google Forms), or your church
management system. The map on the Contact page is also a
placeholder — swap it for an embedded Google Map once you confirm
your exact address.

SOCIAL LINKS
Facebook / Instagram / YouTube links in the footer currently point
nowhere (#) — update the href values once your church has those
accounts live.

# Types of users

## Blind

### Keyboard shortcuts

Skip to the main content on the page
+ Do not want to listen through the list of primary navigation links on every pathname change.

Navigate by headings

Cycle through semantic landmarks

Skip through anchor tags

### Content

Context/sentiment of content cannot be dirrived through visual aids
+ Color
+ Size
+ Font weight
+ Images / icons *(without accessible metadata)*
+ Highlighting

All functionality must be capable using a **keyboard**
+ **Note:** Keyboard navigation can act differently when a screen reader is active
  + What are these differences?
  + Xxxx
  + Xxxx
  + Xxxx
  + Xxxx

Video content/sentiment
+ Blind users can hear audio but cannot see any nuanced context *(like the setting, a users emotion, gestures etc)*
+ [Here is an example of audio descriptors](https://www.youtube.com/watch?v=Al4FNgNvyyI) *(narrating exactly what is going on in the video at any given time)*

Feedback after creating an action
+ Silence after making an action is a bad experience
  + Form submission
  + Input change (like a select)
  + Expand/collapse
  + **Important:** Inform users that a SPA navigation has occurred
    + Is this a wide reaching problem?
    + How can we solve this?

Swipe Gestures
+ Screen readers hijack swipe gestures for themselves
+ All functionality MUST be actionable through click/touch interactions

---

## Low vision

There is a huge disparity between the different type of low vision issues

Color
+ Color contrast/schemes can help users establish extra visual clarity
  + Yellow / Black color schemes = Users that feel pain/discomfort from bright light (reducing the white light)
  + high contrast = Increase the differentiation of the context (text) from the background

Zoom
+ Using 3rd party (or the browser) to increase the page scale
+ **Note:** Do *NOT* disable pinch-to-zoom!
+ [An example of using a 3rd party zoom tool](https://www.youtube.com/watch?v=ojtiVj78QPw)

Custom UX
+ Using 3rd party integrations to change the shape/color of
  + The mouse pointer
  + Text pointer
  + An elements focus state

Screen Readers
+ Not just for blind users, low vision users can benefit from screen readers too!

---

## Color blind

--> A more inclusive term is **Color Vision Deficiency *(CVD)***

**Colors (especially with similar saturation or luminosity) can be hard to distinguish.**
+ Red / Green (99% or color vision issues)
+ Red / Black
+ Blue / Yellow

Green and Red are often hard to differentiate, yet are very common UX patterns:
+ Success / Error
+ Online / Offline
+ Profit / Loss

Color alone, should not be used to convey information. Combine with:
+ Text
+ Icons

3rd party tooling?
+ Noting on the web can reverse color blind issues
+ There are special glasses that can help individuals improve their issues

---

## Deaf

The accessibility of **Audio** (and Video).

Audio files (no video)
+ **Transcript** (plain text summary) of narration, dialogue and sound effects.
+ *MUST!*

Video files
+ **Captions** (played in sync with the video)
  + [See an example of captions here](https://www.youtube.com/watch?v=ZpGLy-FyOc0)
  + *MUST!*

+ **Sign language interpretation**
  + allows deaf people (who can communicate through Sign language) to follow along without captions

---

## Deafblind

Users connect Screen Readers to Braille devices (which raise physical bumps rather then read content allowed)

Audio and Video files
+ **Transcript**
  + A transcript for helps users digest content at their own pace (video captions are too fast for Braille readers)
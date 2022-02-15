# Understanding Technology
[WAI *(**W**eb **A**ccessibility **I**nitiative)*](https://www.w3.org/WAI/people-use-web/)

## **Assistive** Technology
**Hardware** or **Software** that *assists* the user experience.

### Hardware
+ Keyboard (Braille or QWERTY)
+ Reading glasses


### Software
+ Screen reader

## **Adaptive** Strategies
The capability for your application to *adapt* to user needs. 

### Browser / Operating System
+ Adjust font size
+ Change color contrast
+ Responsive design

<br />
<br />
<br />

# Physical & Visual Disabilities

## Keyboard A11y

+ [Examples of UI scenarios and the corresponding keyboard usage to interact with them](https://webaim.org/techniques/keyboard/#testing)

### Semantic elements are accessible by default

#### Clicking
+ **Links:** `Enter`
+ **Buttons:** `Enter` or `Space`

### Custom built capabilities can cause A11y issues


#### Mouse Interactions
Revealing content  on `:hover` (content is inaccessible)


#### Keyboard Focus
+ **No focus capability:** Interactive elements cannot be targeted
+ **No visual focus cues:** Users cannot orientate their location on page
+ **Focus order:** Logical flow **top** --> **bottom** + **left** --> **right** (for English speakers)
+ **Moving focus** A button that opens a modal should move focus to the modal

#### Skip Links
Allow users to access the main content quickly (and not tabbing through the top navigation elements each time)

## Dexterity Issues
Users that have reduced dexterity with touch and mouse can find some UI scenario difficult

+ **Small touch targets:** An iPhone keyboard requires a high level of precision
+ **Hover interfaces** Hovering over an area for a menu or tooltip to reveal

## Switch Controls
Triggering *"traditional"* actions in unique ways
+ **Sip and Puff:** Using a straw to trigger **Tab** or **Clicks**
+ **Button Switches:** [Xbox Adaptive Controler](https://www.xbox.com/en-NZ/accessories/controllers/xbox-adaptive-controller)
+ **Camera Switches:** Tilting a users head to trigger interactions
+ **Eye Tracking:** **Move** and **Click** based on the location of a users visual focus

**Note:** Switch Controls can be used in **combination** to create more enhanced experiences.

## Speech Input
Users can interact with a Web application using only speech (without mouse or keyboard).

Problems a user encounters are similar to keyboard only navigation (particularly around focus).

**Semantic Meaning** is important when considering **Speech Input**
+ Labeling: Links, Buttons and Inputs need accurate labels 
  + > Click "register your interest" link
  + **Assistive Technology** software can overlay numbers on interactive elements for more specific targeting
    + > Click button number seven

**Scrolling** is more difficult when using speech input
+ Small scrolling areas can result in a scrolling action being preformed multiple times for simple tasks. This adds significant cognitive overload


## Screen Readers

Elements are given context to users
+ **Name:** Accept terms and conditions
+ **Role:** Checkbox
+ **State** Unchecked

### iOS

There are various ways to navigate with the built in iOS **Voice Over**

**Note:** 
+ **Voice Over Toggle:** On/Off with a triple click of our iPhone power button (great for debugging)
+ **Screen Curtain:** Hide the screen content (so simulate a user with visual disabilities)


#### Usage
+ Click anywhere on the screen to get an overview of that area
+ Double click to interact with that portion of the page
+ Use the "rotor" (a two finger twist) to bring up a dialog to select things like headings
+ Swipe left / right to move through the items on a page (like `Tab` on the Desktop)

## Low Vision

### Font Size
+ **Not** browser zooming!
+ Enlarging just the font size in the browser settings

### Poor Contrast
+ Users with low vision, screen glare issues

### Color for Context
+ Color should be a **supporting** not a **primary** UX tool for conveying meaning.
+ Users with color blind issues cannot derive color context
+ Screen readers (or text only) interfaces do not accommodate color

#### Problem Areas
+ Using only color for **error**, **success** or **warning** states (should have text messaging)
+ Differentiating graph data with only color (should have a pattern/texture)
+ Using only color to identify links (should use underline)

### Motion
Disrupts users with cognition or photosensitive (seizures) issues
+ Animated Banner ads
+ UI animation
+ Video

**Note:** This issue can be compounded if a users has zoom enabled (motion is more overwhelming)

### Point of Regard
Content changing outside of a users "visual scope" (common with zoom).
+ `:hover` interactions showing content off screen
+ Changing options in a filter updates content in another part of the screen

### Screen Magnification
+ Zoomed area follows the users mouse
+ Mouse color and design can be customized 

## Hearing Disabilities

### Video
+ **Closed Captions:** Same language as the audio
+ **Subtitles:** Spoken audio translated into another language
+ **Transcript:** Text version of spoken and non-spoken audio
+ **Sign Language:** Convey complete video context

**Note:** Users with **Sign Language** as their first language may find written text formats hard to digest.

## Speech Disabilities
Limits the interaction with voice systems like Siri and Alexa.

+ **Mutism:** Due to anxiety or a brain injury
+ **Speech Impediments:** Stuttering or Tourettes
+ **Degenerative Disease:** Parkinson's disease
+ **Hearing Disabilities:** Often have an affect on the ability to speak
+ **Temporary Illness:** Throat issues
+ **Situational:** Loud environment (voice cannot be heard) or quiet (no talking in the Library)


## Cognitive Disabilities

+ [Inclusive Design Principles: Be Consistent](https://www.tpgi.com/inclusive-design-principle-be-consistent/)
+ [A web of anxiety: accessibility for people with anxiety and panic disorders](https://www.tpgi.com/a-web-of-anxiety-accessibility-for-people-with-anxiety-and-panic-disorders-part-1/)
+ [Cognitive Accessibility 103](https://spacedoutandsmiling.com/presentations/cognitive-accessibility-103-csun-2017)

### Complexity
Users can become overwhelmed by comprehensive navigation or Content layout

**Note:** Some users prefer a narrow "mobile" layout (**even** on desktop) as it has a simpler UX flow (and reduced test line width).

### Content
Advanced language, slang terms, long sentences or metaphors can make content consumption difficult.

### Iconography
Some users cannot derive meaning from icons along (a floppy disk = save)

### Images
Images can work well as a secondary element to support and give extra context to content.

**Note:** Adding Text on top of images (Even with A11y contrast) can add too much noise for some users.

<br />
<br />
<br />

# [Essential Components of A11y](https://www.w3.org/WAI/fundamentals/components/)

+ **WCAG:** [Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
+ **ATAG:** [Authoring Tool Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/atag/)
+ **UAAG:** [User Agent Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/uaag/)









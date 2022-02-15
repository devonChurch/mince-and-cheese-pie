# It's About People!
The **Web Standards** are a *secondary* aspect to A11y ... **People** are the *primary*!

It's about all people **contributing** to the Web Platform (**absorbing** content but also **creating** it)!

---

> Access to information and communications technologies, including the Web, is defined as a basic human right in the United Nations Convention on the Rights of Persons with Disabilities (UN CRPD)

> The accessibility barriers to print, audio, and visual media can be much more easily overcome through web technologies.

---

## Disability Categories
+ Auditory
+ Cognitive
+ Neurological
+ Physical
+ Speech
+ Visual

### Examples
+ **Blind Users:** Screen Readers
+ **Reduced Motor Function:** Joystick (instead of Mouse)
+ **No Limb Function:** 
  + Mouth Stick (held in Mouth to tap Screen/Keyboard)
  + Head Wand (hat with a stick to tap Screen/keyboard)
+ **Deafblind:** Digital Braille Display (cannot hear screen reader output and cannot see keyboard to make inputs)
+ **Cognitive Disabilities:** Can see text but cannot process it accordingly (prefers hearing text content in audio form using Screen Readers)
+ **RSI (Repetitive Strain Injury):** User voice recognition to limit the reliance on physical interaction
+ **Color Blindness:**
+ **Low Vision:** Increase font size or zoom in on page

## Users Without Disabilities
+ **Broken Arm:** Cannot use a Mouse
+ **Bright Sunlight:** Dark/Contrast Mode for visual clarity
+ **Loud Environments:** Using video captions to understand context
+ **Different Languages:** Auto-generated captions translating video audio

<br />
<br />
<br />

# Introduction to Screen Readers

## Page Title
Shown in Browser Tabs and important for orientating users

## Heading Hierarchy
Outlines the page structure at its most basic level

## Anchor Tags
Should have a descriptive text to convey context of the links functionatliy.

**Note:** This also benefits SEO (as a selling point for business A11y adoption).

### Right:
Clear context around the links intent
+ Get updates about Accessibility tips and tricks
+ Find out more about Web Accessibility
+ 
### Wrong:
Content is ambiguous about what the link actually does
+ Click here
+ Read More

## Alt Text
Should convey an images visual context in text form

### Right:
Simple and to the point
+ A ginger kitten sleeping on a bed
+ A world map with New Zealand highlighted

### Wrong:
Should not lack visual context
+ A banding image

Should not be too comprehensive
+ An image of seven bananas on a tree in Fiji during an December summers day at 2pm by the Liku beach where tourists often visit to go swimming

## Lists
Using semantic markup for lists (`<ul />`, `<ol />`, `<li />`) will tell users how many items are in the list and allow said items to be easily navigated.

<br />
<br />
<br />

# Technology Can be **Enabling** or **Disabling**!

+ Applications for **Educational learning** or **Medical information** without A11y can ostracize users with accessibility requirements.
+ Platforms (like Facebook or Blogs) that change their user experience to be less accessible can lock users out of accessing their information.

<br />
<br />
<br />

# Visual Disabilities

## Text Wrapping
Generally, needing to scroll both **horizontally** and **vertically** to view content on a page is a bad user experience. This is compounded if users have **Cognitive Disabilities** or **Motor Difficulties** to accurately position the page accordingly. Scenarios like this are common when **Low Vision** users zoom in on a page (for example 400%).

## Snippets
Applications that do not embrace the *fluid* nature of **Web Design** can have content legibility compromised when users inject A11y scripts to improve **Text Spacing**.

![custom Chrome Dev Tools code snippet](https://user-images.githubusercontent.com/15273233/152716966-e05db780-b3df-4b17-b463-6e9aa9dc787a.png)

**Note:** you can also use [the Chrome Extension **Stylus**](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) to inject CSS onto a page.
+ [See here for an example of Stylus](https://www.youtube.com/watch?v=Nv_ovvmHYsg)

## Visual Disabilities are Broad

**Example:** Users with Tunnel Vision often like smaller font sizes with a small content width to fit into their visual field. We often expect users with Visual Disabilities to require large font sizes in the maximin content area possible.

![Representation of what a user with Tunnel Vision sees](https://vidatraining.weebly.com/uploads/5/7/5/8/57580571/tunnel-vision-vida_orig.png)

**Example:** Users with Dyslexia benefit from a specific font that caters to their cognitive needs.

![Dyslexia specific type face](https://upload.wikimedia.org/wikipedia/commons/3/3a/OpenDyslexic.png)


## User-centered Design

## Empathy-driven Development

# Audio Descriptions
Extra audio injected into a video to convey missing context:

**Example:** A video might start with two characters talking about their plans for the weekend. An audio description would set the scene that would typically be inferred through visual context *"A woman and a man are talking in a bar after work"*.

<br />
<br />
<br />


# The *"Medical Model"* of Disability
Associating a person with a disability based on their medical requirements.
+ Anthony is disabled because he is blind
+ Shawn is disabled when her hands have low motor skills
+ Jenny is disabled because she cannot hear

## The *"Social Model"* of Disability

---

> It’s not about a person's abilities or impairments, it’s about the design.
> That is, bad design is disabling.
> When designs provide the flexibility to meet all users' needs, then they are enabling.

> Disability is caused by a mismatch between the design and the person

---
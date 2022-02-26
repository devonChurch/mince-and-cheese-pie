# **POUR** = The Four Principles for WCAG
**W**eb **C**ontent **A**ccessibility **G**uidelines

## Perceivable
Content can be perceived in different methods
+ Text-to-speech
+ Large font sizes
+ Braille devices

## Operable
User experience can be opporated with different methods
+ Keyboard
+ Mouse
+ Sip-n-puff
+ Touch
+ Speech

## Understandable
Content is understandable
+ Consistency (toasts, navigation)
+ Simple (layout, language)

## Robust
User experience works in a wide range of scenarios
+ Desktop/laptop
+ Mobile/tablet
+ Screen reader
+ Browsers

<br/>
<br/>
<br/>

# WCAG

## WCAG 2.0
+ A, AA, AAA
+ Covers **POUR** principles
+ 12 guidelines
+ 61 success criteria

## WCAG 2.1
+ Covers all of WCAG 2.0
+ Focus on **cognitive** disabilities, **low vision** and **mobile**
+ 13 guidelines
+ 78 success criteria

## Technology Agnostic
***--> Normative (Recommendations)***
The same principles apply for **Web** -vs **Native** -vs- **PDF** even if their Engineering implementation details are different.

***--> Non-Normative (Stipulations)***
+ [Understanding WCAG 2](https://www.w3.org/WAI/WCAG21/Understanding/)
+ [Techniques for WCAG 2](https://www.w3.org/WAI/WCAG21/Techniques/)
+ [How to Meet WCAG 2](https://www.w3.org/WAI/WCAG21/quickref/)

# Testing **Perceivable** Scenarios

[Basic WCAG checks for non technical people](https://www.w3.org/WAI/test-evaluate/preliminary/)

## Alternative (`alt`) text

If an image is representing a link `<a><img /></a>` its alt text should describe the link functionality **not** the image description. 
+ A logo wrapped in an anchor tag could have the alt text `[COMPANY_NAME] homepage`

# Keyboard A11y

## Speech Input
Speech inputs directly correspond to Keyboard inputs.
+ If an app support Keyboard navigation, then it also support Speech Input as an interaction method

# Motion

[**PEAT** = **P**hotosensitive **E**pilepsy **A**nalysis **T**ool](https://trace.umd.edu/peat/)

# Content

## Language
You can nest `lang` tags to specify areas on a page with different languages
```html
<html lang="en">
    <body>
        ...
        <span lang="ja">...</span>
```
# IAAP WAS Study Guide

## 1.1 Understand and interpret a11y specificiations and techniques 

### Web Content Accessibility Guidelines 2.1
- [ ] Understand the relationship between principles, guidelines, and success criteria
- [ ] Understand intent, requirement, and impact of each principle, guideline, and success criterion
- [ ] Be familiar with sufficient, failure, and advisory techniques for each success criterion
- [ ] Undertand the conformance level designations (A, AA, AAA)
- [ ] Identify the conformance level of each WCAG 2.1 success criterion
- [ ] Understand the three types of techniques and the W3C vetting process for techniques

- [ ] Read [Intro to understanding WCAG 2.1](https://www.w3.org/WAI/WCAG21/Understanding/intro) – 15 minutes
- [ ] Read through [Understanding WCAG 2.1 (non-normative)](https://www.w3.org/WAI/WCAG21/Understanding/) – 2 hours
- [ ] Read [WCAG 2.1 (normative)](https://www.w3.org/TR/WCAG21/) – 5 hours
- [ ] Go through [WAS Certification - WCAG 2.1 sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=0#gid=0) – 30 minutes
- [ ] Go through [How to Meet WCAG 2.1 (non-normative)](https://www.w3.org/WAI/WCAG22/quickref/?versions=2.1) – 2 hours
- [ ] Read through [Techniques for WCAG 2.1 (non-normative)](https://www.w3.org/WAI/WCAG21/Techniques/) – 8 hours
- [ ] Read [Understanding Techniques for WCAG Success Criteria](https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques) – 15 minutes

### Accessible Rich Internet Applications 1.1
- [ ] Understand the purpose and impact of WAI-ARIA 1.1
- [ ] Understand the WAI-ARIA 1.1 model of names, roles, and values
- [ ] Know when and why to use WAI-ARIA 1.1, and when to use standard HTML instead
- [ ] Be familiar with authoring practices for customm widgets, including semantic structure, keyboard behavior, etc

- [ ] Read [Introduction to WAR-ARIA](https://www.w3.org/WAI/standards-guidelines/aria/) – 15 minutes
- [ ] Read [Demystifying WAI-ARIA (CanAdapt)](https://www.davidmacd.com/blog/wai-aria-accessbility-for-average-web-developers.html) – 45 minutes
- [ ] Read [WAI-ARIA 1.1 (normative)](https://www.w3.org/TR/wai-aria-1.1/) – 8 hours
- [ ] Go through [WAS Certification - WAI-ARIA 1.1 sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=821101334#gid=821101334) - 15 minutes
- [ ] Read through [WAI-ARIA 1.1 The Roles Model (non-normative)](https://www.w3.org/TR/wai-aria-1.1/#roles) – 3 hours
- [ ] Read through [WAI-ARIA Authoring Practices 1.1](https://www.w3.org/WAI/ARIA/apg/) – 5 hours
- [ ] Read [Accessible name and description computation 1.1 (non-normative)](https://www.w3.org/TR/accname/) - 45 minutes

### Authoring Tool Accessibility Guidelines 2.0
- [ ] Understand how ATAG 2 applies to web content authoring tools
- [ ] Understand meaning and intent of the two main sections of ATAG 2
- [ ] Understand the intent, requirement, and impact of each principle, guideline, and success criterion
- [ ] Distinguish between good automated practices in authoring tools and good practices that require author/user input
- [ ] Understand power and limitations of automated accessibility authoring features

- [ ] Read [ATAG Overview](https://www.w3.org/WAI/standards-guidelines/atag/) – 15 minutes
- [ ] Read [ATAG 2.0 (normative)](https://www.w3.org/TR/ATAG20/) – 3 hours
- [ ] Go through [WAS Certification - ATAG 2.0 sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=625526860#gid=625526860) - 30 minutes
- [ ] Read through [Implementing ATAG 2.0 (non-normative)](https://www.w3.org/TR/IMPLEMENTING-ATAG20/) – 6 hours

## 1.2 Create accessible JavaScript, AJAX, and interactive content

- [ ] Read [CSS and JavaScript accessibility best practices (MDN)](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility/CSS_and_JavaScript) – 1 hour

## 1.3 Integrate accessibility into the QA process
- [ ] Characterize and differentiate between disciplines of Agile and Waterfall project mgmt methodologies and compare the approaches concerning a11y QA
- [ ] Demonstrate understanding of benefits of designing digital content with a11y in mind (vs. remediation)
- [ ] Characterize and differentiate between the disciplines of a11y and UX design and compare assumptions of each discipline
- [ ] Demonstrate an understanding of user testing and compare it to a11y verification testing (AVT)
- [ ] Understand how a11y needs to be integrated into the entire product life cycle 
- [ ] Identify ways in which each person's role in the project life cycle can include some aspect of a11y

- [ ] Read [Integrating a11y across agile and waterfall development (Medium)](https://medium.com/@Irfan_ali_/integrating-accessibility-across-the-agile-development-lifecycle-by-irfan-ali-from-princeton-nj-1f2b9b2994ad) – 30 minutes

## 1.4 Choose well-supported a11y techniques
- [ ] Understand importance of coding to standards
- [ ] Understand concept of progressive enhancement 
- [ ] Understand importance of testing across various platforms, browsers, and AT
- [ ] Know which combinations of AT work best with which browsers
- [ ] Know how to tell difference between inaccessible content and incomplete or faulty a11y testing techniques
- [ ] Know when it may be appropriate to write code that overrides, supplements, or fixes bugs in browsers or AT

## 1.5 Create interactive controls/widgets based on a11y best practices

### General
- [ ] Understand native HTML widgets should be used instead of custom WAI-ARIA widgets whenever possible
- [ ] Become familiar with the keyboard interaction model for ARIA custom widgets
  - In many widgets, the keyboard interaction model is to tab to the widget as a
whole, or the active/selected element within the widget, then use the arrow keys
to navigate within the widget. The tab key is generally not used for navigation
within the widget. Other keystrokes may be recommended for certain widgets.
- [ ] Understand ARIA roles, states, and properties that may be used to communicate to a screenreader with what is occuring in the interface (for complex web applications or dynamic content)
- [ ] Read through [Code Library of a11y Examples: ARIA widgets (Deque University)](https://dequeuniversity.com/library/aria/)

### Roles
- [ ] When a custom role is assigned to an element, the custom role completely overrides the native role
  -  For example, `<li role=”button”>` will be treated as a
button by the accessibility API, not like a list item.
- [ ] Understand when creating ARIA widgets, some roles have required parent/child roles, and some roles have required attributes (semantic structure)
- [ ] Understand roles to describe the type of widget presented - e.g. "menu", "treeitem", "slider", "progressbar"
- [ ] Understand roles to describe structure of the web page - e.g. headings, regions, tables 
- [ ] Understand that the `application` role should be used sparingly, if at all, since it overrides many AT keystrokes 
- [ ] Go through [WAS Certification Prep - Role Requirements sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=2129291334#gid=2129291334)

### Properties
- [ ] Understand properties to describe widget state - e.g. "checked" for checkbox, "expanded" for menu
- [ ] Understand properties to define live regions that are likely to get updates (e.g. stock quotes), as well as an interruption policy for those updates - e.g. criticals updates in an alert dialog box, incidental updates within the page

## 1.6 Create accessible single-page applications (SPAs)
- [ ] Understand methods to notify screenreader user that new AJAX content has loaded as a direct result of user action (e.g. activating a button):
  - sending focus to new content
  - using `aria-live` to announce content without moving focus
- [ ] Understand if the AJAX content is loaded passively (i.e., not as the direct result of a user action like activating a button), users may not need to be notified that the new content has loaded. This action may be dependent on the importance and urgency of the new content, and whether the content has been inserted above the user’s current position or not. 
- Read through [ARIA and Dynamic Content (Web Accessibility)](https://www.webaccessibility.com/resource-library/platform/?platform=86) – 1 hour

## 1.7 Create content that is compatible with strategies used by persons with disabilities to access web content 

### Vision 
- [ ] Become familiar with most common screenreaders, including how they work and what parts of HTML5 and WAI-ARIA they support:
  - JAWS (Job Access with Speech) for Windows - by Freedom Scientific - [Documentation](https://support.freedomscientific.com/Products/Blindness/JawsDocumentation) 
  - NVDA (NonVisual Desktop Access) for Windows - by NV Access - [User Guide](https://download.nvaccess.org/documentation/userGuide.html)
  - Narrator for Windows - by Microsoft - [User Guide](https://support.microsoft.com/en-us/windows/complete-guide-to-narrator-e4397a0d-ef4f-b386-d8ae-c172f109bdb1)
  - VoiceOver for MacOS - [User Guide](https://help.apple.com/voiceover/mac/10.15/)
  - VoiceOver for iOS - [User Guide](https://support.apple.com/en-au/guide/iphone/iph3e2e415f/13.0/ios/13.0)
  - ChromeVox (Chromebooks) - [Chromebook Help Center](https://support.google.com/chromebook/answer/7031755?hl=en)
  - TalkBack (Android) - [User Guide](https://support.google.com/accessibility/android/answer/6283677?hl=en)
- [ ] Go through [WAS Certification Prep - Screen Reader shortcuts sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=553443064#gid=553443064)

- [ ] Become familiar with common magnifying tools:
  - ZoomText - by Freedom Scientific 
  - SuperNova - by Dolphin

- [ ] Understand how to support text enlargement in smartphones and how zoom functions work:
  - Vision a11y features in iPhone - [Overview](https://www.apple.com/accessibility/vision/)
  - Magnification in Android - [Overview](https://support.google.com/accessibility/android/answer/6006949?hl=en)
  - Font size and display size in Android - [Overview](https://support.google.com/accessibility/android/answer/11183305?hl=en&ref_topic=9079043&visit_id=638744652185833754-1484159190&rd=1)

- [ ] Understand that's common to use keyboard commands in addition to mouse to navigate to speed up interaction
- [ ] Understand users need clear borders to see where different areas start and end
- [ ] Understand users may alter colors, contrasts, and fonts
- [ ] Understand that users often combine zooming and screen reading
  - A big gap exists between users that only need the built-in zoom in the browser and users that zoom the interface 32 times and use screen readers as a complementary technique. Their strategies vary accordingly.
- [ ] Understand screenreader users may also use voice input tools to navigate 
  - Users can develop physical weaknesses associated with repetitive functions such as carpal tunnel and other limitations
- [ ] Go through [WAS Certification Prep - Other AT shortcuts sheet](https://docs.google.com/spreadsheets/d/1-E52YevqTxAYfQUZdDoMfqqumcmON9Boir6axGvvYOQ/edit?gid=717087441#gid=717087441)

### Reading
- [ ] Become familiar with readers for people with reading difficulties:
  - read&write - by TextHelp - [Overview](https://www.texthelp.com/products/read-and-write-education/)
  - Browsealoud - by TextHelp - [Overview](https://www.texthelp.com/en-gb/products/reachdeck/browsealoud-is-now-the-reachdeck-toolbar/)
  - NaturalReader - by NaturalSoft - [Overview](https://www.naturalreaders.com/)
  - Kurzweil - [Overview](https://www.kurzweiledu.com/products/products.html)
- [ ] Differentiate between screenreaders for this group and screenreaders for blind users
- [ ] Understand the importance of using text instead of images of text
- [ ] Understand typeface, color, spacing, etc. - e.g. readable fonts, typeface suggestions, font size, letter and word spacing widths

### Cognition 
- [ ] Understand importance of clean, simple layout, and presentation - e.g. providing control of as many aspects of the website as possible (with CSS)
- [ ] Understand importance of plain language
- [ ] Understand people differ in ability to process information in different forms, and be familiar with content alternatives - e.g. using sound, text, and audio to present info
- [ ] Understand images and multimedia should be used to supplement text whenever possible 
- [ ] Make sure to not avoid animated graphics, which can be distracting and increase cognitive load
- [ ] Understand users with cognitive disabilities often use AT to read and write

- Read [Cognitive Accessiblity at W3C](https://www.w3.org/WAI/cognitive/) – 15 minutes
- Read [Making Content Usable for People with Cognitive and Learning Disabilities](https://www.w3.org/TR/coga-usable/) – 8 hours

### Motor 
- [ ] Understand users have different input devices: mouse, keyboard, voice, touch/gesture
- [ ] Understand importance of large, visible, and easy to spot clickable areas 
- [ ] Understand importance to indicate what object is currently in focus
- [ ] Understand predicition and autofill are helpful because it limits number of keystrokes required when typing 
- [ ] Understand importance of creating web pages that appear and operate in predictable ways, where appearance, operation, and navigation are predictable and consistent 
- [ ] Watch [Digital Accessibility User Impact: Motor Disabilities (Level Access)](https://www.youtube.com/watch?v=nnDw7JPJBAE)

- [ ] Be familiar with point and click-based solutions:
  - Ordinary mouse
  - Tremor filtering mousepad
  - SteadyMouse - [Overview](https://www.steadymouse.com/)
  - Eye-tracking - [EyeGaze](https://eyegaze.com/) & [Tobii](https://www.tobii.com/)
  - Point scanning with switch control - [Switch Control for iOS](https://support.apple.com/en-us/119835) & [Switch Access for Android](https://support.google.com/accessibility/android/answer/6122836)
  - [MacOS Headpointer feature](https://support.apple.com/en-au/guide/mac-help/mchlb2d4782b/10.15/mac/10.15) 
- [ ] Have basic knowledge on how speech control works:
  - Voice Control for [macOS](https://support.apple.com/en-au/guide/mac-help/mh40719/10.15/mac/10.15) and [iOS](https://support.apple.com/en-us/111778)
  - Voice Access for [Android](https://support.google.com/accessibility/android/answer/6151848?hl=en)
  - Speech Recognition for [Windows](https://support.microsoft.com/en-au/windows/use-voice-recognition-in-windows-83ff75bd-63eb-0b6c-18d4-6fae94050571)

### Hearing
- [ ] Understand importance of providing alternatives for time-based media (e.g. captions or transcript)
- [ ] Understand importance of providing another way to present equivalent information for prerecorded audio-only content (e.g. transcript)
- [ ] Understand transcriptions can be available on the same screen where audio is, or through a link

### Review
- Read through [Design Considerations for Disabilities (Deque)](https://dequeuniversity.com/assets/pdf/module-design/dq-design-considerations.pdf) – 30 minutes

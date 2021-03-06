# Provide enough contrast between front and background colors

<script>$(document).ready(function () {
    setBreadcrumb([
        {"label":"WCAG criteria by project phase - Developers", "url": "./incontournables.html#dev"},
        {"label":"Provide enough contrast between front and background colors"}
    ]);
});</script>

<span data-menuitem="incontournables"></span>

**Target: **everyone, especially the mobile and tablet users, people with visual impairments, experiencing reading or attention difficulties and elderly people.   
**When: **as of design and during development.

**Description: ** 
The contrast between the text and its background, even for non-text graphic objects as long as they provide information, should be high enough.
Insufficient contrast level will have detrimental impact on users with visual difficulties and for mobile and tablets users in a very bright environment.

**Don’t: ** 
The label “film | 20h40…” does not have enough contrast. It will not be readable by all users.  

![screenshot showing text with poor contrast](images/contraste.png)

**Checklist: **
- Make sure that the contrast between the color of the background and that of the text and also for text in the form of image carrying information, is:
   - 4.5: 1 minimum for a size smaller than 24px <abbr>CSS </abbr> and 19px <abbr>CSS </abbr> in bold
   - 3: 1 minimum is sufficient for a size greater than 24px <abbr>CSS </abbr> and 19px <abbr>CSS </abbr> in bold
- Special case of non-underlined links:
   - These links must have a 3:1 contrast ratio with the surrounding text
   - These links must have a way other than the color to distinguish them on keyboard focus or mouse hover 
- Make sure that non-text GUI components, graphical objects and interface status (focus, hover) have a contrast of 3:1. This includes: buttons, radio buttons, check boxes, selection lists, navigation menus and panels, toolbars, tabs, carousels, sliders, progress bars, tooltips, graphics… 

We do not have to apply this criterion:
   - If the graphic component can not be represented otherwise: flag, logotype, real photos, screenshots, medical information diagrams using the colors of biology, gradients representing a measurement (heat maps …)
   - If a text, like a label, a data table, brings the same information as the icon or the graphic
   - If the contrast ratio of the image doesn't prevent the understanding of the content or the function
- **Important: ** for applications used primarily in mobile web or in mobility, the contrast level of the most important elements must be 7:1 in order to ensure a good readability and usability for all

**Users’ goal: **

Ease of reading for all users, especially the visually impaired, or people in a very bright environment (outdoors).

**Tool: ** 
The [Colour Contrast Analyser](http://www.paciellogroup.com/resources/contrastanalyser/) application can quickly measure colour contrast levels (free for Windows and Mac).  

**Reference <abbr>WCAG</abbr>&nbsp;:**
- <a href="https://www.w3.org/TR/WCAG21/#contrast-minimum">1.4.3 Contrast (Minimum)</a>
- <a href="https://www.w3.org/TR/WCAG21/#non-text-contrast">1.4.11 Non-text Contrast</a>
<!--  This file is part of a11y-guidelines | Our vision of mobile & web accessibility guidelines and best practices, with valid/invalid examples.
 Copyright (C) 2016  Orange SA
 See the Creative Commons Legal Code Attribution-ShareAlike 3.0 Unported License for more details (LICENSE file). -->
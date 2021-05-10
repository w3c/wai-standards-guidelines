---
title: "Changelog for W3C Accessibility Standards Overview"
title_html: "Changelog for <a href='/WAI/standards-guidelines/'>W3C Accessibility Standards Overview</a>"
nav_title: "Changelog"
lang: en
layout: default
class: tight-page

permalink: /standards-guidelines/changelog/
ref: /standards-guidelines/changelog/
github:
 repository: w3c/wai-std-gl-overview
 path: content/changelog.md

feedbackmail: wai@w3.org
footer: >
 <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributor: Tolu Adegbite.</p>
---

{::nomarkdown}
{% include box.html type="start" title="About" class="" %}
{:/}

This page is designed so translators can copy and paste from this rendered changelog page. Or, translators can use the [W3C Accessibility Standards Overview page source](https://raw.githubusercontent.com/w3c/wai-std-gl-overview/master/content/index.md).

For others, **particularly significant or substantive changes are summarized after “Significant:”**.

{::nomarkdown}
{% include box.html type="end" %}
{:/}
{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## May 2021
* In the frontmatter at the top, add `changelog: /videos/standards-and-benefits/changelog/` between ref and layout:<br>
`ref: /videos/standards-and-benefits/   # Do not change this`<br>
`changelog: /videos/standards-and-benefits/changelog/`<br>
`layout: default`<br>
* In the frontmatter, under the footer text, add `CHANGELOG.` after the date. _Leave it in all capital letters and do not translate it._<br>
`<p><strong>Date:</strong> Updated 6 January 2021. CHANGELOG.</p>`

## 6 Jan 2021 Significant
**Significant: Added links to [[What's New in WCAG 2.2 Working Draft]](/standards-guidelines/wcag/new-in-22/) and [[WCAG 3 Introduction]](/standards-guidelines/wcag/wcag3-intro/).**

* Add “2” with WCAG:
  * Change "### Web Content Accessibility Guidelines (WCAG) {#wcag}" to:<br>
  `### Web Content Accessibility Guidelines (WCAG) 2 {#wcag2}`
  * Add “2” &mdash; Change "WCAG info:" to:<br>
  `WCAG 2 info:`

* Around `- [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)`add one line of links before and two lines after:<br>
`- [``[WCAG 2 Translations]``](/standards-guidelines/wcag/translations/)`<br>
`- [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)`<br>
`- [WCAG 2.1 Standard](https://www.w3.org/TR/WCAG21/), [[What’s New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)`<br>
`- [``[What's New in WCAG 2.2 Working Draft]``](/standards-guidelines/wcag/new-in-22/)`

* Before “## Technical Specifications”, add:<br>
`### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}`<br>
`WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web.`<br><br>
`WCAG 3 info:`<br>
`* [``[WCAG 3 Introduction]``](/standards-guidelines/wcag/wcag3-intro/)`

## 11 Sep 2019 Significant
**Significant: Added links to [[Pronunciation Overview]](/pronunciation/).**

* Before “## Other Areas of W3C WAI work”, add:<br>
`### Pronunciation`<br>
`[``[Pronunciation Overview]``](/pronunciation/) &mdash; Pronunciation is about screen readers and other text-to-speech (TTS) synthesis pronouncing content properly.`

## 17 Jul 2019
* Under “## Additional Information {#moreinfo}”, in first item, change URI link to `https://www.w3.org/TR/?tag=accessibility`:<br>
`- [List of all W3C accessibility-related Standards ("W3C Recommendations") and Working Group Notes](https://www.w3.org/TR/?tag=accessibility)`

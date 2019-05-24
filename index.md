---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: W3C Accessibility Standards Overview  # Do not translate "title:". Do translate the text after "title:".
nav_title: "Standards/Guidelines" # A short title that is used in the navigation

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2020-11-11   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translators: 
# - name: "@@"   # Replace @@ with translator name
#  link: @@
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /standards-guidelines/   # Do not change this
layout: default
github:
  repository: w3c/wai-std-gl-overview
  path: index.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /standards-guidelines/   # Add the language shortcode to the end; for example /standards-guidelines/fr
feedbackmail: wai@w3.org

footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
  <p><strong>Date:</strong> Updated 13 March 2019.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-std-gl-overview/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces guidelines and other standards related to web accessibility.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction {#intro}

The World Wide Web Consortium (W3C) develops international Web standards: <abbr title="Hypertext Markup Language">HTML</abbr>, <abbr title="Cascading Style Sheets">CSS</abbr>, and many more. W3C's Web standards are called <dfn>W3C Recommendations</dfn>.

All W3C standards are reviewed for accessibility support by the Accessible Platform Architectures ([APA](/about/groups/apawg/)) Working Group.

The W3C standards and Working Group Notes introduced below are particularly relevant to accessibility.

## Accessibility Guidelines {#guidelines}

[[Essential Components of Web Accessibility]](/fundamentals/components/) shows how web accessibility depends on several components of web development and interaction working together, and how the WAI guidelines (WCAG, ATAG, UAAG) apply.

### Web Content Accessibility Guidelines (WCAG) {#wcag}

Web "content" generally refers to the information in a web page or web application, including:

* natural information such as text, images, and sounds
* code or markup that defines structure, presentation, etc.

WCAG applies to dynamic content, multimedia, "mobile", etc. WCAG can also be applied to non-web information and communications technologies (ICT), as described in [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/).

WCAG info:
- [WCAG Overview](/standards-guidelines/wcag/)
- [[WCAG 2.1 at a Glance]](/standards-guidelines/wcag/glance/)
- [How to Meet WCAG 2 (Quick Reference)](https://www.w3.org/WAI/WCAG21/quickref/)
- [WCAG 2.0 Standard {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/WCAG20/)
- [WCAG 2.1 Standard {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/WCAG21/)

### Authoring Tool Accessibility Guidelines (ATAG) {#atag}

Authoring tools are software and services that "authors" (web developers, designers, writers, etc.) use to produce web content. For example: HTML editors, content management systems (CMS), and websites that let users add content, such as blogs and social networking sites. ATAG documents explain how to:
* make the authoring tools themselves accessible, so that people with disabilities can create web content, and
* help authors create more accessible web content.

ATAG info:
- [ATAG Overview](/standards-guidelines/atag/)
- [[ATAG at a Glance]](/standards-guidelines/atag/glance/)
- [ATAG 2.0 Standard {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/ATAG/)

### User Agent Accessibility Guidelines (UAAG) {#uaag}

User agents include browsers, browser extensions, media players, readers, and other applications that render web content.

UAAG info:
- [UAAG Overview](/standards-guidelines/uaag/)
- [UAAG 2.0 Note {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/UAAG20/)

## Technical Specifications

### Accessible Rich Internet Applications (WAI-ARIA) {#aria}

ARIA provides semantics so authors can convey user interface behaviors and structural information to assistive technologies (such as screen readers). The ARIA specification provides an ontology of roles, states, and properties that define accessible user interface elements.

The ARIA suite includes <abbr title="application programming interface">API</abbr> mapping specifications that provide user agent implementation guidance. It also include modules for Graphics and Digital Publishing.

ARIA info:
- [WAI-ARIA Overview](/standards-guidelines/aria/) – includes a [list and description of modules and API mappings](/standards-guidelines/aria/#versions)
- [WAI-ARIA Authoring Practices {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/wai-aria-practices/)
- [WAI-ARIA 1.1 Standard {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/wai-aria-1.1/)

### Audio and Video {#multimedia}

- [WebVTT: The Web Video Text Tracks Format {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/webvtt/) is a format for captions, text video descriptions, and other metadata that is time-aligned with audio or video content.

- [Timed Text Markup Language (TTML) {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/ttml/) is intended to be used for transcoding or exchanging timed text information among legacy distribution content formats for subtitling and captioning.

### Evaluation {#eval}

The following resources support development of accessibility evaluation methods and tools:

- [[Accessibility Conformance Testing (ACT) Overview]](/standards-guidelines/act/) &mdash; ACT establishes and documents rules for testing the conformance of web content to accessibility standards.

- [[Evaluation and Report Language (EARL) Overview]](/standards-guidelines/earl/) &mdash; EARL is a machine-readable format for expressing test results.

Additional resources related to evaluation are listed in the [[Evaluating Web Accessibility Overview]](/test-evaluate/), including:

- [[WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology]](/test-evaluate/conformance/wcag-em/) &mdash; WCAG-EM is an approach for determining how well a website conforms to Web Content Accessibility Guidelines (WCAG).

### Personalization

[[Personalization Overview]](/personalization/) &mdash; Personalization involves tailoring the user experience to meet the needs and preferences of the individual user. Content authors can use personalization standards to provide a default design and enable user personalization with minimal work.

## Other Areas of W3C WAI work

- [[Mobile Accessibility at W3C]](/standards-guidelines/mobile/)

- [[Cognitive Accessibility at W3C]](/cognitive/)

## Additional Information {#moreinfo}

- [List of all W3C accessibility-related Standards ("W3C Recommendations") and Working Group Notes {% include_cached different.html label="to W3C site" %}](https://www.w3.org/TR/#tr_Accessibility__All_)

- [[Web Accessibility Laws & Policies]](/policies/) lists governmental laws and policies relating to web accessibility in countries and regions around the world. Many of these reference W3C accessibility standards.

- [[Why Standards Harmonization is Essential to Web Accessibility]](/standards-guidelines/harmonization/)

- [[Referencing and Linking to WAI Guidelines and Technical Documents]](/standards-guidelines/linking/)

- [How WAI Develops Accessibility Guidelines through the W3C Process: Milestones and **Opportunities to Contribute**](/standards-guidelines/w3c-process/)

![illustration showing the guidelines for the different components, detailed description at https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.png" | relative_url }})

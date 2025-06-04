---
layout: page
title: Case studies
permalink: /case-studies/
menu: true
---


## Accessibility revamp of website.
Improved the user experience by getting full W3C AA compliance on the university website. It was the first university website to achieve ASPIRE Education Gold 100% compliance. The university also won the 2022 UCISA Transformation Award for the provision of accessible content across University digital platforms, of which the website was a key part.

### Objectives
1. Get key parts of the university website fully AA compliant. This was no small task because the website had over 100 different contributors. While we could control many parts of the templates, we could not control every aspect.
2. Try to understand the actual needs of users better. Very often accessibility compliance can focus on ticking boxes rather than looking at how people interact with the website.

### Actions
1. Gain a deeper understanding of accessibility compliance and measuring tools.
2. Gain a better understanding of tools such as JAWS, NVDA and VoiceOver.
3. Interview several people with vision impairment.
4. Work with people from student services teams to help audit content from across the university website, gain better insight into users’ needs.
5. Make fixes to HTML, restyle elements to make them bigger, easier to press or read, easier to tab through, etc.

### Lessons learned
Gaining complete AA compliance on a large website is hard. It’s possible to make structural changes to make sure coloured contrast, buttons, accordions, modals and other components meet the requirements. However much accessibility relies on content. The university had well over one hundred content creators. Part of accessibility is therefore educating content creators about the use of alt text for images, using simple language etc.

## University website rebrand

### Objectives
The university adopted a new brand in 2022. The needed to be applied to all of the public website and internal web systems. The timeline for adopting the new brand was tight. The new brand was finalised in August 2022 and needed to be implemented on the website by the end of September 2022 ready for the new academic year. The core of the design was a new homepage, but many other key pages had to be completely redesigned. Thousands of other pages on the website would still need to work and be on brand.

### Actions
1. Work in detail on a new homepage design. I received Adobe InDesign prototypes from the brand agency which had to be reinterpreted to work as a responsive website using our existing in-house content management system and code.
2. Identify and build key layout components which could be reused on other key pages on the marketing website.
3. Identify quick wins for most of the website, such as adopting new fonts and colours. Work out how these could be incorporated into existing page designs with minimal coding changes, in a way that could be applied quickly to large parts of the website.

### Lessons learned
I was able to rework much of the website brand with relatively simple code changes to switch existing colours to new colours, and switch the font. I was able to keep some of the design shapes because they resembled the new brand.

Building new components for key pages such as the homepage took much longer, and far more effort was directed at this. Many components were only inspired by the agency designs, requiring redesign in Figma, then rebuilding in HTML, CSS and JavaScript.


## Performance analysis and revamp of css/js lazy loading.

### Objectives
Improve PageSpeed Insights scores for key pages on the website.

### Actions
1. Analysis using PageSpeed Insights and Lighthouse. Core Web Vitals.
2. Pinpointing main bottlenecks and issues.
3. Loading CSS as needed, rather than in one large file.
4. Loading above the fold CSS inline.
5. Optimisation of font loading.
6. Loading JavaScript assets dynamically as needed rather than in one large file.
7. Lazy loading images. Using webp images.
8. Overall PageSpeed scores improved significantly, particularly on mobile. 

### Lessons learned
This project ended up being quite a bit larger than originally intended. Analysis of the website performance led to a number of discoveries, many of which had complex solutions.

One major problem was to get above the fold CSS to load early and quickly. The website had many thousands of pages, often with very different content and designs above the fold. I therefore had to carefully isolate the required CSS, often using different sets of CSS inline depending on page type.

JavaScript performance was improved by loading much of it dynamically, as soon as the relevant component on the page approached scrolling into view. Core JavaScript file size was reduced dramatically.

The biggest problem of all - and for which there was no ideal solution - was loading 3rd party marketing JavaScript. The impacted performance hugely. There was therefore a tension between user experience and page speed, and the needs of marketing to track users across the site and interact with them with chat widgets.


## Website analysis and redesign project
### Objectives
Reduce the size and scope of the university website, which had become a massive and disjointed collection of webpages with confused scope.

### Actions
1. Carried out a series of business needs analysis, user needs analysis.
2. Scope of the university website. Data analysis looking at pageviews, user journeys.
3. Interviews with internal stakeholders: executive group, marketing, comms, academic schools, students, prospective students.
4. Need to group student-focused content in a single hub rather than spread across many different areas of the university website.
5. Need to reduce the size and scope of academic school websites.
6. Need to move internal student-focussed content to Moodle.
7. Need to simplify global navigation.

### Lessons learned
A large project with scope to radically change the university’s website. Resulted in the Guide - a hub with all help pages in one area, rather than spread across many sites.
Data analysis pointed to how little much academic school content was viewed. Too much importance placed on non-recruitment.
Resulted in new designs for the website, with much simpler navigation, smaller sites, more focused on marketing.


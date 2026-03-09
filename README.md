# Accessibility-Master
A repository to help you learn about digital accessibility. A curated list of web‑accessibility resources for developers, designers, and anyone interested in inclusive web experiences.

This repo is intended to grow over time.

# The Basics
- [W3C.org](https://www.w3.org/TR/WCAG22/): Short for "Web Content Accessibility Guidelines". The latest version is WCAG 2.2
- [Accessibility fundamentals](https://learn.microsoft.com/en-us/training/paths/accessibility-fundamentals/) by Microsoft
- [Learn the basics of web accessibility](https://learn.microsoft.com/en-us/training/modules/web-development-101-accessibility/) by Microsoft
- [Accessibility Features Reference](https://developer.chrome.com/docs/devtools/accessibility/reference) by Google
- [Accessibility Resources for Developers](https://www.ssa.gov/accessibility/developer_resources.html) by the US Social Security Administration
  - [ANDI Web Accessibility Test Tool](https://github.com/SSAgov/ANDI), the Accessible Name & Description Inspector is an open source accessibility test tool you can use to check for 508 compliance of web content.
  - [SSA 508 Test Method](https://www.ssa.gov/accessibility/testmethod.html) The Social Security Administration uses an Accessibility Test Method based on the Section 508 ICT Testing Baseline.
  - [YANKI Accessibility Troubleshooting Tool](https://www.ssa.gov/accessibility/yanki/yanki.html) temporarily removes problematic HTML and ARIA attributes
  - [Alternative Text Guide](https://www.ssa.gov/accessibility/files/SSA_Alternative_Text_Guide.pdf) Alternative text is used to describe images, charts, diagrams, buttons, and other elements in a way that provides information to users. However, there can be issues if the alternative text is incorrect, confusing, or lacks the necessary context. The SSA aims to create meaningful alternative text by following the guidance in this reference guide.

## POUR Principles:
  1. Perceivable: The user can perceive all website elements with 
  2. Operable: the webpage can be operated with a variety of devices
  3. Understandable: The content is easy to understand and interact with
  4. Robust: Operation allows for mistakes on the client side and can compensate for them.

## Acronyms
These are commonly used when talking/writing about accessibility and inclusion:
- [WCAG](https://www.w3.org/TR/WCAG22/): Web Content Accessibility Guidelines 
- [W3C](https://www.w3.org/): Web 3 Consortium 
- AT: assistive technology 
- SR: screen reader 
- a11y: accessibility 
- alt-text: alternative text  
- [EAA](https://ec.europa.eu/social/main.jsp?catId=1202): European Accessibility Act 
- [ADA](https://www.ada.gov/): Americans with Disabilities Act 
- [UNCRPD](https://social.desa.un.org/issues/disability/crpd/convention-on-the-rights-of-persons-with-disabilities-crpd): United Nations Convention on the Rights of Persons with Disabilities

## Courses
- [Digital Accessibility Foundations by W3C](https://www.w3.org/WAI/courses/foundations-course/)
- [Building for Everyone Series by GDG Vienna](https://gdg.community.dev/events/details/google-gdg-vienna-presents-getting-started-with-designing-for-web-accessibility-2025-01-23/) also recorded on [Accessibility First](https://www.accessibilityfirst.at/webinar-series)
- [DHS Trusted Tester Certification Study Group by GDG Vienna](https://gdg.community.dev/events/details/google-gdg-vienna-presents-dhs-trusted-tester-study-group-1-what-is-section-508-functional-performance-criteria-and-testing-tools/) (ongoing + recorded)

# Web Accessibility Testing Tools
- [WAVE](https://wave.webaim.org/) Tool by WebAIM: An automatic testing tool that provides WCAG references for each error, alert, and feature it finds. As with every automatic testing tool, none of them is perfect, but getting acquainted with this one in particular is particularly helpful because the [WebAIM Million Report](https://webaim.org/projects/million/) uses it. Learning the limitations of automated testing will help you interpret the findings better.
- [Contrast Checker](https://webaim.org/resources/contrastchecker/), and arguably even better: the [Link Contrast Checker](https://webaim.org/resources/linkcontrastchecker/?fcolor=0000FF&bcolor=FFFFFF) to compare 3 colors against each other
- [CoBliss Color Blindness Simulator](https://www.color-blindness.com/coblis-color-blindness-simulator/) 
- [Accessibility Insights for Web](https://accessibilityinsights.io/)
- [WCAG EM Report Tool](https://wcag-em-report-tool-2021-redesign.netlify.app/)
- [NVDA](https://www.nvaccess.org/download/), a free screen reader
- Wondering what screen readers people use? Consult the latest [WebAIM screen reader survey](https://webaim.org/projects/screenreadersurvey10/).

## Browser Extensions
- [Colorless A11Y - Color blindness empathy test](https://vinceumo.github.io/A11Y-Color-Blindness-Empathy-Test/)
- [WAVE Chrome Extension](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) 
- [axe DevTools](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd?hl=en-US&utm_source=ext_sidebar) 
- [Visual ARIA](https://chrome.google.com/webstore/detail/visual-aria/lhbmajchkkmakajkjenkchhnhbadmhmk/related)
- [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/accessibility/scoring) 

## Alt‑Text
- Does this image need alt text? Follow the [alt-text decision tree](https://www.w3.org/WAI/tutorials/images/decision-tree/) by W3C
- Need some inspiration for what to write? The Nielsen Norman Group has a good article to get you started: [NNG Write Alt Text](https://www.nngroup.com/articles/write-alt-text/)

## Universal Design
- [Center of Universal Design](https://design.ncsu.edu/research/center-for-universal-design/)
- [Universal Design for Learning](https://www.nea.org/professional-excellence/student-engagement/tools-tips/universal-design-learning-introduction) (UDL) – The Why, What, and How of Learning. Especially relevant if you are developing courses, onboarding material, or professional‑development content.
- [Accessibility: Build the foundation for inclusive learning](https://learn.microsoft.com/en-us/training/courses/accessibility-build-foundation-inclusive-learning) by Microsoft

## Content Creation
[Creating accessible content with Microsoft 365](https://learn.microsoft.com/en-us/training/modules/accessible-content-m365/) by Microsoft 

## Typography
- [Typographer vs Accessibility](https://www.youtube.com/watch?v=XQkCBdEEWCE)

# Laws & Directives
- [European Accessibility Act](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882) (EAA) 
- [Accessibility Standards at the European Level](https://accessible-eu-centre.ec.europa.eu/accessibility-standards-european-level_en)
- [Americans with Disabilities Act](https://www.ada.gov/law-and-regs/ada/) (ADA) 
- [UK Equality Act](https://www.gov.uk/guidance/equality-act-2010-guidance)
- [Accessibility for Ontarians with Disabilities Act](https://www.aoda.ca/the-act/) (AODA)

# Accessibility Specialists:
- [Adrian Roselli](https://adrianroselli.com/)
- [Leonie Watson](https://tink.uk/) (blind a11y tester)
- [Manuel Matuzovic](https://matuzo.at/) (a11y Specialist, focused on HTML and CSS)
- [Scott O’Hara](https://www.scottohara.me/) (a11y Specialist)
- [Sara Soueidan](https://www.sarasoueidan.com/) (a11y Specialist)
- [Steve Faulkner](https://html5accessibility.com/stuff/)
- [Paul J. Adam](https://pauljadam.com/)
- [Scott O’Hara](https://www.scottohara.me/)
- [Eric Eggert](https://yatil.net/)
- [Makoto Ueki](https://weba11y.jp/news/) (a11y Specialist, Infoaxia, Inc.)

# Advanced:
- [DOM accessibility tree](https://developer.chrome.com/blog/full-accessibility-tree)
-  [WAI‑ARIA Overview](https://www.w3.org/WAI/standards-guidelines/aria/) WAI‑ARIA stands for Accessible Rich Internet Applications. It defines a way to make web content and applications more accessible, especially dynamic interfaces built with HTML, JavaScript, and related technologies.
-  [Accessibility an UI Developemtn Resources](https://medium.com/@b_atish/ui-development-accessibility-resources-6c27d0b680fb): includes resources in Spanish & French

## ASP.NET Core
[Create accessible web apps by using ASP.NET Core](https://learn.microsoft.com/en-us/training/modules/aspnet-core-accessibility/) by Microsoft

## Gaming
[Gaming accessibility fundamentals](https://learn.microsoft.com/en-us/training/paths/gaming-accessibility-fundamentals/) by Microsoft

parts of [Gaming accessibility fundamentals](https://learn.microsoft.com/en-us/training/paths/gaming-accessibility-fundamentals/) by Microsoft
- [Introduction to gaming and disability](https://learn.microsoft.com/en-us/training/modules/intro-to-gaming/) by Microsoft
- [Accessibility best practices for games and platforms](https://learn.microsoft.com/en-us/training/modules/games-and-platforms1/) by Microsoft
- [Accessibility best practices for gaming hardware](https://learn.microsoft.com/en-us/training/modules/hardware-devices/) by Microsoft


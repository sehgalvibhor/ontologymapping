---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2021/05/10/71298a2d-7028-45e6-a707-be0642ca796c-removebg-preview-1.png"
  navigation:
  - link: "/"
    link_text: OntoMap
  - link: "#about"
    link_text: About
  - link: "#team"
    link_text: Team
  cta:
    url: "/"
    button_text: Home
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: OntoMap<br><strong>Automated Ontology Mapping for Cardiovascular Ailments</strong>
  content: A model exposed to the medical community as a web application that allows
    users to upload ECHO reports and extract a standardized representation of their
    input.
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: 'See on GitHub '
  image:
    image: "/uploads/2021/05/10/localhost_5000_index-ipad.png"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: 1-column-text
  block: one-column-1
  headline: Overview
  content: Next to Chest X-ray, Echocardiogram (also known as cardiac ultrasound)
    is the single highest-volume cardiac imaging test practiced in millions of hospitals
    worldwide. There are numerous guidelines documents on what and how to measure
    heart anatomy and function in an echocardiogram. This has led to different hospitals,
    medical professionals and patients, speaking a different language when it comes
    to communicating ECHO results. Harmonization of reports is needed not just to
    directly improve clinical communications, but also to leverage the ontology labels
    in pursuit of advanced machine learning on cardiac ultrasound imaging. We propose
    a hierarchical ontology mapping model that can map free-text in ECHO reports to
    a standardized ontology. This model is exposed to the medical community as a web
    application that allows users to upload ECHO reports and extract a standardized
    representation of their input.
  slug: ''
- template: 2-column-text
  block: two-column-1
  col_1:
    content: A user can upload an echo report in the CSV format and the web application
      runs preprocessing pipeline and model predictions in the backend to generate
      the three-level ontology. Users can explore all the processed reports and individually
      view each by selecting them.<br>
    headline: Report Upload
    slug: ''
  col_2:
    headline: Data Dictionary Upload
    slug: ''
    content: Hospitals can upload a data dictionary that is a compilation of possible
      ECHO report free-text sentences used within their facility. This option enables
      hospitals to test the tool their vernacular style of writing reports. The tool
      will read the sentences in the data dictionary and generate the ontology for
      each sentence in the data dictionary. The hospitals can then review the resulting
      ontology on the web tool.<br>
- template: full-width-media-element
  block: media-1
  image: "/uploads/2021/05/11/ontology-mapping-1.png"
  slug: ''
  caption: OntoMap Architecture
- template: hero-banner-w-image
  block: hero-2
  background_image: "/uploads/2021/05/11/ontology-mapping-1.png"
  image:
    image: ''
    alt_text: ''
  headline: ''
  content: ''
  cta:
    enabled: false
    url: ''
    button_text: ''
- template: simple-footer
  block: footer-1
  content: Made with ❤︎ in Canada

---

---
title: About Us
date: 2020-03-01T00:00:01+00:00
layout: custom
headerTransparent: false
rss_ignore: true
outputs: html
sections:
- template: hero
  options:
    paddingTop: false
    paddingBottom: false
    borderTop: false
    borderBottom: false
    classes: ''
    theme: base
    backgroundColorCustom: ''
  headings:
    heading: "An organisation that does not evaluate, is one that is not learning or getting better."
    text: '- Professor David Halpern, Chief Executive, The Behavioural Insights Team.'
    headingColorCustom: ''
    subHeadingColorCustom: ''
    textColorCustom: '#405965'
  height: ''
  alignHorizontal: left
  alignVertical: middle
  background:
    backgroundImage: ''
    backgroundColorCustom: ''
    monotone: false
    opacity: ''
  image:
    image: "images/stopwatch.jpeg"
    overlap: false
    border: false
    borderRadius: true
    shadow: true
    altText: "A young businessman experiencing stress during a late night at work"
- template: grid
  options:
    theme: base
  heading: "The team"
  subHeading: ""
  contentType: team 
  sortBy: weight
  limit: 2
  columns: 4
  columnsMobile: 12
  marginBottom: 2
  align: center 
  card:
    partial: card
    border: true
    padding: true
    shadow: true
    showThumbnail: true
    showThumbnailLink: false 
    showFooter: true
    showTitle: true
    showTitleLink: false 
    showDate: false
---

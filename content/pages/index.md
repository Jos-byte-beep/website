---
title: Home
slug: /
sections:
#Afbeelding rechts, tekst links
  - type: GenericSection
    title:
      text: "Week 2: Building up again Luchthavenweg 10."
      color: text-dark
      type: TitleBlock
    text: >
      The immense space is a good start point
      <div style="display: flex; justify-content: space-between; align-items: flex-end; gap: 40px;">
        <img src="images/DJI_0786.jpg" alt="First Image" style="width: 50%; height: 300px; object-fit: cover;">
        <img src="images/DJI_0811.jpg" alt="Second Image" style="width: 50%; height: 300px; object-fit: cover;">
        <img src="images/DJI_7979.jpg" alt="Second Image" style="width: 50%; height: 300px; object-fit: cover;">
      </div>
    badge:
      label: 3th of February
      color: text-primary
      type: Badge
    elementId: "february"
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16       
#Afbeelding links, tekst rechts
  - type: GenericSection
    title:
      text: "Week 1: Start demolition work."
      color: text-dark
      type: TitleBlock
    text: >
      First step is demolition!
    media:
      url: /images/DJI_0824.mp4
      altText: Unblock your team boost your time to production preview
      elementId: "january"
      type: VideoBlock
    badge:
      label: 31th of January
      color: text-primary
      type: Badge
    elementId: "january"
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
#Afbeelding rechts, tekst links
  - type: GenericSection
    title:
      text: "Week 0: The move to Luchthavenweg 10."
      color: text-dark
      type: TitleBlock
    text: >
      Welcome to the move to our new location at Luchthavenweg 10!
    media:
      url: /images/afbeelding.jpeg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: 29th of January
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
seo:
  metaTitle: Home - Demo site
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

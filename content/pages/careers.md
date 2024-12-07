---
title: help-center
slug: careers
sections:
  - title:
      text: Access Support Whenever You Need It
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Section subtitle
    text: >+
      The **Letsdial Help Center** is a comprehensive resource designed to
      assist businesses in maximizing their communication efficiency. It
      provides guidance on using virtual phone systems, troubleshooting issues
      like call forwarding and SMS delivery errors, and setting up features such
      as voicemail, custom greetings, and international calling. With tools for
      managing shared numbers, internal team discussions, and detailed call
      analytics, the Help Center ensures seamless operations and improved
      customer engagement

    actions:
      - label: Help-Center
        url: 'https://www.letsdial.com/help-center/'
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
        altText: help-center
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Knowledge Base
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
  - title:
      text: FAQs
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - title: 1. What services does Letsdial offer?
        subtitle: Sales
        text: >+
          Letsdial provides virtual phone systems with features like call
          forwarding, voicemail, call recording, and customizable greetings. It
          also supports international calling and team collaboration through
          shared numbers and analytics dashboards​

        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: 2. Can I use Letsdial for international calls?
        subtitle: Marketing
        text: >+

          Yes, Letsdial supports international calling with competitive rates.
          You can select numbers from various countries and manage global
          communications effortlessly

        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: 6. Does Letsdial offer customer support?
        subtitle: Customer Support
        text: >+

          Yes, Letsdial provides 24/7 customer support via email, chat, or phone
          to assist with any issues or questions you may have

        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

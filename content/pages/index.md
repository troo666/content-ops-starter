---
title: Home
slug: /
sections:
  - title:
      text: Develop Robust and Adaptive AI for Dark Web Threat Detection
      color: text-light
      styles:
        self:
          textAlign: center
          fontWeight: 700
      type: TitleBlock
    subtitle: 'Check, Prevent and Eliminate Personal Data Leaks'
    text: ''
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    colors: bg-dark-fg-light
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
        fontWeight: 700
    type: GenericSection
    actions:
      - type: Button
        label: Twitter
        altText: ''
        url: '/https://x.com/s_appdevelop'
        showIcon: true
        icon: twitter
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Button
        label: View on Github
        altText: ''
        url: '/https://github.com/troo666/OwlGuardx'
        showIcon: true
        icon: github
        iconPosition: right
        style: secondary
        elementId: ''
  - type: ImageGallerySection
    subtitle: Our Sponsors
    images:
      - type: ImageBlock
        url: /images/empathy-logo.svg
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        url: /images/wellster-logo.svg
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/vise-logo.svg
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/telus-logo.svg
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/contenful-logo.svg
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/sanity-logo.svg
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        url: /images/rangle-logo.svg
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: move-to-right
    colors: bg-dark-fg-light
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      text: Everything You Need to Keep Your Data Safe
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: Password Manager
        subtitle: Take care of your passwords
        text: >
          The application has the function of safely storing passwords in an
          encrypted form and checking by advanced ai model if your password has
          been leaked somewhere, if it has been, you will be notified
          immediately.
        actions: []
        elementId: null
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
            borderStyle: dotted
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Finding data leaks function
        subtitle: Check if your data has been leaked somewhere
        text: >
          Advanced AI algorithms available in the application will very quickly
          search all data available on the web in search of your publicly
          available data like passwords or card numbers.
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Remove your data from the web
        subtitle: Delete your data from the web
        text: >
          The application has the ability to remove your private data from the
          internet through advanced algorithms so that no unauthorized person
          can use it.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
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
    badge:
      label: This is a badge
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

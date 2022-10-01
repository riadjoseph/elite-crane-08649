---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: Une formation en 9 modules pour bien démarrer et réussir son entreprise.
    subtitle: '100% en ligne, avec votre coach, et financée par le CPF'
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
      - type: Link
        label: Learn More
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/hero.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-28
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    text: >
      Ce que Rezopreneurs leur a apporté et comment ils ont mis en pratique leur
      vision collectives.
    badge:
      type: Badge
      styles:
        self:
          textAlign: left
      label: étude de cas
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
      - type: Link
        label: Watch Video
        url: /
        showIcon: true
        icon: playCircle
        iconPosition: left
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-16
          - pb-16
          - pl-16
          - pr-16
        justifyContent: center
        flexDirection: row
        alignItems: center
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
    media:
      url: /images/hero-3.jpg
      altText: Where did everyone go?
      caption: Team meeting
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    subtitle: >-
      Comment 3 amis ont démarré et scalé leur entreprise de revente de
      vêtements
    title: '3 amis, 1 projet, 1 vision'
  - colors: colors-h
    subtitle: Ils en parlent
    elementId: ''
    images:
      - type: ImageBlock
        url: /images/apple.svg
        altText: Apple
        caption: Apple
      - type: ImageBlock
        url: /images/google-play.svg
        altText: Google Play
        caption: Google Play
      - type: ImageBlock
        url: /images/playstation.svg
        altText: PlayStation
        caption: PlayStation
      - type: ImageBlock
        url: /images/gatsby.svg
        altText: Gatsby
        caption: Gatsby
      - type: ImageBlock
        url: /images/xbox.svg
        altText: Xbox
        caption: Xbox
      - type: ImageBlock
        url: /images/skype.svg
        altText: Skype
        caption: Skype
      - type: ImageBlock
        url: /images/zcool.svg
        altText: ZCOOL
        caption: ZCOOL
    spacing: 3
    columns: 7
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
    imageSizePx: 240
    type: MediaGallerySection
  - colors: colors-a
    elementId: ''
    title: Les modules de la formation
    subtitle: >-
      Financeable et 100% en ligne. Ne ratez pas votre opportunité, places
      limitées pour garantir la qualité.
    items:
      - type: FeaturedItem
        title: Marketing digital
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Business plan
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Management
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/focused.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
    columns: 3
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - type: FeaturedItemsSection
    colors: colors-a
    elementId: ''
    items:
      - title: Marketing digital
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
      - title: Business plan
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
      - title: Management
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/focused.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
    actions: []
    columns: 3
    enableHover: true
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-3
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
  - type: FeaturedItemsSection
    colors: colors-a
    elementId: ''
    title: null
    subtitle: null
    items:
      - title: Anglais pour le business
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
      - title: L'Arabe et comprendre la culture
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
      - title: Management
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/focused.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions: []
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
        type: FeaturedItem
    actions: []
    columns: 3
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-a
    title: Votre compte CPF
    text: |
      Avec votre compte CPF, vous financez votre formation entièrement
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Link
        label: Learn More
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-6
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
  - elementId: ''
    colors: colors-a
    title: Aides pour la Création d'entreprise
    text: |
      Les aides auxquels vous accèdez en démarrant votre entreprise.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Link
        label: Learn More
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/hero-2.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-6
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
  - elementId: ''
    colors: colors-a
    variant: variant-b
    title: >-
      Outre que les modules de formations, vous trouverez ces articles
      pertinents à vos besoins actuellement
    actions:
      - type: Link
        label: voir tous les guides pour la création d'entreprise
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-0
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    showDate: true
  - colors: colors-f
    elementId: ''
    title: Des réponses à vos questions
    items:
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation. At the office, working together is often a
          distraction, on remote, it could be motivation. At the office, working
          together is often a distraction, on remote, it could be motivation.
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation. At the office, working together is often a
          distraction, on remote, it could be motivation. At the office, working
          together is often a distraction, on remote, it could be motivation.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-20
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        fontWeight: '400'
        textAlign: center
    type: FaqSection
    actions:
      - altText: ''
        url: /faq
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
        type: Link
        label: See all
  - elementId: ''
    colors: colors-a
    variant: variant-a
    testimonials:
      - quote: >
          Such a great experience to be using this product. It really helped
          with what I needed help with.
        name: Carla Rogers
        title: Happy customer
        image:
          type: ImageBlock
          url: /images/carla.jpg
          altText: Photo of Carla Rogers
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-28
          - pb-56
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: TestimonialsSection
  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Get early access
    text: >
      Sign up your team today to be the first to try out our new product to
      increase your team’s productivity
    form:
      type: FormBlock
      variant: variant-b
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
---

---
title: Rezopreneurs
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: Une formation en 9 modules pour bien démarrer et réussir son entreprise.
    subtitle: >-
      100% en ligne, à distance, d’une durée de 10 jours, avec un coach en
      direct.
    actions:
      - type: Button
        label: En savoir plus
        url: '/#etre-epaule'
        style: primary
        altText: En savoir plus
        icon: chevronRight
        iconPosition: right
        showIcon: true
    media:
      type: ImageBlock
      url: /images/post-1.jpg
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
  - colors: colors-a
    elementId: ''
    images:
      - type: ImageBlock
        url: /images/Capital-Management copy.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
      - type: ImageBlock
        url: /images/cnews-logo.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
      - type: ImageBlock
        url: /images/LOGO-LeParisien.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
      - type: ImageBlock
        url: /images/logo-cadre-et-dirigeant-magazine-420x139.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
    spacing: 1
    columns: 4
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: full
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-7
          - pb-9
          - pl-3
          - pr-3
        justifyContent: center
        borderRadius: x-small
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
    imageSizePx: 240
    type: MediaGallerySection
    title: Ils en parlent
  - elementId: etre-epaule
    colors: colors-f
    text: >
      Seul, on va plus vite. Ensemble, on va plus loin. Rezo'preneurs, c'est
      pour toute personne souhaitant ou ayant créer une entreprise.


      Rezo’preneurs est un organisme de formation privé qui a pour principale
      ambition d’aider le maximum de personne à gagner en compétences dans le
      monde de l’entrepreneuriat.


      L’expérience de l’équipe dirigeante et enseignante est mise en œuvre afin
      de garantir une qualité irréprochable de nos formations et ainsi permettre
      à chaque stagiaire d’être épaulé durant son apprentissage et dans la
      création et/ou le développement de son activité .


      Rezo’preneurs est aussi un réseau d’entrepreneurs de tous horizons.
    actions:
      - type: Button
        label: Les modules de la formation
        style: primary
        altText: Modules de la formation
        icon: chevronRight
        iconPosition: right
        showIcon: true
        url: '/#modules'
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
          - pt-16
          - pb-16
          - pl-16
          - pr-16
        justifyContent: center
        flexDirection: row
        alignItems: center
        borderRadius: none
        boxShadow: xx-large
        borderColor: border-primary
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
      altText: Etude de cas
      caption: Team meeting avec Rezopreneurs
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Être épaulé
  - colors: colors-a
    elementId: modules
    title: Les modules de la formation
    subtitle: >-
      Éligible au financement CPF et 100% en ligne. Ne ratez pas votre
      opportunité. Les places sont limitées pour garantir la qualité.
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
          - pt-28
          - pb-3
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
      - title: Anglais
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions:
          - type: Link
            label: Formation Anglais
            altText: ''
            url: /formation-anglais
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
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
          - pb-3
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
      - title: Formation en langue Arabe
        text: >
          Si vous souhaitez tisser des liens commerciaux avec l’Afrique du nord
          ou le moyen-orient, l’arabe est un réel atout pour votre activité.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions:
          - type: Link
            label: Formation Arabe
            altText: Formation Arabe
            url: /formation-arabe
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
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
          - pb-3
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
    title: Coaching personnalisé
    text: >
      Sollicitez une coaching individuel 100% gratuit afin de vous aider à
      developper votre projet.
    actions:
      - type: Link
        label: En savoir plus
        url: /contactus
        showIcon: true
        icon: arrowRight
        iconPosition: right
        altText: En savoir plus
    media:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-14
          - pb-6
          - pl-4
          - pr-4
        alignItems: flex-start
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
    title: Nos formateurs
    text: >
      Nos formateurs sont choisis pour leurs expertises métiers, leurs
      compétences pédagogiques et leur connaissance de l'entreprise.
    actions:
      - type: Link
        url: /contactus
        showIcon: true
        icon: arrowRight
        iconPosition: right
        label: Posez vos questions
        altText: Posez vos questions
    media:
      type: ImageBlock
      url: /images/careers.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-6
          - pb-12
          - pl-4
          - pr-4
        alignItems: flex-start
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
  - type: FaqSection
    colors: colors-f
    elementId: ''
    title: Questions fréquentes
    subtitle: null
    actions:
      - type: Link
        label: Nous contacter
        altText: Nous contacter
        url: /contactus
        showIcon: true
        icon: mail
        iconPosition: right
        elementId: ''
    items:
      - question: 1/ Quelles formations peut-on faire grâce au CPF ?
        answer: >
          Le CPF vous donne droit à diverses formations reconnues par l'État
          dans de nombreux domaines tels que : le management, la finance, le
          droit, la communication et les réseaux sociaux, l'informatique etc.
        type: FaqItem
      - question: '2/ Quelles formations pour devenir autoentrepreneur ? '
        answer: >
          Cela dépend de votre projet professionnel. Rezo’Preneurs vous aide à
          acquérir des bases solides qui sont nécessaires dans la construction
          de votre projet, de la simple idée au lancement du projet. Par exemple
          il vous faut choisir un statut juridique correspondant le plus à votre
          activité, être capable de faire une étude approfondie de votre projet,
          comment communiquer avec vos futurs clients, comment assurer une
          gestion efficace de votre projet.
        type: FaqItem
      - question: >-
          3/ Je souhaite faire une formation courte mais compétente que choisir
          ?
        answer: >
          Nos formations sont dispensées par des coachs compétents et eux-mêmes
          entrepreneurs. Vous serez donc formés pendant 10 jours sur diverses
          thématiques complètes et variées. Et si vous le souhaitez, vous pouvez
          obtenir gratuitement un accompagnement personnalisé par l'un de nos
          coachs.
        type: FaqItem
      - question: 4/ Comment savoir si je suis éligible au CFP ?
        answer: >
          Sur le site
          https://www.moncompteformation.gouv.fr/espace-prive/html/#/ vous
          pouvez prendre connaissance de votre solde de formation disponible sur
          votre compte. Ensuite, il ne vous reste plus qu'à choisir vos
          formations.
        type: FaqItem
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
          - pt-32
          - pb-12
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
        textAlign: left
      actions:
        justifyContent: flex-start
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
---

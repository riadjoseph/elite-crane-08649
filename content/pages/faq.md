---
title: FAQ
layout: PageLayout
sections:
  - colors: colors-a
    elementId: ''
    title: Questions fréquentes
    items:
      - question: 1/ Quelles formations peut-on faire grâce au CPF ?
        answer: >
          Le CPF vous donne droit à diverses formations reconnues par l'État
          dans de nombreux domaines tels que : le management, la finance, le
          droit, la communication et les réseaux sociaux, l'informatique etc.
      - question: '2/ Quelles formations pour devenir autoentrepreneur ? '
        answer: >
          Cela dépend de votre projet professionnel. Rezo’Preneurs vous aide à
          acquérir des bases solides qui sont nécessaires dans la construction
          de votre projet, de la simple idée au lancement du projet. Par exemple
          il vous faut choisir un statut juridique correspondant le plus à votre
          activité, être capable de faire une étude approfondie de votre projet,
          comment communiquer avec vos futurs clients, comment assurer une
          gestion efficace de votre projet.
      - question: >-
          3/ Je souhaite faire une formation courte mais compétente que choisir
          ?
        answer: >
          Nos formations sont dispensées par des coachs compétents et eux-mêmes
          entrepreneurs. Vous serez donc formés pendant 10 jours sur diverses
          thématiques complètes et variées. Et si vous le souhaitez, vous pouvez
          obtenir gratuitement un accompagnement personnalisé par l'un de nos
          coachs.
      - question: 4/ Comment savoir si je suis éligible au CFP ?
        answer: >
          Sur le site
          https://www.moncompteformation.gouv.fr/espace-prive/html/#/ vous
          pouvez prendre connaissance de votre solde de formation disponible sur
          votre compte. Ensuite, il ne vous reste plus qu'à choisir vos
          formations.
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
    type: FaqSection
  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Get early access
    text: >
      Sign up your team today to be the first to try out our new product to
      increae your team’s productivity
    form:
      type: FormBlock
      variant: variant-b
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - type: TextFormControl
          name: Nom
          label: Nom
          hideLabel: false
          placeholder: Your home address
          isRequired: false
          width: full
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      text:
        textAlign: center
---

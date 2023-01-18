---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Contact
sections:
  - type: ContactSection
    elementId: ''
    colors: colors-h
    backgroundSize: full
    title: Nous contacter
    text: >
      Merci de votre interêt pour nos formations. Rezo'preneurs pour les
      entrepreneurs d'aujourd'hui.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: Nom et prénom
          label: Nom et prénom
          placeholder: Nom et prénom
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: Votre adresse email
          label: Votre adresse email
          placeholder: Votre adresse email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: Votre téléphone
          label: Votre téléphone
          placeholder: Votre téléphone
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: Consent
          label: Je donne mon consentement pour être contacté(e)
          isRequired: 'false'
          width: full
        - type: SelectFormControl
          name: Formation
          label: Formation
          hideLabel: false
          defaultValue: Faites votre choix...
          options:
            - Autre sujet
            - Anglais
            - Arabe
          isRequired: true
          width: full
      submitLabel: Send Message
    media: null
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---

---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Erase Wrinkles and Restore Youth with Botox
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Botox is the most popular non-surgical cosmetic procedure in the United
      States. Due to its long and successful history, it’s one of the most
      trusted wrinkle-minimizing treatments in existence. Millions of people
      receive injections of this popular neurotoxin every year. But despite its
      rising popularity, you may have questions or even trepidation about this
      celebrity-favorite procedure.
    actions:
      - label: Learn More
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/botox.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
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
  - type: FeaturedItemsSection
    title:
      text: How Botox Works
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: >
          Botox is a type of neurotoxin (botulinum toxin type A) that blocks
          nerve signals to specific muscles. When the muscles can no longer
          fully contract, they can no longer contribute to the formation of
          wrinkles. As the targeted muscles relax, the face appears smoother,
          softer, and younger.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
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
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
      - title: ''
        subtitle: ''
        text: >
          Botox injections are most commonly used around the eyes, mouth, and
          forehead. That’s because these are the areas most commonly impacted by
          fine lines. It’s important to note that Botox can’t eliminate wrinkles
          caused by gravity or sun damage. It can only minimize wrinkles caused
          by muscle contractions and facial expressions.
        image:
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
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
      - title: ''
        subtitle: ''
        text: "Studies show that Botox has a high patient satisfaction rate.\_Besides smoothing existing wrinkles, it’s also a preventative treatment that can slow the development of future facial lines.\n"
        image:
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
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
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: ''
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
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Book Your FREE Consultation
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: >
      We’re excited to welcome you for your first Botox appointment! When you
      arrive, we’ll sit down with you and review your treatment steps. We’ll
      invite you to tell us about specific concerns and ensure we fully
      understand your treatment expectations. Then, we’ll carefully mark the
      treatment areas and gently clean the skin.
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
        - name: Phone Number
          label: Phone Number
          hideLabel: true
          placeholder: Phone Number
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
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

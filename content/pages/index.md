---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-6
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: "Welcome to my portfolio. \U0001F44B\U0001F3FB"
    subtitle: Geeking. Exciting. Accelerating.
    text: |+
      ##### **Get your coffee for the ride ☕.**

    actions:
      - type: Button
        label: 'Projects | Blogs '
        showIcon: false
        icon: arrowRight
        style: primary
        url: /blog
      - type: Link
        altText: ''
        url: |
          https://www.linkedin.com/in/mohamed-zayed-cie-2023/
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://github.com/mozayed007'
        showIcon: true
        icon: github
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/bf517d4c2a4b8908e7b1292ee383a89cc0ba4328_hq.gif
      altText: Get your coffee for the ride ☕.
      caption: Get your coffee for the ride ☕.
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-40
          - pb-40
          - pl-15
          - pr-15
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
  - type: QuoteSection
    colors: colors-b
    quote: >+
      **“There are no regrets. If one can be proud of one’s life, one should not
      wish for another chance.”**

    name: – Saber
    title: (Fate Stay Night)
    styles:
      self:
        height: screen
        width: wide
        padding:
          - pt-72
          - pb-5
          - pr-4
          - pl-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
    backgroundImage:
      type: BackgroundImage
      url: /images/304364.jpg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 70
  - elementId: ''
    colors: colors-c
    variant: variant-a
    title: 'Recent Projects | Blogs :'
    actions:
      - type: Link
        label: See all
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/anime-recommender.md
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
          - pt-28
          - pb-48
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
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: See more
    showAuthor: false
  - type: TextSection
    colors: colors-e
    variant: variant-a
    text: |+
      ## Aim High !

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
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      text:
        textAlign: center
  - type: FeatureHighlightSection
    colors: colors-e
    backgroundSize: inset
    title: 'Find me also on Kaggle:'
    text: |
      Sharing Notebooks There.
    actions:
      - type: Link
        label: My Profile
        url: 'https://www.kaggle.com/lordmz'
        showIcon: true
        icon: arrowRight
        iconPosition: right
    backgroundImage:
      type: BackgroundImage
      url: /images/wp8740316-python-code-wallpapers.jpg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 90
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
          - pb-72
          - pr-4
          - pl-4
        justifyContent: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start 
  - type: ContactSection
    colors: colors-d
    title:  Have a question ?
    text: |+
      ### Feel free to DM me whenever you want. I'll try to respond ASAP.  
    form:
      type: FormBlock
      elementId: sign-up-form
destination: mozayedpentest007@gmail.com      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit form
      styles:
        submitLabel:
          textAlign: center
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
    backgroundSize: full

addTitleSuffix: true
metaTags: []
---

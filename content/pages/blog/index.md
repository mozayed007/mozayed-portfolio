---
layout: PostFeedLayout
title: Projects | Blogs
numOfPostsPerPage: 10
postFeed:
  showDate: true
  showAuthor: false
  showExcerpt: false
  showReadMoreLink: true
  readMoreLinkLabel: Join adventure
  variant: variant-c
  colors: colors-e
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: center
bottomSections:
  - type: ContactSection
    colors: colors-d

    elementId: null
    backgroundSize: full
    title: Have a question ?
    text: "### Feel free to DM me whenever you want. I'll try to respond ASAP \U0001F338\n\n"
     form:
      type: FormBlock
      elementId: sign-up-form
      destination: mozayedpentest007@gmail.com
      action: /.netlify/functions/submission_created
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
          label: Sign me up to get news
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
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
 addTitleSuffix: true
 metaTags: []
---


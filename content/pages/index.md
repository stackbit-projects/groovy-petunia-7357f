---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    variant: variant-c
    colors: colors-f
    width: wide
    height: tall
    bottomGap: none
    topGap: none
    contentWidth: small
    contentAlignHoriz: left
    contentAlignVert: bottom
    textAlign: left
    title: 'We have a product, and it''s pretty spactacular'
    text: |
      ## Here are some more reasons why it's so great. 
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: 'https://www.stackbit.com/'
        style: secondary
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
      url: /images/STAY BACKGROUND.png
  - elementId: ''
    colors: colors-a
    width: wide
    height: short
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-b
    badge: {}
    title: WHat folks say about us
    subtitle: What our customers say about us
    testimonials:
      - type: Testimonial
        quote: >
          > # **I found a dog at a shelter, but maybe she found me!&#xA;This
          food really makes her happy.**
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          type: ImageBlock
          url: /images/dianne-ameter.jpg
          altText: Product Marketing Manager
      - quote: >-
          “It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.”
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          url: /images/dianne-ameter.jpg
          altText: Product Marketing Manager
        logo:
          elementId: ''
          altText: lorem-ipsum
          caption: lorem-ipsum
          opacity: 100
          type: ImageBlock
          url: /images/Frame 157@2x-80d7a619.png
        elementId: lorem-ipsum
    type: TestimonialsSection
  - elementId: ''
    colors: colors-a
    width: wide
    height: tall
    topGap: medium
    bottomGap: medium
    contentWidth: large
    contentAlignHoriz: left
    contentAlignVert: middle
    textAlign: center
    variant: variant-a
    badge: {}
    title: Latest news
    subtitle: Featured blog posts section example
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    type: FeaturedPostsSection
  - type: FeaturedPostsSection
    variant: variant-b
    colors: colors-c
    width: wide
    height: short
    contentWidth: medium
    contentAlignHoriz: center
    contentAlignVert: middle
    bottomGap: none
    topGap: none
    title: What's included?
    textAlign: center
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
  - elementId: ''
    colors: colors-a
    width: wide
    height: short
    topGap: medium
    bottomGap: medium
    contentWidth: small
    contentAlignHoriz: center
    contentAlignVert: middle
    textAlign: left
    variant: variant-a
    badge: {}
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: CtaSection
  - type: CtaSection
    variant: variant-b
    colors: colors-c
    width: wide
    height: short
    textAlign: left
    contentAlignHoriz: center
    contentWidth: medium
    bottomGap: none
    topGap: none
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
  - type: TextSection
    colors: colors-f
    width: wide
    height: tall
    contentWidth: small
    contentAlignHoriz: center
    contentAlignVert: middle
    bottomGap: none
    topGap: none
    textAlign: center
    badge:
      label: Small text
    title: The Section Title
    subtitle: The section subtitle
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
  - type: ContactSection
    variant: variant-b
    colors: colors-h
    width: wide
    height: tall
    textAlign: left
    title: Join our club
    bottomGap: none
    topGap: none
    text: >-
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not.
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Fisherman holding lobster
    form:
      type: FormBlock
      idAttr: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
---

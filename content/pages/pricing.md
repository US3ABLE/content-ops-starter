---
title: Pricing
slug: pricing
sections:
  - title:
      text: Flexibl Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: What Is Our Budget?
    plans:
      - type: PricingPlan
        title: Free Trial
        price: Free
        details: Credit card required
        description: ''
        features:
          - 2 Users
          - 2 Devices
          - Limited Bandwidth
        image:
          type: ImageBlock
          url: /images/image (3).png
          altText: Pricing plan 1
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - title: Basic
        price: $15
        details: per month
        description: ''
        features:
          - 3 Users
          - 5 Devices
          - Modes & Routines
          - Feature four
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Get Basic
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Business
        price: $99
        details: per month
        description: ''
        features:
          - 25 Users
          - Unlimited Devices
          - Unlimited Customisation
          - 24/7 Support
          - Modes & Routines
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: Get Business
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
            textAlign: left
        type: PricingPlan
      - title: Enterprise
        price: $299
        details: per month
        description: ''
        features:
          - Unlimited Users
          - Unlimited Devices
          - Unlimited Bandwidth
          - 24/7 Priority Support
          - Advanced Configuration & Customisation
          - Modes & Routines +
          - Unlocked Access To Beta Features
        image:
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: 'Get Enterprise '
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
isDraft: false
---

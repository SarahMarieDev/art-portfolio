---
type: PageLayout
title: Sarah's Portfolio
colors: colors-a
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
  url: /images/bg5.jpg
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'I’m a developer, digital artist, and consultant.'
    subtitle: >-
      This is a collection of my projects and artworks from the past few years.
      Feel free to contact me for hire, collab, questions or just to say hello!
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
    type: HeroSection
    actions: []
    text: |
      Stay tuned for more projects...
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all artwork
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/painterly-collage.md
      - content/pages/projects/pixel-art-simple-landscape.md
      - content/pages/projects/pixel-art-sprites.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Artwork
addTitleSuffix: true
socialImage: /images/Untitled.jpeg
---

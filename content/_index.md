---
title: Welkom
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: NEI-therapie
      text: Zachte en effectieve ondersteuning bij emotionele en lichamelijke klachten
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: banner.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      text: |
        # NEI-therapie
        ## Zachte en effectieve ondersteuning bij emotionele en lichamelijke klachten

        Voel je dat er iets wringt, maar kun je er geen vinger op leggen? NEI helpt je naar de kern.

        * Voor mensen die voelen dat praten alleen niet genoeg is.
        * Voor wie lichamelijke klachten ervaart zonder dat er een duidelijke oorzaak is te vinden.
        * Voor wie vastloopt in werk, relaties of zichzelf in herhalende patronen en wil begrijpen waarom.
        * Voor wie zichzelf beter wil leren kennen, van binnenuit.
        * Voor ouders die merken dat hun kind niet lekker in z’n vel zit.
        * Voor wie klaar is om oude ballast los te laten.

         Nieuwsgierig wat NEI voor jou kan doen? Ik help je graag.
  - block: cta-card
    content:
      text: "Benieuwd hoe NEI-therapie jou kan helpen? Neem contact op!"
      button:
        text: "Contact"
        url: /contact
    design:
      background:
        text_color_light: true
      spacing:
        padding: ["6", "6", "6", "6"]                   
       
---

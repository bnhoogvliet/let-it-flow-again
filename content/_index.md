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
        # NEI therapie voor mens en dier

        NEI staat voor Neuro Emotionele Integratie en combineert inzichten uit zowel de Westerse als Oosterse gezondheidsleer. Denk aan elementen uit de psychologie, acupunctuur en neurologie. 
        
        Deze methode helpt om op een milde manier emotionele spanningen, fysieke klachten en onverwerkte ervaringen los te laten — zonder langdurige gesprekken of het herbeleven van pijnlijke gebeurtenissen.

        Met Nei Therapie help ik je om je lichaam en geest te herstellen zodat je weer kunt leven vanuit je ware potentieel.
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

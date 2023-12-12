---
layout: home
header:
  title: Edén

  text: >
    Jag skapar personliga möbler i trä och hjälper dig med dina byggprojekt!
  action: # action button is optional
    label: Kontakta mig
    url: '#contacts'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: Om mig
    text: Jag heter Torbjörn Edén och har lång erfarenhet av snickeri och hantverk i trä. Jag har renoverat flera hus och skapat mer än 100 unika föremål och möbler, allt från skärbrädor till matbord. Nu är jag redo att ta tag i dina projekt. Jag kan skapa unika inredningsdetaljer till dig eller hjälpa dig renovera ditt kök och allt där emellan.
    actions:
      - title: Kontakta mig
        url: '#contacts'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: Tjänster och produkter
    services:
      - title: Byggprojekt
        text: Jag hjälper dig med dina byggprojekt. Allt från köksrenoveringar till altanbygge.
        icon: bi-hammer
      - title: Möbler
        text: Jag bygger personliga möbler efter dina önskemål.
        icon: bi-bookshelf
      - title: Inredning
        text: Jag skapar mindre föremål för ditt hem. T.ex skärbrädor, lampor eller ljuslyktor.
        icon: bi-lamp

  - type: portfolio.html
    section_id: portfolio
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

  - type: contact.html
    section_id: contacts
    title: Kontakta mig
    text: >-
      Är du redo att starta ditt nästa projekt med mig? Ring mig eller skicka ett mail så kör vi igång!
    actions:
    - title: +1 (202) 555-014
      icon: bi-telephone-fill
    - title: E-Mail
      icon: bi-envelope-fill
      url: mailto:contact@yourwebsite.com
    - title: Twitter
      icon: bi-twitter
      url: '#'
    - title: Facebook
      icon: bi-facebook
      url: '#'

---

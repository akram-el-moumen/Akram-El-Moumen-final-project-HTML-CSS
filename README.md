# Makanak 🌿

**Makanak** is a responsive, trauma-informed mental health awareness and support web platform built for Morocco. Designed with warm, calming aesthetics, the platform provides a safe digital space for emotional recovery, survivor storytelling, guided breathing exercises, and access to pro-bono mental health specialists.

##  Project Structure

Akram-El-Moumen-final-project-HTML-CSS/
├── index.html                  # Main landing page
├── package.json                # Project dependencies (Tailwind CSS)
├── README.md                   # Project documentation
└── public/
    ├── css/
    │   ├── input.css           # Tailwind CSS source file
    │   ├── output.css          # Compiled Tailwind CSS
    │   └── style.css           # Additional custom styles
    ├── images/                 # Hero imagery, icons, and section graphics
    └── pages/
        ├── stories.html        # Survivor stories & articles
        ├── specialists.html    # Free therapy & volunteer specialists
        └── contact.html        # Contact & support resources

## Responsiveness

Built with a mobile-first layout using Tailwind CSS breakpoints (`max-sm` and `max-md`) alongside custom media queries in `public/css/input.css` to adapt across mobile screens, tablets, and desktops.
After completing the whole desktop version, i went back to the mobile version and finally the tablet version

## Built with 

**HTML**
**TAILWINDCSS**
**CSS**

## Resources

- icons from (https://icon-sets.iconify.design/)
- images are AI genrated

## code structure

- header ==== fixed in all the responsive views, and the menu button in the mobile and tablet has been done with the checkbox methode and the peer utility
- main ==== contain multiple sections 
- footer ==== the same website footer used in the four pages
- the colors used in the website are the brown and orange gradients

**60-Second Guided Breathing:** Visual step-by-step grounding exercise (*Breathe In 4s → Hold Gently 4s → Let It Go 6s*)  styled with CSS `conic-gradient` progress rings.
**Community Stories (`public/pages/stories.html`)**
    Real reflections and recovery stories shared across Morocco, alongside an anonymous story submission form.
**Volunteer Specialists (`public/pages/specialists.html`)**
    Directory of pro-bono mental health specialists offering free sessions.
**Contact & Helplines (`public/pages/contact.html`)**
    Direct contact channels and emergency support info, including Morocco's **National Listening Line (`8350`)**.
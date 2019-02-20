# Design System

> A Design System is the single source of truth which groups all the elements that will allow the teams to design, realize and develop a product


> A Design System is a product which is going to help the actors of a project build other products


> a Design System is a set of deliverables
- Tools for designers & developers, patterns, components, guidelines…
- But also abstract elements such as brand values, shared ways of working, mindset, shared beliefs (which are often the most difficult thing to achieve)…

^ Pulled from [here](https://uxdesign.cc/everything-you-need-to-know-about-design-systems-54b109851969)

## What Is It?

1. Sketch library
2. Styleguide (think: Colors, fonts, illustrations)
3. Utliity / Pattern Library (think components: Buttons, pop ups, inputs)
4. Coding standards
5. ... Plus more!

## Why Do We Need It?
- Help centralize material and maintain standards among a large team
- Consistency saves times, money and instils trust in our users

## How Do We Implement It?
- Figure out who will be using it
- Align teams around shared goals
- Decide if the product / system will be loose or stict. Loose meaning it's there if you decide to adopt / follow, strict being system adoption is manadatory
- Decide if the development of the system will be distributed (will many people be contributing? Better for overall adoption, but harder to manage) or centrally managed (easier to manage, but system adoption is slower/more difficult). Either way, it's recommended to allow everyone to participate.


## Design System Examples:

(IBM)       [https://www.carbondesignsystem.com/]
            
            - Really great docs


(Shopify)   [https://polaris.shopify.com/]
            
            - This one has a LOT of content
            - Side note: It would actually be kind of cool to do a #10 like the "paper" on right side / main bullet (h3) on the left side

(Figma)     [https://www.designsystems.com/]
            
            - I like the show/hide fontsize/color and the layout

(LF)        [https://sites.agorafinancial.com/promos_2/LF/production/pubs/general/common/css/guide/]
            
            - Version 0.01. Just to demo

---

### RANDOM NOTES

*System:*
- `.main` and `.footer` will have be set to `max-width: 1000px;`. These containers will be centered on page.
- Colors are like `.text-pub`, `.bg-pub`, `.text-primary`, `.bg-error`
- You will need to add margins to paragraphs, header, footer, h1-h6, buttons, etc. They do not come padded.
- `.header`, `.main`, `.footer` are primary classes
- Breakpoints? 1080px (tablet) and 540px (mobile)
- Agree on break points (540, 1080)? 360 is most common mobile screen size for AF... (after we agree can set hide_on_mobile, show_only_desktop)
- Margins are like `.mb-`1-4, `.mr-`1-4, `.ma-`1-4, `.mx-`1-4, `.my-`1-4
- Padding is like `.pb-`1-4, `.pr-`1-4, `.pa-`1-4, `.px-`1-4, `.pa-`1-4
- Coloring: text-[pub|color|state], bg-[pub|color|state], btn-[pub|color|state], btn-outline-[pub|color|state]
- Coloring (links) use: text-[pub|color|state]
- Default a page using class on <body> e.g.: theme-[pub] or `.theme-dark`
- Add smthing like <body data-color=""> to pull in for dynamic theme color

*General*
- Once we have our production design system ironed out we could move to another dept. (e.g. marketing, copy writer, etc)

### QUESTIONS
- What catchy name should we give this system / product? (e.g. Zambini, trackasaurus, Polaris, CarbonDesign, etc.)

### TODO
[x] Remove dash around `.aside`

### Wishlist:
[ ] - Add `.hide-sm-up` `.hidebr`
[ ] - hr styles (h-(1-4) (for height on HRs))
[ ] - Checkboxes styles
[ ] - Radios styles
[ ] - Consider '.text-tiny, .text-sm, .text-md, .text-lg, .text-xl...'
[ ] - Create a mockup of promo / OF with comments about what we (w/in LF) call each section (eyebrow, hero, form, subhead, Y/NO call to actions)

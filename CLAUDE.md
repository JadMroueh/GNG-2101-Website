# Team Z14 Product Website

## What this is

A marketing and documentation website for a one-hand adaptive cutting station. The product was designed by Team Z14 for GNG2101 (Introduction to Product Development and Management for Engineers) at the University of Ottawa. Five student engineers. The site is a course deliverable and a showcase piece, not a commercial storefront.

## The client

An elementary school student with limited hand mobility, reached through her teacher and CIL Western Wisconsin.

- Dominant hand: weak thumb, cannot grip well, but can push and drag.
- Other arm: can push and rotate, cannot grip.
- Goal: cut paper independently, without an adult holding the sheet or operating a tool.

Write about her with respect. No pity framing. No medical language beyond what is listed above. Do not name her.

## The product

Four subsystems. Describe all four on the site.

1. Adjustable angled wooden board. The teacher sets the angle and locks it before use. The angle brings the work surface toward the child instead of forcing her to reach.
2. Magnet attachment system. A galvanized steel plate sits on the board. The paper lays flat. Magnetic strips hold it down. The board raises and locks with the paper secured.
3. 3D printed wearable brace. Worn on the dominant hand. Holds a Slice 10408 ceramic blade facing downward. The child drags her hand forward to cut. No button. No trigger. The teacher straps the brace on.
4. Rubber feet stabilizer. Mounted on the bottom of the board. Stops sliding during the cut.

## Design priorities

In order: safety, usability, reliability, portability, simplicity. If the site ever ranks or frames the design goals, use this order.

## Key components

- Slice 10408 ceramic blade (finger friendly, the core cutting component)
- Galvanized steel sheet (Home Depot)
- Wooden easel base
- Magnet Strips
- 3D printed brace (uOttawa Makerstore)
- Rubber feet

## Numbers

Use these only if the site needs them. Both come from team analysis, not from a public source. Label them as team estimates on the page.

- Bill of materials, prototype total: about $78.61 retail before tax.
- Addressable market estimate: about 200,446 children. Derived as 35% of North American children with cerebral palsy who have hand involvement, plus children with congenital upper limb differences.

Do not invent new figures. Do not add pricing, timelines, user counts, or performance claims that are not in this file. If a number is needed and not here, leave a TODO and ask.

## Writing style for all site copy

- Short sentences. Active voice only.
- No em dashes. Use commas or periods.
- No semicolons.
- No setup phrases. No "in conclusion." No "it is important to note."
- No unnecessary adjectives or adverbs.
- No marketing clichés. No "revolutionize," "game changer," "unlock," "seamless," "empower."
- Speak to the reader with "you" where it fits.
- Data and concrete examples over adjectives.

## Suggested structure

Adjust with Jad before building.

- Home: what the product is, who it is for, the four subsystems in one line each.
- How it works: the cut sequence from setup to finished cut.
- Design: the four subsystems in detail, with the priority order and the reasoning behind each choice.
- Safety: the ceramic blade, the downward orientation, the locked board, the rubber feet.
- Team: five members, Z14, GNG2101, uOttawa.

## Build constraints

- Static site. No backend. No database. No auth.
- Must run locally with no build step if possible, or a single standard toolchain if not.
- Accessible by default. Keyboard navigation. Real contrast. Alt text on every image. The product is an accessibility product, so the site should hold the same standard.
- Responsive. Assume a TA or judge opens it on a phone.

## Open TODOs

- Photos of the prototype are not in this repo yet. Use placeholders and mark them.
- Confirm the five team member names and roles before publishing the team page. Jad is Design Engineer and DFX Lead.

Most people are going to open it on their phone
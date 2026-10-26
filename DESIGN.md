# Design — Dornville Jean-Louis Mandé memorial

## Surface

`index.html` — a read-mode life, full-bleed at the open, paper for the story.

## Visual world

Guyane, then the winter he was sent into, then the town he came home to. The first screen is the river. The reading that follows is warm paper. Deep green returns only for the closing line.

## Palette

| Role | Value | Use |
|------|-------|-----|
| Night | `#081610` | page ground behind the hero and the footer |
| Canopy | `#10281f` | closing band |
| River | `#1c5874` | links |
| Mist | `#d5e6ea` | dates on the hero |
| Clay | `#c6a36a` | eyebrows on dark |
| Clay deep | `#8a5e2e` | labels on paper |
| Paper | `#f3eee6` | story ground |
| Ink | `#241910` | body text |
| Ink soft | `#5c4c3e` | captions, secondary prose |

## Typography

- Display: Fraunces
- Body: Source Serif 4
- Labels: Outfit, small, tracked uppercase
- Body size 1.125rem, measure about 64ch

## Signature

The name is stacked on the river photograph, left aligned, not centered. A five-part ledger sits up over the bottom of the photograph. Chapter numbers are italic Fraunces. Illustrations are captioned as evocations. The register’s signalement is set like a form, because that description is the only face the papers give.

## Images

- `images/oyapock.jpg`, `images/verdun.jpg`, `images/honours.jpg`, `images/cayenne.jpg` — evocations
- `images/citation.jpg`, `images/livre-dor.jpg`, `images/matricule.jpg` — the documents

## Responsive

Below 860px the ledger, the man/signalement split, the citation split, and the papers become one column. Below 560px the ledger is a single stack and the side margins tighten. Hero height is `min-height: 100dvh`.

## Languages

A fixed bar at the top switches the whole page: English, Français, Kriyòl, Deutsch. The choice is remembered in the browser. The printed citation stays in French in every language. The Kriyòl is the Creole of the French islands, Martinique and Guadeloupe spelling, so readers from those islands can read it; a line at the foot says people from Guyane will follow it too. German is there because the family account uses the word Ausbildung for the Martinique years, and because Verdun was the German front. The page credit names Maurice Holda, the generation after his great-grandfather, with a link to nagacodex.cloud.

## Motion

A slow scale on the hero image, and a fade-up on chapters, only when the visitor has not asked for reduced motion. The grain sits on a fixed overlay and does not scroll with the text.

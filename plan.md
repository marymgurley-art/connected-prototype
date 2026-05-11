# Plan: Interactive Dinosaur Book Spec

## What We're Building
A written product spec for an interactive dinosaur book — covering content, layout, interactions, games, and sound — so Mary has a clear blueprint before choosing a tool or building anything.

## Dinosaur List
15 lesser-known dinosaurs chosen for their wild, surprising qualities:

| # | Dinosaur | Why It's Cool |
|---|----------|---------------|
| 1 | Amargasaurus | Had spiky sails running down its neck |
| 2 | Carnotaurus | Bull horns on a meat-eater's head |
| 3 | Therizinosaurus | Claws up to 3 feet long — but ate plants |
| 4 | Parasaurolophus | Hollow crest worked like a trumpet |
| 5 | Pachycephalosaurus | Dome skull used for head-butting |
| 6 | Zuul | Named after the Ghostbusters monster; had a club tail |
| 7 | Nigersaurus | Mouth shaped like a vacuum cleaner |
| 8 | Kosmoceratops | Had 15 horns on its face |
| 9 | Oviraptor | Called "egg thief" but was actually innocent |
| 10 | Deinonychus | The real-life inspiration for Jurassic Park raptors |
| 11 | Cryolophosaurus | Lived in Antarctica; nicknamed "Elvisaurus" |
| 12 | Nasutoceratops | Giant nose, big horns, looked like a bull |
| 13 | Maiasaura | The "good mother" — built nests and raised babies |
| 14 | Epidexipteryx | Tiny feathered dinosaur with ribbon-like tail feathers |
| 15 | Dreadnoughtus | One of the largest animals to ever walk the earth |

## Page Layout
Each dinosaur page follows this structure:
- Full-page photo or illustration at the top
- Dinosaur name in big bold text
- Short fun paragraph (2-3 sentences, age 6 reading level)
- Browseable dino list on the left for navigation
- Tap-to-hatch egg revealing 3 facts one at a time
- Sound effect button (roar, stomp, trumpet, etc.)
- Mini-game button at the bottom

## Mini-Games (4 types, rotating across dinosaurs)
| Game | How It Works | Best For |
|------|-------------|----------|
| Fossil Dig | Tap to uncover hidden bones in the dirt | Deinonychus, Oviraptor |
| Egg Hatch | Tap to crack the egg and reveal the baby dino | Maiasaura, Oviraptor |
| Matching Game | Match the dino to its food or feature | Therizinosaurus, Nigersaurus |
| Quiz | Pick the right answer; sound plays for correct/wrong | All dinos |

## Content Rules
- Reading level: age 6 (short sentences, simple words)
- Tone: exciting, fun, lots of exclamation points
- No scary, violent, or gory content
- Facts should be surprising and delightful, not dry

## No-Code Tool Requirements
The chosen tool must support:
- Image and photo embedding
- Text formatting (big headers, paragraphs)
- Tap/click interactions and simple animations
- Sound effect embedding or linking
- Mini-game embedding (via iframe or plugin)
- Works in browser on desktop and tablet
- No login required for the child to use it

## Risks
- High-quality free dino photos may require sourcing from museum archives or licensed image sites
- Some no-code tools don't support sound natively — may need workarounds
- Mini-games may need a separate tool (e.g. Genially, BookWidgets) embedded inside the main book

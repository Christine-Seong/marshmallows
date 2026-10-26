# Marshmallows

A healing app prototype for **Prospect Terrace Park** in Providence, RI: a place for people who are worn out by everyday life to empty their heads and rest by interacting with the park.

By Christine Seong, Lauren Hong and Jeewoo Kim.

## What's in it
- **Home**: greeting, weather widget, and a round lens that slowly roams over the park map.
- **Sound map**: tap a spot to preview its sound in place, then zoom in to listen.
- **Info map**: swipe through short stories about the park; markers follow the cards.
- **Listening**: rhetorical questions float over the scene; reply in a DM-style bar.
- **Reflection**: write (handwritten or sans serif) or draw on torn paper over a photo of where you are.
- **Letters**: each reflection folds into an envelope and floats in your archive.

## Run it
Open `index.html` in a browser. It's a single page with no build step.

## Notes
- The weather widget shows sample data.
- Park sounds are generated in the browser with the Web Audio API, not recordings.
- Letters are saved in your browser (localStorage) when opened outside claude.ai.
- Neulis Neue isn't on Google Fonts, so Lexend stands in for it.

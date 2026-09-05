# Move — Personal Workout Guide

A personal 4–5 day workout guide built around a long loop resistance band, bodyweight movements, and 40–45 minute sessions. It combines a weekly training plan with a searchable exercise library.

**Live site:** [View the workout guide](https://paola13ulep.github.io/move/)

**Created by:** [Christine Paola Ulep](https://christinepaolaulep.vercel.app/)

## Features

- Five-day plan with an optional recovery day
- Lower-body, upper-body, full-body, cardio, and core sessions
- Searchable and filterable exercise library
- Custom workout builder with day, workout type, duration, exercise selection, and editable targets
- Saved custom workouts stored locally in the browser
- 41 movements, including twelve warm-up and cooldown stretches in the exercise gallery
- Mandatory dynamic warm-up and cooldown stretches in every built-in and custom workout
- Two-position anatomical exercise illustrations with highlighted working muscles
- Form instructions, modifications, sets, reps, and rest guidance
- Weekly completion tracking stored locally in the browser
- Responsive layout for phones and desktops

## Use locally

No installation or build step is required.

1. Download or clone the repository.
2. Open a terminal in the project directory.
3. Serve the `dist` directory:

```bash
python -m http.server 8000 --directory dist
```

4. Open `http://localhost:8000` in your browser.

## Publish with GitHub Pages

1. Upload this project to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push to the `main` branch. The included workflow publishes the `dist` folder automatically.

## Project structure

```text
dist/
├── assets/anatomy/     # Anatomical exercise illustrations
├── index.html
├── styles.css
└── app.js
```

## License

The original code and written content are licensed under the [MIT License](LICENSE).

This guide is for personal educational use and is not medical advice. Stop exercising if you feel sharp pain, dizziness, or unusual shortness of breath.

## Privacy

This project has no accounts, analytics, advertising, or project-operated server database. Workout completion and custom plans are saved only in your browser's local storage. See the [Privacy Policy](PRIVACY.md).

## Illustration inspiration

The anatomical presentation was inspired by [Makatserchyk / Makatolga's Shutterstock portfolio](https://www.shutterstock.com/g/Makatolga) and the [Gym Visual exercise catalog](https://gymvisual.com/content/10-list-of-exercises). Those catalogs do not provide the long-loop resistance-band exercises required for this guide; the illustrations used here were generated specifically for the project from exercise-by-exercise prompts.

The inspiration credit does not imply endorsement or grant permission to reuse artwork from Shutterstock or Gym Visual.

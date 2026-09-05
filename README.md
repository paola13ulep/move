# Move — Personal Workout Guide

Move is a personal 4–5 day workout guide built around long loop resistance-band
and bodyweight exercises, with sessions lasting approximately 40–45 minutes.

I created this project because a long loop resistance band is the main workout
equipment I have at home. I often forget which exercises to perform, their
proper positions, and how many repetitions I have completed. Move keeps my
routines, exercise instructions, and weekly progress organized in one place.

**Live site:** [View the workout guide](https://paola13ulep.github.io/move/)

**Created by:** [Yours truly](https://christinepaolaulep.vercel.app/)

## Features

- Five-day workout plan with an optional recovery day
- Lower-body, upper-body, full-body, cardio, and core sessions
- Searchable and filterable exercise library
- Custom workout builder with day, workout type, duration, exercise selection,
  and editable targets
- Saved custom workouts stored locally in the browser
- 41 movements, including twelve warm-up and cooldown stretches
- Dynamic warm-up and cooldown stretches included in every built-in and custom
  workout
- Two-position anatomical illustrations with highlighted working muscles
- Form instructions, modifications, sets, repetitions, and rest guidance
- Weekly completion tracking stored locally in the browser
- Responsive layout for phones and desktop computers

## Workout Builder

The custom workout builder makes it possible to create a routine by selecting:

- Workout day
- Workout type
- Session duration
- Exercises
- Sets and repetitions
- Timed targets
- Rest periods

Warm-up and cooldown stretches are automatically included in every custom
workout.

## Exercise Library

The exercise gallery contains long loop resistance-band exercises, bodyweight
movements, core exercises, cardio movements, and stretches.

The gallery can be searched and filtered by exercise name, workout category,
and equipment type.

## Use Locally

No installation or build step is required.

1. Download or clone the repository.
2. Open a terminal in the project directory.
3. Serve the `dist` directory:

```bash
python -m http.server 8000 --directory dist
```

4. Open `http://localhost:8000` in your browser.

## Publish With GitHub Pages

1. Upload the project to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push your changes to the `main` branch.

The included GitHub Actions workflow automatically publishes the contents of
the `dist` directory.

## Project Structure

```text
.github/
└── workflows/          # GitHub Pages deployment workflow

dist/
├── assets/
│   ├── anatomy/        # Anatomical and bodyweight illustrations
│   └── exercises/      # Resistance-band exercise illustrations
├── ATTRIBUTION.md      # Illustration information and acknowledgements
├── index.html          # Website structure
├── styles.css          # Layout and visual design
└── app.js              # Exercises, workout builder, and local storage
```

## Local Storage

Move does not require an account. Custom workouts and weekly completion
progress are stored locally in the browser.

Clearing the browser's site data may remove saved workouts and progress.

## Privacy

This project has no accounts, advertising, analytics, or project-operated
server database. Workout completion and custom plans remain in the browser's
local storage.

See the [Privacy Policy](PRIVACY.md) for more information.

## Illustration Inspiration

The exercise illustrations were generated specifically for this project using
exercise-by-exercise prompts.

Their general anatomical presentation was visually inspired by the
[Makatserchyk/Makatolga Shutterstock portfolio](https://www.shutterstock.com/g/Makatolga)
and the [GymVisual exercise catalog](https://gymvisual.com/content/10-list-of-exercises).

These sources are acknowledged for visual inspiration only. The credit does not
imply endorsement, affiliation, or permission to reuse original artwork from
Shutterstock or GymVisual.

See [`dist/ATTRIBUTION.md`](dist/ATTRIBUTION.md) for additional information.

## Disclaimer

This guide is intended for personal planning and general informational
purposes. It is not medical advice or a substitute for guidance from a
qualified fitness or healthcare professional.

Stop exercising if you experience sharp pain, dizziness, unusual shortness of
breath, or other concerning symptoms.

## License

The source code is licensed under the [MIT License](LICENSE).

Exercise illustrations and other visual assets are excluded from the MIT
License. Their permitted uses are described separately in
[`LICENSE-ASSETS`](LICENSE-ASSETS).

# CodeAlpha App Development Projects

Flutter and Dart source for three CodeAlpha app development tasks.

## Flutter app

Open the `flutter-apps` folder in Android Studio or VS Code. It contains Android and web runners and three screens in one Flutter app:

- **Flashcards:** flip cards, navigate the deck, and add, edit, or delete study cards.
- **Random quotes:** show a quote and author on launch; tap **New quote** for another.
- **Fitness tracker:** log steps and workouts, review daily totals and a weekly workout chart, and delete entries.

The flashcard deck and fitness records use local device storage through `shared_preferences`.

```sh
cd flutter-apps
flutter pub get
flutter run
```

## Browser versions

The original standalone prototypes are also available in the repository root:

- `flashcard-quiz-app.html`
- `random-quote-generator.html`
- `fitness-tracker-app.html`

A ZIP archive containing the complete Flutter source is available as `codealpha_flutter_source.zip`.

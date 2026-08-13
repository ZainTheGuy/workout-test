# CalmMove Android workout app

CalmMove is a clean, calming micro-workout app built with Expo and React Native. It includes onboarding, configurable notification windows, 20-minute minimum spacing, random workouts and durations, exercise video previews, stacked weekly charts, a daily completion ring, and read-only history.

## Test on an Android phone

1. Install **Expo Go** from Google Play.
2. On a computer, install Node.js 20 or newer.
3. In this project folder run `npm install`, then `npm start`.
4. Scan the displayed QR code using Expo Go (phone and computer should be on the same Wi-Fi).

## Get future updates without downloading another ZIP

Clone `ZainTheGuy/workout-test` once using GitHub Desktop. For future versions, open GitHub Desktop and select **Fetch origin**, then **Pull origin**. In the same local project folder, restart Expo with `npm start`.

## Verify

Run `npm run typecheck`.

## Play Store build

Install EAS CLI (`npm install -g eas-cli`), sign in with an Expo account, then run `eas build --platform android --profile production`. Before submission, replace the sample exercise-video URLs with owned/licensed bundled videos, add final icons/privacy policy, and complete Play Console data-safety answers.

Notifications are scheduled locally and profile/history data stays on the device in this MVP.

## Version 1.1 improvements

- Unified stacked bars with a seamless green/red split.
- Centred percentage inside the progress ring.
- Completed and Not completed results become permanently read-only.
- Future workout details remain hidden until their scheduled time.
- Full-screen workout presentation with a larger video.
- Vertically snapping, animated History cards with dates in chronological order.

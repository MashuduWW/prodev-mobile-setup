# Expo Go Setup Documentation

## Setup Process

1. **Install Expo CLI**
   ```bash
   npm install -g expo-cli

## Challenges Faced

Expo Go vs Expo Orbit confusion: At first, it wasn’t clear if Expo Orbit and Expo Go were the same.

- Solution: Expo Go is the correct app for testing projects. Expo Orbit is a companion/preview tool but not required for local testing.

Android Emulator Setup:

- Installing Android Studio and configuring the emulator took extra time.

Needed to ensure HAXM (Intel Emulator Accelerator) or Hyper-V was enabled for performance.

Avoiding phone dependency:

- Initially tried to avoid using a physical device, but setting up the emulator was more complex.

Decided to use both approaches — run with Expo Go on phone for quick testing, and use Android emulator for PC-based development.

Terminal Errors:

Example: Running npm run android without an emulator/device connected produced No Android connected errors.

- Start emulator from Android Studio before running npm run android.

Expo Credentials:

- At one point, the CLI prompted for Expo account login.

Solution: Either sign up on expo.dev
 or run locally without logging in (not required unless publishing builds).


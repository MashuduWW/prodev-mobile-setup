<<<<<<< HEAD
# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
=======
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

>>>>>>> 565f8de71a6dc7f51e84afe6a43bc450f4703553

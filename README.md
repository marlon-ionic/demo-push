# DEMO Push Notifications (Android Icon Issue)

Simple Project to test Push Notifications functionality. It's based on the Capacitor documentation for setting up [Push Notifications in Firebase](https://capacitorjs.com/docs/guides/push-notifications-firebase).

The project has an custom image specific for push notifications (please note: actual push icon is colored white);

![verified icon](/icons8-verified-badge-48.png)

There was a report that the icon does not render on Pixel devices.

## Installation

- Ensure that you have a [Firebase Message Project](https://capacitorjs.com/docs/guides/push-notifications-firebase#creating-a-project-for-your-app-on-firebase) [setup](https://capacitorjs.com/docs/guides/push-notifications-firebase#add-the-googleservice-infoplist-file-to-your-ios-app)
- For Android, download the `google-services.json` file to your local machine. Then move the file into your Capacitor Android project directory, specifically under `android/app/`.
- Install the project dependencies and run the project using:

```bash
npm i
```

## Running

To run the app on your emulator or device, a script is defined to run `ionic build`, `cap sync` & `cap run android`:

```bash
npm run android
```

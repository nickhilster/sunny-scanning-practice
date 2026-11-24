# Sunny Scanning Practice

A mobile-first, static web practice aid for carrying a therapist-taught left-to-right scanning strategy into short exercises.

> This is a practice and training aid. It does not diagnose or treat any condition and is not a substitute for assessment or therapy from a qualified clinician.

## Use

Open the deployed app at <https://sunny.teambotics.app/> or serve this directory locally:

```sh
python3 -m http.server 8080
```

Then open <http://localhost:8080> in a browser. No build step or backend is required. The service worker and web manifest support installation and caching after the first online load.

## Privacy

There is no account, tracker, analytics SDK, or third-party runtime dependency. Practice records and saved progress stay in the browser's local storage on the device. A summary is exported only when the user chooses to save one. Deleting records removes the app's local practice data.

## Results and safety

Practice and Probe results describe performance on this screen only. They are not medical results, and phone-screen results must not be compared with paper-test cut-offs. The app makes no treatment-efficacy claims. New or suddenly worse symptoms require urgent medical care, not more exercises.

## License

No license has been selected yet.

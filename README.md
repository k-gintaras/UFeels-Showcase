# UFeels - Emotion Tracking Android App

## Project Overview

**UFeels** is an Android application designed to help users track, categorize, and reflect on their emotions. By focusing on a privacy-first, offline approach, UFeels allows users to log and analyze their feelings without the need for registration or data sharing. The app offers a unique take on emotional tracking, providing options for custom emotion categorization and insightful data visualization.

> _"What is a feeling, and how should it be categorized?"_ - UFeels tackles this complex question by allowing users to define and track their emotions in a way that suits them, rather than following rigid psychological classifications.

[Available on Google Play](https://play.google.com/store/apps/details?id=com.ideatheimage.ufeels)

---

## Key Features

- **Emotion Tracking**: Users can log their emotions with timestamps, location (optional), and custom categories.
- **Data Visualization**: Emotions are visualized over time using charts and graphs, allowing users to identify patterns and triggers.
- **Custom Categorization System**: Users can define their own emotional categories, moving beyond traditional "positive" or "negative" labels.
- **Offline-First Design**: Data is stored locally, ensuring user privacy without requiring cloud storage or user accounts.
- **Monetization**: In-app purchases are available through the Google Billing API, allowing for a monetized, ad-free experience.

---

## How UFeels Works

UFeels was developed to address some of the challenges involved in emotional self-tracking:

1. **Defining Feelings**: The app encourages users to differentiate between mind-related emotions (e.g., joy, anger) and physical states (e.g., hunger, fatigue).
2. **Flexible Categorization**: UFeels doesn’t limit users to standard categorizations of emotions; instead, it allows for personal, subjective categorization.
3. **Enhanced Self-Reflection**: The app is designed to discourage default responses (like "I’m fine") that can make self-development data less meaningful.

![UFeels Process Diagram](https://github.com/k-gintaras/UFeels-Showcase/blob/master/Diagrams/UFeels-diagram.gdraw)

---

## Screenshots

![Main Screen - Free Mode](https://github.com/k-gintaras/UFeels-Showcase/blob/master/Screenshots/in-app-screenshots/main-free.jpg)
_Main screen showcasing free tracking mode._

![Random Emotion Selection Mode](https://github.com/k-gintaras/UFeels-Showcase/blob/master/Screenshots/in-app-screenshots/random-mode.jpg)
_Random mode for spontaneous emotion tracking._

![Advanced Settings - No Ads](https://github.com/k-gintaras/UFeels-Showcase/blob/master/Screenshots/in-app-screenshots/settings-noads.jpg)
_Settings screen, ad-free experience with premium features._

---

## Concept Insights and Research

The journey to create UFeels involved exploring various perspectives on emotions and how to categorize them. Here are some unique considerations that guided its development:

- **What Constitutes a "Feeling"?**: The app differentiates between emotions related to mental states (e.g., happiness, anger) and physical conditions (e.g., hunger, fatigue).
- **Categorization Flexibility**: Psychological interpretations often label emotions as positive or negative, but UFeels allows users to interpret their emotions subjectively.
- **Response Authenticity**: Common responses like "I’m fine" are minimized through the app’s design, encouraging genuine reflections for meaningful data.

For further reading on emotional categories and concepts:

- [Plutchik’s Wheel of Emotions](https://en.wikipedia.org/wiki/Contrasting_and_categorization_of_emotions#Plutchik.27s_wheel_of_emotions)
- [Vocabulary of Emotions](https://www.vocabulary.com/lists/535865)
- [PsychPage on Feelings](http://www.psychpage.com/learning/library/assess/feelings.html)

![Example Chart - Emotion Frequency](https://github.com/k-gintaras/UFeels-Showcase/blob/master/Diagrams/Stats-Diagrams.gdraw)

---

## Data Collection Methodology

UFeels allows users to collect data on:

- **Emotion Occurrences**: Timestamps for each emotion.
- **Location Data**: Optional location tracking to provide context for emotional patterns.
- **Reaction Time**: Measurement of response times, which can indicate the strength or intensity of an emotion.

Example data format:

```javascript
var feelingData = {
    "Happiness": {
        msSubmitted: [1469648412340,1469648411140],
        msReactionTime: [2989,2970],
        location: ["lastKnown;51.487395;0.008363;London:United Kingdom"],
        image: ["/storage/emulated/0/UFeels/UFeels1469644801704.jpg"]
    },
    ...
};
```

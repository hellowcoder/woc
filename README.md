# Codeforces Challenge Enhancer

## Overview

Codeforces Challenge Enhancer is a Chrome extension designed to elevate the competitive programming experience on the Codeforces platform. With features like virtual rooms, real-time challenges, progress tracking, and collaborative tools, this extension transforms problem-solving into a dynamic and interactive experience.

## Features

### 1. Virtual Rooms
- Create or join virtual rooms directly from the extension popup.
- Engage with friends or fellow programmers in real-time problem-solving challenges.

### 2. Challenge Button Integration
- Adds a "Challenge" button to each problem page on Codeforces.
- Share problem links with room participants for synchronized problem-solving.

### 3. Countdown Timer
- Displays a synchronized countdown timer on the problem page.
- Ensures all participants start the challenge simultaneously.

### 4. Real-Time Notifications
- Get notified when participants solve problems during challenges.
- See who solved it first and track progress live.

### 5. Challenge Completion Popup
- View detailed results at the end of the challenge.
- Includes participant rankings and options to start new challenges.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/codeforces-challenge-enhancer.git
   ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top-right corner.
4. Click **Load unpacked** and select the project directory.
5. The extension will be added to Chrome and accessible from the toolbar.

## Usage

1. Open Codeforces and navigate to the extension icon.
2. Create or join a virtual room through the popup interface.
3. Start a challenge by clicking the "Challenge" button on a problem page.
4. Solve the problem while tracking progress and updates in real time.
5. View results and continue with new challenges as desired.

## Project Structure

```
/codeforces-challenge-enhancer/
├── manifest.json
├── icons/
│   ├── icon16.png
│   ├── icon48.png
│   ├── icon128.png
├── popup.html
├── popup.js
├── background.js
├── content.js
├── styles.css
├── options.html
├── options.js
```

- **manifest.json**: Extension configuration.
- **popup.html**: Main UI for creating/joining rooms and starting challenges.
- **background.js**: Handles room synchronization and notifications.
- **content.js**: Injects features like the "Challenge" button and countdown timer into Codeforces pages.
- **styles.css**: Styling for the extension's UI.

## Technologies Used

- **HTML/CSS/JavaScript**: For building the user interface and extension logic.
- **Firebase**: For real-time room management and synchronization.
- **Codeforces API**: To fetch problem and submission data.
- **Chrome Extensions API**: For integrating the extension with the browser.

**Happy Coding!**

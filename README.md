# Event Website Features Documentation

## Overview
This project consists of multiple HTML tasks designed to enhance a community event website. The features include navigation, form handling, media elements, debugging techniques, and storage functionality.

## 1. Navigation and Linking
- **File:** `navigation.html`
- **Description:** Implements a `<nav>` menu with internal section links.
- **Key Features:**
  - Uses `<a>` tags for smooth scrolling.
  - Sections defined with matching `id` attributes.
  - External help document linked using `<a href="help.html" target="_blank">`.

## 2. Welcome Message with Styling
- **File:** `welcome.html`
- **Description:** Displays a uniquely styled welcome banner.
- **Key Features:**
  - Uses `<div id="welcomeBanner">` for styling.
  - Inline styles for special offer `<span>`.
  - `.highlight` class applied for emphasis.

## 3. Community Event Image Gallery
- **File:** `gallery.html`
- **Description:** Showcases images of past events in a table format.
- **Key Features:**
  - 2 rows × 3 columns of event images.
  - `<img>` tags with `alt`, `title`, and border styles.
  - `<caption>` used to describe the gallery.

## 4. Event Registration Form
- **File:** `registration.html`
- **Description:** Enables users to register for upcoming events.
- **Key Features:**
  - Inputs for name, email, date, event type, and message.
  - Uses `placeholder`, `required`, and `autofocus` attributes.
  - Displays a confirmation message using `<output>`.

## 5. Event Feedback Form with Event Handling
- **File:** `feedback.html`
- **Description:** Collects user feedback while handling various JavaScript events.
- **Key Features:**
  - `onblur` validation for phone numbers.
  - `onchange` displays selected event fees.
  - `onclick` confirmation message.
  - `ondblclick` enlarges images.
  - Key event tracking for character count in textarea.

## 6. Video Invite with Media Events
- **File:** `video_invite.html`
- **Description:** Embeds an event promo video.
- **Key Features:**
  - `<video>` tag with `controls` for user playback.
  - `oncanplay` displays "Video ready to play" message.
  - `onbeforeunload` warns users about unsaved form changes.

## 7. Saving User Preferences
- **File:** `preferences.html`
- **Description:** Stores and retrieves the user’s preferred event type.
- **Key Features:**
  - Saves selection using `localStorage`.
  - Pre-selects preference on page reload.
  - "Clear Preferences" button to reset storage.

## 8. Geolocation for Event Mapping
- **File:** `geolocation.html`
- **Description:** Helps users locate nearby events.
- **Key Features:**
  - "Find Nearby Events" button triggers `getCurrentPosition()`.
  - Displays user coordinates.
  - Handles permission denial and timeout errors.

## 9. Debugging with Chrome DevTools
- **File:** `debugging.html`
- **Description:** Demonstrates debugging techniques in DevTools.
- **Key Features:**
  - Uses `console.log()` for testing logs.
  - Creates intentional errors for `console.error()`.
  - Guide to using Inspect Element, Console, Network, and Breakpoints.

## Setup Instructions
1. Download all files into a single project folder.
2. Open the `.html` files in a browser to view functionality.
3. Modify `.css` and `.js` files as needed to customize features.
4. Use **Chrome DevTools (`F12`)** for live debugging.

## Notes
- Make sure images and video files (`event1.jpg`, `promo.mp4`, etc.) are in the same directory.
- Forms require JavaScript for dynamic behavior.
- LocalStorage-based features persist data across reloads.

## Contributors
- **Developer:** Your Name
- **Created On:** May 2025


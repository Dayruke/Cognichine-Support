# Retro Pixel Camera

## Overview
"Retro Pixel Camera" transforms your device's camera feed into a nostalgic pixel art style in real-time. Apply classic console and computer palettes, adjust the pixel resolution, and capture unique photos and videos with a retro aesthetic. Includes a built-in gallery and palette editor for customization.

## Installation

### Mobile (Android/iOS)
1.  Download "Retro Pixel Camera" from your device's app store (e.g., Google Play Store, Apple App Store - *Note: Availability may vary*).
2.  Install the app on your device.
3.  Open the app. You may be prompted to grant camera and storage permissions. These are necessary for the app to function.

## How to Use

### Main Interface (Camera View)
*   **Live Preview**: The central area shows the live camera feed processed with the selected retro effect.
*   **Top/Left Panel (Controls vary by orientation)**:
    *   **Palette Button**: Tap the palette icon or name to cycle through available color palettes. The current palette name is displayed next to the icon.
    *   **Edit Palette Button**: Tap the pencil icon to open the Palette Editor for the current palette.
    *   **Pixel Resolution Buttons**: Use the "Pixel +" and "Pixel -" buttons (or icons showing larger/smaller pixels) to increase or decrease the pixelation effect.
*   **Bottom/Right Panel (Controls vary by orientation)**:
    *   **Gallery Thumbnail**: Shows a preview of the latest saved photo or video. Tap it to open the Gallery. A "working" message appears during video processing.
    *   **Capture Button**:
        *   **Photo Mode**: Tap the camera icon to take a picture.
        *   **Video Mode**: Tap the video icon to start recording. Tap the recording icon again to stop. A timer shows elapsed recording time.
    *   **Mode Toggle Button**: Switches between Photo and Video capture modes.
    *   **Flip Camera Button**: Switches between the front and rear cameras.

### Capturing Photos
1.  Ensure the app is in Photo mode (toggle button shows a camera icon).
2.  Frame your shot using the live preview.
3.  Adjust palette and resolution as desired.
4.  Tap the central **Capture Button** (camera icon).
5.  The photo is saved automatically to the app's gallery folder.

### Capturing Videos
1.  Switch to Video mode using the **Mode Toggle Button** (it will show a video camera icon).
2.  Frame your shot. Adjust palette and resolution.
3.  Tap the central **Capture Button** (video icon) to start recording. A timer will appear.
4.  Tap the **Capture Button** (now a recording icon) again to stop recording.
5.  A "working" message may appear briefly on the gallery thumbnail while the video is processed and saved.
6.  Videos are saved automatically to the app's gallery folder.

### Editing Palettes
1.  Select the palette you wish to edit using the **Palette Button**.
2.  Tap the **Edit Palette Button** (pencil icon).
3.  The Palette Editor screen will appear.
4.  Tap a color swatch to change its color using a color picker.
5.  Modify the palette name if desired.
6.  Use the "SAVE" button to store changes or "RESET" to revert to default colors/name.
7.  Tap "EXIT" to return to the camera view. Changes are applied immediately.

### Using the Gallery
1.  Tap the **Gallery Thumbnail** on the main screen.
2.  **Navigate**: Swipe left or right to view different photos and videos.
3.  **Play Videos**: If a video is displayed, tap the play icon overlay to watch it. Tap again to pause.
4.  **Actions (Bottom/Right Panel)**:
    *   **Back**: Exit the gallery and return to the camera view.
    *   **Share**: Share the current photo or video using your device's standard sharing options.
    *   **Delete**: Permanently delete the current photo or video from your device.

## Features

*   **Real-time Pixel Shader**: Applies pixelation and palette effects directly to the live camera feed.
*   **Classic Palettes**: Includes built-in palettes inspired by NES, SNES, EGA, and Game Boy.
*   **Palette Editor**: Customize existing palettes or create your own. Modify colors and names, save changes, and reset to defaults.
*   **Adjustable Resolution**: Control the size of the "pixels" for different levels of abstraction.
*   **Photo & Video Capture**: Save your retro creations as still images (.png) or videos (.mp4).
*   **Built-in Gallery**: Browse, view, play, share, and delete your captured photos and videos within the app.
*   **Front/Back Camera Support**: Easily switch between cameras.
*   **Orientation Support**: The user interface adapts for both portrait and landscape use.
*   **Persistent Custom Palettes**: Your palette edits are saved for future use.

## Support
You can use the [Issues](https://github.com/Dayruke/Cognichine-Support/issues) tab on GitHub to search for existing questions or make suggestions.

For additional support, visit our main [Cognichine Support README](https://github.com/Dayruke/Cognichine-Support).

## FAQ

**What's the purpose of this app?**
Retro Pixel Camera lets you see the world through a retro lens, applying pixel art styles and limited color palettes to your camera in real-time for capturing unique photos and videos.

**How do the palettes work?**
The app maps the colors from the camera feed to the closest colors available in the currently selected 16-color palette. You can cycle through built-in palettes or edit them.

**How does the resolution adjustment work?**
It changes the size of the virtual "pixels" the image is broken down into before the palette is applied. Lower resolution means larger, chunkier pixels; higher resolution means smaller, more detailed pixels.

**Where are the photos and videos saved?**
*   **Android**: They are typically saved in a dedicated folder within your device's main picture directory: `DCIM/RetroPixelCamera/`.
*   **iOS**: They are saved within the app's documents directory, accessible via the Files app or iTunes File Sharing.

**Is there a time limit for video recording?**
Yes, by default, there is a 5-minute (300 seconds) time limit for video recordings to manage file size and processing.

**What does the "working" message mean after recording a video?**
After stopping a recording, the app needs a moment to process and save the video file correctly to the gallery folder. The gallery thumbnail will update once it's ready.

**Can I edit the built-in palettes like NES or GB?**
Yes, you can select any palette and use the Edit Palette button to modify its colors and name. Your changes will be saved.

**How can I reset a palette to its original colors?**
In the Palette Editor, use the "RESET" button to restore the currently selected palette to its default name and colors.

**Does the app work offline?**
Yes, all core camera, effects, capture, and gallery features work entirely offline after the app is installed and necessary permissions are granted. Sharing requires an internet connection.
# HTML Elements Group Assignment - Music Theme

This repository contains the implementation for **Part 1 (Structure Lead)** and **Part 2 (Media Lead)** of the HTML Elements Group Activity. The project follows a cohesive **Music Theme**, demonstrating various HTML5 capabilities.

## 🎵 Project Overview
*   **Theme:** Music (Orchestras, Genres, Composition)
*   **Author:** Karabo-jpg (k.ojiambo@alustudent.com)

## 📂 Implementation Details

### Part 1: Structure Lead (`block-inline.html`)
Demonstrates the difference between block and inline elements using visual borders and music-related content.
*   **Block Elements:**
    *   `<div>`: Represents the "Symphony Orchestra" (full width, purple border).
    *   `<section>`: Represents "Music Genres" (full width, orange border).
    *   Both elements demonstrate how block-level items take up the full available width and start on new lines.
*   **Inline Elements:**
    *   `<strong>`: Used for emphasizing key terms like "music composition".
    *   `<span>`: Used for highlighting text with a yellow background.
    *   Demonstrates how inline elements flow within the text content without breaking lines.

### Part 2: Media Lead (`media.html`)
Showcases HTML5 multimedia elements with local files and accessibility features.
*   **Audio Player:**
    *   Plays specific track: **Elevation Worship So Be IT**.
    *   Uses `<audio controls>` for native browser playback (seek/volume/pause).
    *   Source: `audio/elevation-worship.mp3`
*   **Video Player:**
    *   Plays short film: **Forest Bunny** (Big Buck Bunny).
    *   Uses `<video controls width="320">`.
    *   Source: `video/forest-bunny.mp4` (Stored locally).
*   **Accessibility (Captions):**
    *   Includes a `<track>` element for WebVTT captions.
    *   File: `captions/music-captions.vtt`.
    *   Features custom "lyrics" and descriptive audio cues ("♪ A bunny wakes with morning pride ♪") synced to the video.

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone https://github.com/Karabo-jpg/HTML-Elements.git
    ```
2.  Open the folder in **VS Code**.
3.  Right-click `block-inline.html` or `media.html` and select **"Open with Live Server"** (or just open the file in your browser).
    *   *Note: For captions to load correctly in some browsers (like Chrome), running through a local server is recommended due to security restrictions on local files.*

## 📁 File Structure
```
/
├── block-inline.html       # Part 1: Structure Demo
├── media.html              # Part 2: Media Player
├── audio/
│   └── elevation-worship.mp3
├── video/
│   └── forest-bunny.mp4
└── captions/
    └── music-captions.vtt
```

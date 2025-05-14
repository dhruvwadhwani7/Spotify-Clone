# Spotify Clone

A web-based Spotify clone that allows users to browse playlists, play songs, and control playback. This project is built using HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: The layout adjusts for desktop and mobile devices.
- **Playlist Display**: Dynamically fetches and displays playlists from the `songs` directory.
- **Music Playback**: Play, pause, skip, and adjust volume for songs.
- **Seekbar**: Allows users to seek through the currently playing song.
- **Volume Control**: Includes a mute/unmute toggle and volume slider.
- **Mobile Navigation**: Hamburger menu for mobile devices.

## Project Structure

### Key Files

- **[index.html](index.html)**: The main HTML file for the project.
- **[css/style.css](css/style.css)**: Contains the primary styles for the project.
- **[css/utility.css](css/utility.css)**: Utility classes for common styling.
- **[js/script.js](js/script.js)**: JavaScript logic for fetching playlists, handling playback, and UI interactions.
- **`songs/`**: Contains playlists, each with a `cover.jpg` and `info.json` file for metadata.

## How to Run

1. Clone the repository or download the project files.
2. Open the `index.html` file in a web browser.
3. Ensure the project is hosted on a server (e.g., using a local server like `Live Server` in VS Code) to enable fetching of playlist data.

## Dependencies

- **Google Fonts**: The project uses the `Roboto` and `Lato` fonts.
- **Modern Browsers**: Ensure you use a modern browser that supports ES6 and CSS3.

## Screenshots

### Desktop View
![Desktop View](img/cover.jpg)

### Mobile View
![Mobile View](img/hamburger.svg)

## Future Enhancements

- Add user authentication for personalized playlists.
- Integrate a backend for storing user data and playlists.
- Support for more audio formats and streaming.

## License

This project is for educational purposes only and is not affiliated with Spotify.

---

### Author

**Dhruv Wadhwani**

Feel free to contribute or suggest improvements!
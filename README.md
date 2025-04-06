# Message Map

Message Map is a simple web application that allows users to post messages tied to their current location. 
These messages are then displayed on a map, making it easy to see what people are saying around you.

## Features

* **Post Messages:** Share your thoughts and location with others.
* **View Messages on a Map:** See messages posted by other users on an interactive map.
* **Search Functionality:** Easily find messages by name or content.
* **Interactive Message Actions:** Like, comment, and share messages.
* **Edit and Delete Messages:** Manage your own messages.
* **Message View Count:** See how many times your message has been viewed.
* **Progressive Web App (PWA):** Install the app for an enhanced experience.

## Installation

1.  Clone the repository:

    ```bash
    git clone [repository URL]
    ```

2.  Navigate to the project directory:

    ```bash
    cd message-map
    ```

3.  Open `index.html` in your web browser.

## Usage

1.  Enter your name and message in the provided fields.
2.  Click the "Post Message" button to add your message to the map.
3.  Use the search bar to filter messages.
4.  Click on markers on the map to view message details and interactions.
5.  Use the bottom navigation to switch between different app sections.

## PWA Installation

To install Message Map as a Progressive Web App (PWA):

1.  Open the app in a supported browser (Chrome, Edge, Safari).
2.  Look for the "Install" button or prompt.
3.  Click the "Install" button to add the app to your home screen or app launcher.

## Technologies Used

* HTML
* CSS
* JavaScript
* Leaflet.js (for map functionality)
* Progressive Web App (PWA) features

## Manifest

The `manifest.json` file contains the necessary information for the PWA:

```json
{
  "name": "Message Map",
  "short_name": "MessageMap",
  "start_url": ".",
  "display": "standalone",
  "background_color": "#ffffff",
  "theme_color": "#008CBA",
  "icons": [
    {
      "src": "icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "icon-512x512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
```
## Service Worker1
The `service-worker.js` file handles caching and offline functionality.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License
Apache License
Version 2.0, January 2004

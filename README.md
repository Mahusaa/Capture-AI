# Capture AI

**Capture AI** is a Chrome extension that allows users to snip (screenshot) portions of a webpage and submit it to an AI for analysis. Whether you're capturing text, images, or web elements, this tool simplifies the process of gathering information from webpages and querying an AI for more insights.

## Features

- **Snip/Screenshot**: Easily capture parts of a webpage.
- **AI Integration**: Automatically send captured content to an AI for analysis.
- **Real-time Results**: Receive quick responses and insights from the AI.
  
## Technology Stack

- **jQuery**: Used for DOM manipulation and event handling.
- **Vanilla JavaScript**: Core functionality of the extension.
- **Tesseract.js**: For optical character recognition (OCR) to extract text from images.
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Capture-AI.git
   ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the extension directory.

## How to Use

1. Once installed, click the **Capture AI** icon in your Chrome toolbar.
2. Select the area of the webpage you wish to snip.
3. The extension will capture the selected area and send the image to the integrated AI.
4. View the AI's response in the extension's output window.

## Key Libraries

- **jQuery**: Simplifies JavaScript tasks such as DOM manipulation and event handling.
- **Vanilla JS**: Lightweight and fast, used for core logic.
- **Tesseract.js**: Converts the image-based screenshot into text using OCR.

## Development

### Prerequisites

Ensure that you have the following installed:

- **Node.js**: For managing dependencies and building the project.
- **Tesseract.js**: This library is included via a CDN in the `index.html`.

### Running Locally

1. Clone the repository and navigate into the project folder.
2. Load the extension in Chrome (follow installation steps).
3. Make changes to the code and reload the extension to see updates.

## Contributions

Feel free to fork the repository, create a new branch, and make pull requests for any new features or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

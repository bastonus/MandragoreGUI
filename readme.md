Below is an updated README that explains the project as a graphical client for the Mandragore digital resources provided by the Bibliothèque nationale de France:

---

# MandragoreGUI

**A Graphical Client for Mandragore Digital Resources**  
*(A user-friendly interface to browse, zoom, and download high-resolution images hosted by [Mandragore](https://mandragore.bnf.fr/) at the Bibliothèque nationale de France.)* citeturn2fetch0

## Overview

MandragoreGUI is a lightweight, static web application built using HTML, CSS, and JavaScript. It serves as a dedicated client for the [Mandragore](https://mandragore.bnf.fr/) digital repository provided by the Bibliothèque nationale de France (BnF). Using this interface, users can enter a book reference (with the default being `12148/btv1b52506706r`), navigate through pages, zoom and pan high-resolution images, and download them with ease. The application leverages the IIIF endpoint available on the Mandragore site to retrieve resources, making it a handy tool for researchers, historians, and digital humanities enthusiasts. citeturn0fetch0

## Features

- **Book Loading:**  
  Enter a book reference (e.g., `12148/btv1b52506706r`) to load its associated digital resource from Mandragore.

- **Seamless Navigation:**  
  Browse through pages with **Précédent** (Previous) and **Suivant** (Next) buttons or jump directly to a desired page using the input field.

- **Dual & Single Page Display:**  
  Automatically switches between dual-page spreads and single-page mode when viewing the cover or final pages.

- **Zoom & Pan:**  
  Easily adjust the zoom level with intuitive sliders. When zoomed in, click and drag (or use touch gestures) to pan across the image. A reset button is provided to quickly return to the default view.

- **Download Images:**  
  Download high-resolution page images using the provided download buttons. *(Note: Although files are labeled with a `.highres` extension, they are standard JPEG images. You may rename them after downloading.)*

- **Theme Toggle:**  
  Switch between light and dark modes manually; the application also auto-detects your system's color scheme for a tailored viewing experience.

## Live Demo

Experience MandragoreGUI in action on GitHub Pages:  
[MandragoreGUI Demo](https://bastonus.github.io/MandragoreGUI/) citeturn0fetch0

## Installation

Since MandragoreGUI is a static site, you can run it locally or host it on any static file server.

### Running Locally

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bastonus/MandragoreGUI.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd MandragoreGUI
   ```

3. **Open the Application:**

   - **Directly:** Open the `index.html` file in your web browser.
   - **Using a Local Server:** For example, using Python’s built-in server:
     ```bash
     python -m http.server
     ```
     Then navigate to `http://localhost:8000` in your browser.

## Usage

1. **Load a Book:**
   - Enter a valid Mandragore book reference (the default is `12148/btv1b52506706r`) in the input field.
   - Click the **Charger** button to load the digital resource from [Mandragore](https://mandragore.bnf.fr/).

2. **Navigate Through Pages:**
   - Use the **Précédent** and **Suivant** buttons to move between pages.
   - Alternatively, input a page number directly and press Enter to jump to that page.

3. **Zoom and Pan:**
   - Adjust the zoom level with the slider beneath each page image.
   - Click on the image to toggle between standard and zoomed views.
   - When zoomed, drag the image (or use touch gestures) to pan. Use the **Réinitialiser** button to reset the view.

4. **Download Images:**
   - Click the **Télécharger l'image** button on either the left or right page to download the image.
   - Remember: Despite the `.highres` file extension, the downloaded file is a JPEG image.

5. **Toggle Theme:**
   - Use the **Thème sombre** button to switch between light and dark modes. The theme also auto-adjusts based on your system’s settings.

## About Mandragore

Mandragore is the digital repository hosted by the Bibliothèque nationale de France, offering access to high-resolution scans of books and manuscripts. This project provides a dedicated GUI client to interact with Mandragore’s IIIF-based resources, making it easier to download and work with the materials.

## Contributing

Contributions and suggestions are welcome! If you encounter any issues or have ideas for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/bastonus/MandragoreGUI). citeturn2fetch0

## License

This project currently does not include a license. For details regarding reuse or distribution, please contact the repository owner.

## Contact

For questions, feedback, or contributions, please reach out via GitHub issues on the [MandragoreGUI repository](https://github.com/bastonus/MandragoreGUI). citeturn2fetch0

---

*Created by [bastonus](https://github.com/bastonus).* 
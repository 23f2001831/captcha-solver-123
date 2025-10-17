# CAPTCHA Solver Application

This is a simple, single-file web application designed to demonstrate a user interface for solving CAPTCHAs. The application is built with pure HTML, Tailwind CSS for styling, and vanilla JavaScript for interactivity. It allows users to load CAPTCHA images and input their perceived solution.

## Features

*   **Responsive Design:** Optimized for various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading:** Loads a default CAPTCHA image (`sample.png`) or a custom image specified via a URL parameter.
*   **User Input and Validation:** Provides an input field for users to type their CAPTCHA solution and offers instant feedback.
*   **Minimalistic UI:** Clean and straightforward interface for a focused user experience.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Default CAPTCHA:** By default, the application will display `sample.png`. For this image, the hardcoded solution is "ADURB".
3.  **Custom CAPTCHA (URL Parameter):** To load a different CAPTCHA image, append a `?url=` query parameter to your browser's address bar, followed by the URL of your desired image.
    *   **Example:** `index.html?url=https://example.com/path/to/your/image.png`
    *   **Note:** When using a custom URL, the application will still check against the hardcoded solution "ADURB" for demonstration purposes. In a real-world scenario, a robust CAPTCHA solver would involve OCR (Optical Character Recognition) or an API integration to verify custom images. This app primarily showcases the front-end interaction.

### Example Interaction

1.  Open `index.html`.
2.  Observe the "ADURB" image.
3.  Type "ADURB" into the input field.
4.  Click "Submit".
5.  Receive "Correct!" feedback.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** Utility-first CSS framework for responsive and modern styling.
*   **JavaScript:** Client-side scripting for image loading, form handling, and validation.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
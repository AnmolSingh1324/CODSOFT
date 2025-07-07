Image Captioning AI - Discord Style

This is a modern web application for generating concise captions for images using the power. The user interface is inspired by Discord's sleek and intuitive design, providing a seamless experience for uploading images and getting instant descriptions.
Features

    Image Upload: Easily upload images via a file input or drag-and-drop functionality.

    Live Preview: See a preview of your selected image before generating a caption.

    AI-Powered Captioning: Utilizes the Gemini API for advanced image understanding and caption generation.

    Responsive Design: Optimized for a smooth experience across various devices (desktop, tablet, mobile).

    Discord-Inspired UI: A visually appealing interface with a dark theme, subtle gradients, and modern button styles.

    Loading Indicator: Provides visual feedback while the AI is generating a caption.

    Custom Message Box: User-friendly alerts for errors or important information.

    Keyboard Shortcuts:

        Ctrl + U (or Cmd + U on Mac): Upload image.

        Ctrl + Enter (or Cmd + Enter on Mac): Generate caption.

        Escape: Clear the current image.

Technologies Used

    HTML5: Structure of the web application.

    CSS3: Custom styling to achieve the Discord-like aesthetic, including gradients, shadows, and responsive adjustments.

    Tailwind CSS: A utility-first CSS framework for rapid UI development and responsive design.

    JavaScript (ES6+): Powers the application's logic, UI interactions, and API calls.

    TensorFlow.js (CDN): Included in the project, suggesting potential for client-side machine learning models in the future, though currently the Gemini API handles the core captioning.

How to Use

    Open the Application: Open the IMAGE CAPTIONING.html file in your web browser.

    Upload an Image:

        Click the "📸 Upload Image for Advanced Analysis" button.

        Alternatively, drag and drop an image file directly into the "Supports JPG, PNG, GIF • Maximum accuracy with high-resolution images" section.

    Preview: The selected image will appear in the "Image Preview" area.

    Generate Caption: Click the "Generate Caption" button. A loading spinner will appear while the AI processes the image.

    View Caption: Once generated, the caption will be displayed under "Generated Caption:".

    Clear Image: Click the "Clear Image" button to remove the current image and reset the application.

Project Structure

The project is a single HTML file (IMAGE CAPTIONING.html) containing all the HTML, CSS, and JavaScript.

    <head>: Contains meta information, title, TensorFlow.js and Tailwind CSS CDN links, and Google Fonts import.

    <style>: Custom CSS rules for the Discord-like theme and responsive adjustments.

    <body>:

        Main container for the application UI.

        Image upload section with drag-and-drop support.

        Image preview area.

        Control buttons (Generate Caption, Clear Image).

        Loading indicator.

        Output area for the generated caption.

        Custom message box for alerts.

        Footer with project information.


Development Notes

    The application uses FileReader to convert uploaded images to Base64.

    Error handling is implemented for API calls and invalid file types, displaying user-friendly messages.

    The apiKey for the Gemini API is currently hardcoded as an empty string, assuming it will be provided by the Canvas environment at runtime. If running outside this environment, you would need to insert your actual API key.

    Performance monitoring features (FPS, memory usage) were present in the original code but have been removed in the current version.

Developed with ❤️ by ANMOL SINGH
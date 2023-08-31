# QR-code


## QR Code Generator

This web page serves as a QR Code Generator, allowing users to create QR codes for text or URLs. It provides a user-friendly interface for generating QR codes, and it also features a visual design with animated shapes for added visual appeal.

# Features

1. **QR Code Generation:** Users can input text or URLs in the provided text input field and click the "Generate QR Code" button to generate a QR code corresponding to the entered content.

2. **Dynamic QR Code Display:** The generated QR code is displayed dynamically on the page using the "qr-code" `<div>` element. The QR code updates every time the user clicks the "Generate QR Code" button with new content.

3. **Download QR Code:** Once the QR code is generated, a "Download QR Code" button becomes visible. Users can click this button to download the QR code as a PNG image file.

4. **Visual Animations:** The page is visually enhanced with animated shapes that add an attractive visual element to the QR code generator.

# HTML Structure

1. `<head>` Section: Contains metadata and stylesheets for the webpage, including title, character encoding, viewport settings, and inline styles for animations and shapes.

2. `<body>` Section:
   - `<div id="container">`: This div contains the main content of the page, including the QR code generator interface and the animated shapes.
     - `<h1>`: The page title, "QR Code Generator."
     - `<input>`: A text input field where users can enter text or URLs.
     - `<button>`: The "Generate QR Code" button to trigger the QR code generation process.
     - `<div id="qr-code">`: The container for displaying the generated QR code.
     - `<a id="download-link" download="qrcode.png">`: An anchor element wrapped around the "Download QR Code" button to enable downloading the QR code as an image.
     - `<button id="download-button">`: The button for downloading the generated QR code.
   - Animated Shapes: Several `<div>` elements with classes for different animated shapes such as stars, circles, squares, triangles, diamonds, and crosses. These shapes are positioned using inline `style` attributes to distribute them across the page.

3. `<script>` Section:
   - External Script: Includes the QR code generation script sourced from the provided CDN link.
   - Inline Script: Listens for the "Generate QR Code" button click event and triggers the generation of the QR code. It also handles the dynamic update of the QR code display and the enabling of the download feature.

### Usage

1. Enter the desired text or URL in the input field.
2. Click the "Generate QR Code" button.
3. The QR code will be displayed in the designated area.
4. The "Download QR Code" button will become visible. Click it to download the generated QR code as a PNG image.

### Customization

- To customize the animations, colors, shapes, and positions of the animated elements, modify the corresponding CSS rules in the `<style>` section.
- To modify the QR code generator behavior, refer to the inline script inside the `<script>` section.

---


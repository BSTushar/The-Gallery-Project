# The-Gallery-Project

# My Gallery

A simple, responsive image gallery built with HTML and CSS, designed to display images in a card-style layout with hover effects. This project is intended to showcase a collection of images in a visually appealing and interactive manner.

## Features

- **Responsive Layout**: The gallery is responsive and adjusts to various screen sizes.
- **Image Hover Effects**: Each image card has a grayscale effect that transitions to full color on hover. Additionally, captions are displayed on hover.
- **Box Shadows and Transitions**: Subtle shadows and smooth transitions are applied to create a modern and interactive feel.

## File Structure

```
My Gallery/
├── index.html         # Main HTML file
├── style.css          # Stylesheet for the gallery layout and styling
└── images/
    ├── image1.jpg
    ├── image2.jpeg
    ├── image3.jpeg
    ├── image4.jpeg
    ├── image5.jpeg
    ├── image6.jpeg
    ├── image7.jpeg
    ├── image8.jpeg
    └── image9.jpeg
```

## Usage

1. Clone the repository or download the files.
2. Open `index.html` in your web browser.
3. View the gallery with the images provided or replace with your own images by placing them in the `images/` directory and updating the `src` attribute in the HTML.

## Customization

- **Add/Remove Images**: Add or remove images by modifying the `<figure class="card">` elements in `index.html`.
- **Change Hover Effects**: Modify hover effects by editing the CSS in `style.css`, specifically under the `.card:hover` and `.card:hover img` sections.
- **Adjust Layout**: Customize the gallery's appearance by changing the `.container` and `.gallery` flex properties to suit different layouts.

## License

This project is open-source and available under the MIT License.


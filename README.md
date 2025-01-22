
# Dummy Image Generator

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A **fast**, **free**, and **easy-to-use** image placeholder service! Whether you're a developer, designer, or content creator, this tool allows you to generate placeholder images with customizable dimensions, text, colors, and more.

---

## Features

- **Custom Dimensions**: Set image height and width.
- **Dynamic Text**: Add text to the image.
- **Font Styles**: Choose from multiple font options.
- **Color Customization**: Select background and text colors.
- **Background Images**: Use a URL or choose from pre-defined templates.
- **Image Types**: Supports PNG, JPEG, WEBP, GIF, and BMP formats.
- **Text Positioning**: Flexible options for text alignment within the image.
- **Responsive Design**: Works seamlessly across all devices.

---

## Demo

<div align="center">
  <!-- Place for Demo GIF or Screenshot -->
  <img src="https://www.dummyimg.in/placeholder" alt="Demo GIF or Screenshot" />
</div>

---

## How to Use

1. **Set the Dimensions**  
   Specify `Height` and `Width` in pixels (minimum value: 10).
   
2. **Customize Your Image**  
   - Add custom `Text`.
   - Select a `Font Style` from the dropdown.
   - Choose `Background Color` and `Text Color`.
   - Upload a `Background Image` or select one from templates.

3. **Generate and Copy the URL**  
   - Click **Generate Image** to preview.
   - Use the provided **Generated URL** to embed the image.

4. **Download**  
   - Click **Download Image** to save locally.

---

## Fields

The following fields are available for customization:

| Field Name           | Type        | Description                                         | Example Value                          |
|----------------------|-------------|-----------------------------------------------------|----------------------------------------|
| `height`             | Number      | Image height in pixels                             | `200`                                  |
| `width`              | Number      | Image width in pixels                              | `300`                                  |
| `text`               | String      | Text to display on the image                       | `Hello World`                          |
| `font_style`         | Dropdown    | Font type for the text                             | `Arial UNI`, `Comic`, `Disko`, etc.    |
| `bg_color`           | Color Picker | Background color in HEX format                     | `#d3d3d3`                              |
| `text_color`         | Color Picker | Text color in HEX format                           | `#FFFFFF`                              |
| `bg_image_url`       | URL         | URL of a background image                          | `https://example.com/bg.png`           |
| `font_size`          | Number      | Font size for the text in pixels                   | `16`                                   |
| `image_type`         | Dropdown    | Format of the generated image                      | `PNG`, `JPEG`, `WEBP`, etc.            |
| `text_position`      | Dropdown    | Alignment of text within the image                 | `center`, `top-left`, `bottom-right`   |



## Example URLs

### Generate a Placeholder Image
```url
https://www.dummyimg.in/placeholder?width=600&height=400
```

### Add Custom Text
```url
https://www.dummyimg.in/placeholder?text=Hello%20World
```

### Set Background and Text Colors
```url
https://www.dummyimg.in/placeholder?bg_color=%23FF0000&text_color=%23FFFFFF
```

### Use a Background Image
```url
https://www.dummyimg.in/placeholder?bg_image_url=https://example.com/bg.png
```

---

## Notes

1. **Minimum Values**: Height and width must be at least 10 pixels.
2. **Default Dimensions**: If no dimensions are specified, the image defaults to 300x200.
3. **Background Image Compatibility**: Ensure the image format matches the selected type.
4. **Empty Text**: Leave the text field with a space to exclude text.

---

## Installation

No installation is required! Just visit [dummyimg.in](https://www.dummyimg.in) to start generating images.

---

## Screenshots

### Example Generated Image
<div align="center">
  <!-- Add screenshot or placeholder example -->
  <img src="https://www.dummyimg.in/placeholder" alt="Example Placeholder Image" />
</div>

### Interface Preview
<div align="center">
  <!-- Add screenshot of the user interface -->
  <img src="./home page image.png" alt="User Interface Screenshot" />
</div>

---

## Support

For any issues or feedback, open an [issue](https://github.com/shubham0809200/dummyimg.in/issues) 

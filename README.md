# Image Color Changer - Rust

Welcome to the Image Color Changer project written in Rust! This application allows you to change the colors of an image, providing a simple yet powerful tool for color manipulation.

## Overview

Image Color Changer is a Rust-based command-line tool designed to modify the colors of an image. Whether you want to apply a global color shift, convert to grayscale, or perform more advanced color transformations, this tool has you covered.

## Features

- **Color Shifting:** Change the overall color tone of the image.
- **Grayscale Conversion:** Convert the image to grayscale for a classic look.
- **Customizable Parameters:** Adjust parameters to fine-tune the color transformation.
- **Efficient Processing:** Built with Rust for performance and speed.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/image-color-changer-rust.git
   ```

2. Navigate to the project directory:

   ```bash
   cd image-color-changer-rust
   ```

3. Build the project:

   ```bash
   cargo build --release
   ```

4. Run the application with your desired image and color transformation options:

   ```bash
   ./target/release/image-color-changer input_image.jpg --shift-hue 30
   ```

   Replace `input_image.jpg` with the path to your image file and adjust the transformation options as needed.

5. Explore the newly generated image with the applied color changes.

## Usage

The basic usage of the Image Color Changer is as follows:

```bash
image-color-changer <INPUT_IMAGE> [OPTIONS]
```

For example, to shift the hue of an image:

```bash
image-color-changer input_image.jpg --shift-hue 30
```

For more information on available options and their usage, refer to the help command:

```bash
image-color-changer --help
```

## Contributing

If you'd like to contribute to the development of the Image Color Changer, feel free to fork the repository and submit pull requests. Your contributions are highly appreciated!

## License

This project is licensed under the [MIT License](LICENSE).

Enjoy transforming your images with Rust! 🌈

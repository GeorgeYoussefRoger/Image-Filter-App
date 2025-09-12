# Image-Filters

A console-based C++ app for applying a wide variety of image processing filters. This app supports loading, editing and saving images in multiple formats. Demonstrating core image processing techniques.

## Features

It offers a rich set of 18 image filters and transformations:

- **Basic Adjustments**: Grayscale, Black & White, Invert, Brightness, Resize, Crop
- **Color Effects**: Sunlight, Purple, Infrared
- **Transformations**: Flip, Rotate, Skew
- **Enhancements**: Blur, Oil Painting, TV Effect
- **Editing**: Frame (Simple/Decorated), Merge Images, Edge Detection

Image Formats Supported: `.jpg`, `.jpeg`, `.png`, `.bmp`, `.tga`

## Prerequisites

- Ensure that `Image_Class.h` , `stb_image.h` and `stb_image_write.h` are present in the same directory or properly linked.

## Deployment

1. Clone this repository:
   ```
   git clone https://github.com/GeorgeYoussefRoger/Image-Filter-App.git
   ```
   ```
   cd Image-Filter-App
   ```
2. Build the app
   ```
   g++ -std=c++17 main.cpp -o ImageFilter
   ```
3. Run the app
   ```
   ImageFilter.exe
   ```

## Acknowledgment

This project was built using a custom image handling library provided by:

> **Dr. Mohamed El Ramly**  
> Faculty of Computers and Artificial Intelligence  
> Cairo University

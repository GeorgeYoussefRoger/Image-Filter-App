# 🖼️ Image-Filter-App
A console-based C++ application for applying a variety of image processing filters and transformations. In this project, I implemented the entire application logic and user interface in `main.cpp`, utilizing a pre-provided image processing library for image loading, saving, and pixel manipulation.

## 🚀 Features
- The application provides 18 image filters and transformations, grouped as follows:
  - **Basic Adjustments**: Grayscale, Black & White, Invert, Brightness, Resize, Crop
  - **Color Effects**: Sunlight, Purple, Infrared
  - **Transformations**: Flip, Rotate, Skew
  - **Enhancements**: Blur, Oil Painting, TV Effect
  - **Editing**: Add Frame (Simple/Decorated), Merge Images, Edge Detection
- Supported Image Formats: `.jpg`, `.jpeg`, `.png`, `.bmp`, `.tga`

## 📂 Project Structure
```
Image-Filter-App/
├── src/
│   ├── Image_Class.h        # Image class for pixel manipulation and processing
│   ├── stb_image.h          # Image loading library
│   ├── stb_image_write.h    # Image saving library
│   └── main.cpp             # Application logic and user interface (Implemented by me)
├── README.md
├── .gitignore
└── LICENSE
```

## 🧰 Technologies Used
- Language: C++ (Standard 17/20 recommended)
- Concepts: OOP, File I/O, Pointers, Sobel edge detection, Error Handling & Input Validation

## 📦 Installation & Usage
1. Clone the repository

```
git clone https://github.com/GeorgeYoussefRoger/Image-Filter-App.git
cd Image-Filter-App
```

2. Build the application

```
g++ -std=c++17 src/main.cpp -o FilterApp
```

3. Run the program

```
./FilterApp
```

## 🙏 Acknowledgment
The image processing libraries (`Image_Class.h` `stb_image.h` `stb_image_write.h`) were provided by:

> **Dr. Mohamed El Ramly**  
> Faculty of Computers and Artificial Intelligence  
> Cairo University

## 📜 License
- This project is licensed under the MIT License.
- See the `LICENSE` file for details.
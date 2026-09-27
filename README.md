# 🔐 Image Steganography

## 📌 Description

Image Steganography is a **C-based application** that hides secret data inside an image file and later extracts the hidden data from the encoded image.

The project demonstrates how data can be embedded into image data while maintaining the visual appearance of the image.

## 🚀 Features

* Encode secret data into an image
* Decode hidden data from an encoded image
* Hide data inside BMP image files
* Preserve the image structure while embedding data
* Validate input files and encoding information
* Extract the hidden data from the encoded image

## 🛠️ Technologies Used

* **Language:** C
* **Platform:** Linux
* **Compiler:** GCC
* **File Format:** BMP
* **Concepts:** File Handling, Bit Manipulation, Binary Data Processing

## 🧠 Concepts Demonstrated

* Pointers
* Structures
* File Handling
* Binary File Operations
* Bit Manipulation
* Command Line Arguments
* String Handling
* Dynamic Memory
* Modular Programming

## 🔄 Working

### Encoding

The encoding process takes:

* Source image
* Secret data
* Secret file extension

The secret data is embedded into the source image to produce an encoded image.

### Decoding

The decoding process reads the encoded image and extracts the hidden information.

## ⚙️ How to Compile

```bash
gcc *.c
```

## ▶️ How to Run

### Encoding

```bash
./a.out -e source.bmp secret.txt output.bmp
```

### Decoding

```bash
./a.out -d output.bmp extracted.txt
```

> Use the exact command-line options supported by the project when running it.

## 🔑 Magic String

The project uses a **magic string** to identify and validate the encoded image during the decoding process.

## 📚 What I Learned

Through this project, I gained practical experience with:

* Reading and writing binary files
* Manipulating data at the bit level
* Working with BMP image files
* Passing command-line arguments
* Implementing encoding and decoding logic
* Handling file pointers and binary data
* Organizing a C project into multiple modules

## 🎯 Key Skills

**C Programming • File Handling • Bit Manipulation • Binary Data • Pointers • Command Line Arguments • Encoding & Decoding**

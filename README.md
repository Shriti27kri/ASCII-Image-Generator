Image to ASCII Art Converter (Python)
 Project Overview

This project demonstrates how to convert a digital image into ASCII art using Python. Instead of displaying an image with pixels, the program represents the image using text characters, where darker pixels are mapped to dense characters and lighter pixels to sparse characters.

This project helps in understanding image processing basics, loops, and logical mapping in Python.

 Objectives

To load and process an image using Python

To convert an image into grayscale

To map pixel intensity values to ASCII characters

To generate a text-based (ASCII) representation of an image

Concepts Used

Python loops (for loop)

String manipulation

Image resizing and grayscale conversion

Pixel-to-character mapping

🛠️ Library Used

Pillow (PIL) – for image loading and processing

Install Pillow using:

pip install pillow
How the Code Works (Step-by-Step)

The image is loaded using Image.open()

The image is resized to maintain clarity and aspect ratio

The image is converted into grayscale (0–255 pixel values)

Each pixel value is mapped to a character from a predefined ASCII set

Characters are arranged line-by-line to form the ASCII image

The final ASCII art is printed in the console

Notes

Output quality depends on image resolution and contrast

This code is meant for learning and reference purposes

ASCII art generated automatically may differ from manually designed ASCII art

 Student Details

Name: Shriti Kumari
Course: AI/ML
Semester: 3rd
Institute: Rungta College of Engineering & Technology

 This project showcases Python fundamentals, image processing logic, and creative text-based visualization.

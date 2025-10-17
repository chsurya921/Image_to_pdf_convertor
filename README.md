# Image_to_pdf_convertor
This Python program allows users to convert multiple images into a single PDF file through a simple graphical interface (GUI). It is built using the Tkinter library for the user interface, Pillow (PIL) for handling images, and ReportLab for creating PDF files.

When the program runs, a small window appears with buttons and text fields. The user can click on the “Select Images” button to choose one or more image files (in formats like .jpg, .jpeg, or .png) from their computer. The selected image names are then displayed in a list box on the window.

After selecting the images, the user can enter a name for the output PDF file in the text box provided. Finally, when the “Convert to PDF” button is clicked, the program automatically arranges each selected image on a separate page in a new PDF document.

The program makes sure that all images are resized and centered properly on each page to fit neatly. Once the conversion is complete, the PDF file is saved in the same folder as the script (or working directory).

Overall, this project demonstrates:

->How to create a Graphical User Interface using Tkinter

->How to select files using the file dialog

->How to open and process images with Pillow

->How to generate PDF files using ReportLab

It’s a perfect beginner-friendly project to understand how Python can combine multiple libraries to create useful desktop applications.

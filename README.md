# Custom Resume Builder Website
This repository is a JScript template editor to generate resumes with customized templates

###### Live Demo - https://developer-geek.github.io/Resume_Builder/
###### Languages Used - HTML, CSS, JScript

**NOTE** : Click the "VIEW INSTRUCTIONS" button in the editor to read usage instructions.

#### Features :
- Resume content can be edited just like a normal document editor (cut,copy,undo etc).
- Section visibility can be toggled while retaining the content.
- Script provided to merge multiple pages and compress the PDF.
- Options provided in the left panel to modify the template and formatting.

#### Using the merge & compress script
- You must be able to run python file on your system for this.
- Save the individual pages in PDF format with name ```1.pdf``` , ```2.pdf```
- Download the ```compress_pdf.py``` file and open it in a text editor.
- Set the following variables :
	- ```dir_path``` : Directory path where you saved the PDFs for individual page
	- ```num_of_pages``` : Number of files to merge (i.e. pages in your Resume)
	- ```out_file``` : Name of output file
- Run this python file.
- Note: As this creates a new PDF file, you may have to see permission settings or run with sudo on terminal.

**Note** : Use Google Chrome

# LlamaParse_to_parse_PDF

In this repo - I would like to show how to use llamaParse to parse a document.

The document is a PDF file (Electoral Roll PDF listing all the voters in a certain constituency).

Each page is in this Voters List is an image of voters with their voter id, name, age, gender address etc, and contents cannot be extracted directly. A Sample of the page is shown below.

These are about 20 to 30 pages of PNG or JPG images, which is now showing up as a PDF document.

The text in this cannot be extracted directly, Each page has to be converted from the IMG ( PNG or JPG ) and the text has to be 
extracted using OCR.

LlamaParse is an Open Source tool that allows users to extract contents of each page and creates a MarkDown md file as an output.

I have used the API from LlamaParse and fed in the PDF document as an input and let it extract the the contents to an Markdown output file.

A sample first page image in the Input file is as shown. Has the voters Id along with related information.... ( There are about 20-30 such images converted to a single PDF file)

<img width="705" height="208" alt="image" src="https://github.com/user-attachments/assets/9f215853-af58-4e96-8129-b75975128053" />

The objective here is to use LlamaParse tool to convert it to text / output.

A sample Markdown output is shown below.

<img width="922" height="299" alt="image" src="https://github.com/user-attachments/assets/d06b4227-212b-4543-97ce-5e72328dc8df" />





Sign in to llama index Portal

https://www.llamaindex.ai/llamaparse


<img width="995" height="462" alt="image" src="https://github.com/user-attachments/assets/165dce91-c230-4cf6-8139-f991cbda1711" />

Sign In -> Global 

---

<img width="419" height="173" alt="image" src="https://github.com/user-attachments/assets/db55474b-5bc8-4623-bc95-1892abcd3b1b" />

---

<img width="365" height="301" alt="image" src="https://github.com/user-attachments/assets/3551f026-4fed-42b8-bf36-fb7666396a0b" />

--- 
Upload a pdf file

Go to Code and select Javascript

<img width="380" height="198" alt="image" src="https://github.com/user-attachments/assets/de989c66-c1ba-49d9-8392-136fa60ed5c9" />


Download the Javascript to you local workstation

OR

You can parse it there itself - but it will cost you.






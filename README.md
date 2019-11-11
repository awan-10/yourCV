1. Edit yourCV.adoc file and add content

2. Run the following to make HTML

asciidoctor -a nofooter -a stylesheet=yourCV.css yourCV.adoc

3. Run the following to create a PDF

wkhtmltopdf yourCV.html yourCV.pdf

Instructions are taken from: 

https://breslawscripts.co.uk/blog/generate-your-cv-in-html-pdf-and-docx-with-asciidoc/




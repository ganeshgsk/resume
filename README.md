Markdown Resume
============================
Mirror of https://git.chmd.fr/?p=resume.git


### Write your resume using markdown and convert it to HTML (using CSS) or to any other format like docx, pdf etc.


##Usage instructions
- Fork this repo and clone it. 

  `git clone https://github.com/sarathjiguru/resume`

- install pandoc (a universal document converter)

  `sudo apt-get install pandoc`

- convert Markdown to html 

  `pandoc -o index.html --css style.css index.md`
- To convert to PDF, you can use pandoc, but I felt chrome is doing better job for this. 
  
  Open the html in chrome browser, hit ctrl+p. 
  
  **Note:** Don't forget to uncheck headers and footers, as it will result in adding headers and footers, 
  which contain source filenames(index.html in our case) and page numbers. 
  

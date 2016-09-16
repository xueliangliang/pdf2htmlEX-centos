# pdf2htmlEX-centos
pdf2htmlEX container and easiest way to convert pdf to html file using cenos:latest as base

# How to use this docker containter to convert pdf file to html
Suppose you have a PDF file ~/pdf/test.pdf, simply running
`docker run -ti --rm -v ~/pdf:/pdf xueliangliang/pdf2htmlex pdf2htmlEX --zoom 1.3 test.pdf`
would produce a single HTML file test.html in ~/pdf directory.

For detail instruction on how to run pdf2htmlEX, please read the wiki

https://github.com/coolwanglu/pdf2htmlEX/wiki/Quick-Start

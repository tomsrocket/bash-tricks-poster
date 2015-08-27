# The bash.tricks-Poster

## What is this?

bash.tricks, a poster showing a fine selection of bash commands & parameters. 
Print it in A1 size and put it on your wall. 
For geeks, hackers, coders.

## Demo

See the HTML version here: http://tomsrocket.github.io/bash-tricks-poster/poster-bash-tricks.html
Just to get a rough impression of the commands that are listed and the basic styling. The poster is prettier than the HTML version. :-) 

## How to compile

1. Download WkHtmlToPdf from http://wkhtmltopdf.org/downloads.html

2. Generate Poster PDF with the following command:
	```bash
	wkhtmltopdf -O Landscape -s A1 poster-bash-tricks.html poster-printable.pdf
	``` 
3. Go to your favorite copy shop and print it in size DIN A1. (If you don't bother reading small fonts, DIN A2 might work, too)


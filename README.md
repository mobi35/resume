# Adrian Radores Resume

Based off of sb2nov/resume & jakegut/resume

create pdf

```
sudo pacman -S texlive && pdflatex resume.tex
```

to convert to image

```
brew install poppler imagemagick
convert -density 300 resume.pdf -colorspace sRGB -background white -alpha remove -alpha off resume.png
```

![Resume Preview 1](resume-0.png)
![Resume Preview 2](resume-1.png)

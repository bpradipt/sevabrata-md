# Updating
Create new index.html by running the following command

```
pandoc -c pandoc-files/pandoc.css --section-divs  -s --template=pandoc-files/tufte.html5 -f markdown+smart  -t html5 --metadata title=" "  *.md -o index.html
```

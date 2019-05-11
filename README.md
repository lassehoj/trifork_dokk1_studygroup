Small blog for the Trifork Dokk1 Study Group, where we read papers and discuss them.

Find it here: https://lassehoj.github.io/trifork_dokk1_studygroup/ 

Use docker to check layout of new posts locally:
```
docker run --name myblog --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:3.7 jekyll serve --watch --drafts
```
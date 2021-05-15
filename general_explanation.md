### 1. Preprocessing 


##### Step 1) Running refine.py

If you open the file named "refine.regex.txt", there come tow columns of letters,each separated by a tab. Unlike Japanes and Chinese,Korean langauge does contina or support double byte.
For precautionary purposes,we will take an extra step for a transformation of double to single byte. Right after running the line below, there appears a newly generated file
called review.sorted.uniq.refied.tsv'

```linux
python3 refine.py  refine.regex.txt 1  <review.sorted.uniq.tsv> review.sorted.uniq.refined.tsv

```

step 2) 

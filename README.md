# CMSC5702 – Advanced Topics in Parallel / Distributed Systems

Assignment 2: Parallel Programming  
Topic 1: CMSC5702-asgn2a-MapReduce
=======

## Group Member List:

- LEE Kai Chun 1155154969
- LAM Ka Lok 1155164795
- KWONG Chi Ho 1155033442

## Installation:

- Our group used Python to implement the program

- The source code is on Google Colaboratory
- The following link is the source code of our group: https://colab.research.google.com/github/Kyle-kclee/cmsc5702-asgn2a-MapReduce/blob/main/MapReduce.ipynb

- Upload the input file (HTML files) directly under the path "/content/" and right click for upload before running the program  
  ![Upload](https://user-images.githubusercontent.com/96198188/162397540-2f1e2380-f54f-4790-be53-953fb1d13128.png)
- Install "pyspark" pakage before running the program

- If the Google Colab notebook cannot be used, please visit the following GitHub link to download our source code: https://github.com/Kyle-kclee/cmsc5702-asgn2a-MapReduce

## Testing:

- The result of our program is shown in the following image
  ![result](https://user-images.githubusercontent.com/96198188/162397559-a14bcdec-4a37-4be3-a9dc-3b69ffd2b7d9.png)

- There are some variances in href count from the sample output, including the following:
  - `#` - 176 (179 in sample output)
  - `http://stanfordmedicine.org/flu/` - 22 (23 in sample output) 

  
- It is found that some `<a>` tag lies inside the comment block, thus being ignored by the Beautiful Soup library. \
  Below shows an example in `147.html` that leads to the variance of `http://stanfordmedicine.org/flu/`
  ![comment](https://user-images.githubusercontent.com/96198188/162397494-8e48ea7f-60e4-4d5a-bbeb-f70fdf61060f.jpg)

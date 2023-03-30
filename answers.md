# CMPS 2200 Recitation 6
## Answers

**Name:**__Tanner Martz_______________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt         |    1340              |     1141            |  1:1.17
alice29.txt    |    1039367           |     1050386         |  1:0.98
asyoulik.txt   |    876253            |     827516          |  1:1.05
grammar.lsp    |    26047             |     26097           |  1:0.99
fields.c       |    78050             |     73120           |  1:1.06

Huffman encoding achieves greater compression efficiency when there is a limited variety of characters present.

- **e.**

In this situation, the size of the Huffman encoding is directly related to the number of distinct characters within the file. As the diversity of characters differs among various files, this proportional relationship will not remain consistent across different files.

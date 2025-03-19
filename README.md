# Purpose of this repository

This repository is for a material of M1 introduction in 2025

**Contact**: *umakoshi[at]icepp.s.u-tokyo.ac.jp*


# How to convert from tex files to a PDF file

Just conduct below command.

```
./latex.sh
```

# Explanation about files

## main.tex

This is a main tex file. "documentclass" is defined in this file. Also, when one want to add new chapter, add "\include{tex_name}" in this file.

## AuthorInfo.tex

Title, author name are written in this file.

## thesis_cover.sty

Cover format of thesis is created in this file. AuthorInfo.tex is loaded in this file to output its info. Also, Affiliation is written in this file.

## thesis.bib

This file is for bibliography. After adding bibliography infomation, when they are citated in the tex files, the bibliography infomation are wrote in the bibliography chapter.

# Reference

This repository was created by modifying the Okumura's [MasterThesisTemplate](https://github.com/akira-okumura/MasterThesisTemplate).
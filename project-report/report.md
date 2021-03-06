# Sample Project Report :hand: fa18-523-000 fa18-523-001

| Gregor von Laszewski, Albert Zweistein
| laszewski@gmail.com, zwei@example.edu
| Indiana University, Example University
| hid: fa18-523-000 fa18-523-001
| github: [:cloud:](https://github.com/cloudmesh-community/proceedings-fa18/blob/master/project-report/report.md)
| code: [:cloud:](https://github.com/cloudmesh-community/proceedings-fa18/blob/master/project-code)

> If you do a project report only without any code, remove the line
> with the code url link. Remove this line also ;-)

---

Keywords: Cloud, Example

---

## Abstract

TBD

## Introduction

One possible way of structuring the document.
We may have to tweak this example as we progress.

Make sure paragraphs are 80 chars wide 

Place images in an images directory

Use empty lines before and after headings

In [@vonLaszwski-fa18-sample-report] we can find a sample report.

Naturally the headings are just suggestions and you may change them as
appropriate for your project.

## Requirements


### Images

Image locations that start with http are not allowed. All images must be in an images folder within your directory.

All images must be referred to in the text. The words bellow and above
must not be used in your paper for images, tables, and code. For code you could use 

> In the previous

> In the following 

> As explained next

> We install the softwere with

BUT DO NOT USE THEM FOR IMAGES, ANY IMAGE MUST HAVE A MEANINGFUL CAPTION AS SHOWN IN OUR EXAMPLE

Comment: Above and bellow in a paper means you ask the reader to look at their shoes or the ceiling :smiley:.

+@fig:fromonetotheorther shows a nice figure exported from Powerpoint
to png. If you like you can use this as a basis for your drawings.

![A simple flow chart](images/from-one-to-the-other.png){#fig:fromonetotheorther}

Figures must not be cited with an explicit number, but automated
numbering must be used. Here is how we did it for this paper:

```
+@fig:fromonetotheorther shows a nice
figure exported from Powerpoint to png.
If you like you can use this as a basis
for your drawings.

![A simple flow chart](images/from-one-to-the-other.png){#fig:fromonetotheorther}
```

If the paper is copied form another source you MUST use a citation in the caption. 

![A simple flow chart [@vonLaszwski-fa18-sample-report]](images/from-one-to-the-other.png){#fig:fromonetotheorthertwo}

This is done as follows

```
![A simple flow chart [@vonLaszwski-fa18-sample-report]](images/from-one-to-the-other.png){#fig:fromonetotheorthertwo}
```

### Sylistic Issues

Your report must not include the phrases


* In this term project we show
* In this project we describe
* In this chapter we have
* In this report we do

or similar

Instead you use

* We show
* We describe
* We have
* We do

You will not use the word `I` but instead you will use `we` or third person.



### Copy from this document

In case you want to copy part of this document you need to do this from raw mode

* <https://raw.githubusercontent.com/cloudmesh-community/proceedings-fa18/master/project-report/report.md>

**HOWEVER, YOU MUST NOT COPY THIS EXAMPLE IN YOUR REPORTS. IF YOU DO YOU MUST
CHANGE THE IMAGE REFERNCES. THIS IS LOGICAL AS ALL IMAGE REFERNCES
MUST BE UNIQUE.**


## Design 

## Architecture

## Dataset

## Implementation

## Benchmark

## Conclusion

## Acknowledgement

## Workbreakdown

Only needed if you work in a group.


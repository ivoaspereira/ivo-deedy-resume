Ivo-Deedy-Resume
=========================

A **one-page**, **two asymmetric column** resume template in **XeTeX**.
This is **v1.0**, using **OpenFonts** - free, open-source fonts that resemble the above - *Lato* (and its various variants) and *Raleway*.

It is licensed under the Apache License 2.0.

## Motivation
Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter)  and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates. 

Based on [**Deedy-Resume**](https://github.com/deedy/Deedy-Resume), this template attempts to **look clean**, while **beautiful**, highlight **details**, be a **single page**, and allow useful **LaTeX templating**.

Original [**Deedy-Resume**](https://github.com/deedy/Deedy-Resume) do not have a cover letter template. Based on [**Anthony Attard work**](https://github.com/anthonyattard/Deedy-Resume), a cover letter template was added.

## Preview
### Resume
![alt tag](https://raw.githubusercontent.com/ivoaspereira/ivo-deedy-resume/master/dist/template-resume-1page.png)
### Cover Letter
![alt tag](https://raw.githubusercontent.com/ivoaspereira/ivo-deedy-resume/master/dist/template-cover-letter.png)

## Dependencies
1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.

## Changelog
### v1.0
 1. Added \header command for name section with background color
 2. Added \skill command for a bullet-based skill classification (until 5)
 3. Added \companylogo command for adding institution logos
 4. Added Summary section
 5. Changed order of 1st column topics

## Known Issues:
1. Overflows onto second page if any column's contents are more than the vertical limit
    -- One possible solution in next version

## License
    Copyright 2014 Debarghya Das

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

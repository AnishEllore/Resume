Credits: [Original Author-Sourabh Bajaj](https://github.com/sb2nov/resume)

### Motivation
Inspired from the above credited resume and modified to my usecase. Added few commands to suit my needs. Hope this helps.

### Information
A single-page, one-column resume for software developers. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The five main sections in the resume are education, experience, publications, projects, and skills.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex anish_reddy_ellore_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Anish Reddy Ellore.

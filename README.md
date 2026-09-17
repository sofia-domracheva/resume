A single-page, one-column resume for software developers. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.

The original LaTeX template was created by [Sourabh Bajaj](https://github.com/sb2nov) (available at [sb2nov/resume](https://github.com/sb2nov/resume)) and is distributed under the MIT License.

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sofia_domracheva_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Resume template is under MIT license (original by Sourabh Bajaj). All personal data is owned by Sofia Domrachev.

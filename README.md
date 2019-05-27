# Resume
## Personal resume in LaTeX and Open Document formats.
The cover letter is written in a plain text document to allow for easy changes as needed. Necessary, user-specific changes in `/src/resume.tex` are prefaced with comments of the format `### <Information to add>`.

### Preview
<p align="center">
<img src="src/assets/preview/resume.png" width="250" style="margin-right:5px; border: 1px solid #ccc;" />
</p>

## Compiling files
To make the pdfs using LaTeX, simply run

```
bash make.sh
```

from the parent directory.

### Required dependencies
``texlive-core``, (Dejavu font](https://www.ctan.org/pkg/dejavu).

## Note about Open Document files
The Open Document file has a lot of peculiar spacing and indenting from trying to fit all information onto the page which is why I decided to re-do it in a LaTeX to have absolute control over specific formatting.

# Resume
## Personal resume in LaTeX and Open Document formats.
The cover letter is written in a plain text document to allow for easy changes as needed. Necessary, user-specific changes in ``/src/resume.tex`` are prefaced with comments of the format ``### <Information to add>``.

### Preview
<p align="left">
<img src="src/assets/preview/resume.png" width="450"/>
</p>

## Compiling files
To make the pdfs using LaTeX, simply run

```
bash make.sh
```

from the parent directory.

### Requirements
``texlive-core``, [Dejavu font](https://www.ctan.org/pkg/dejavu) (I personally just install ``texlive-fontextras``).

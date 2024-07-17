# latex-workspace
This is a template repository for latex projects

This repository has CI/CD pipelines. They only work for branches staring with `latex`.
Those pipelines work only for pull requests. The CI pipeline is used to prevent broken
LaTeX documents from being merge in the main branch. On the other hand, the CD pipeline
is used to build the a pdf of the main document and a pdf with changes. At last this
piepline automatically creates a release with the those pdfs. The `latex` directory
is needed by the CD pipeline so that a the old latex document can be copied to
a different directory.
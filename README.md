# UpdateHub
This is the UpdateHub Cloud documentation. In moment we are building this, so if you have a contribution, send to us =)


## How to run

After to clone just run the command to execute MkDocs server:

```
mkdocs serve
```
## How to run with Docker

Build: docker build -t mkdocs .

Run: docker run --rm -it -p 8000:8000 -v ${PWD}:/docs mkdocs

## Structure

*mkdocs.yml* - it is the configuration file: navigation structure, theme definitions, personal informations, among others are here.  

*docs* - this folder contains the pages contents of the documentation.

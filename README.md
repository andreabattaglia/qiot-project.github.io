# qiot-project.github.io
Official website for qiot-project

Use asciidoctor (https://asciidoc.org/userguide.html) to generare the HTML page:

$ docker run -it -v ${PWD}:/documents/ asciidoctor/docker-asciidoctor asciidoctor index.adoc
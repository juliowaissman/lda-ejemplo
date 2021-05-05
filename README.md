# Ejemplo de uso de LDA en modelado de tópicos

**Olivia Gutú y Julio Waissman**

En este ejemplo vamos a ver como se realiza el modelado de tópicos. 

Para poder hacer el ejemplo es necesario crear un entorno de `conda`con

```bash

$ conda create --file lda-ejemplo.yml

```

y luego activar el entorno virtual con

```bash

$ conda activate lda-ejemplo 

```

Por último, para poder usar el modelo de `SpaCy` es necesario descargarlo. Yo voy a usar como ejemplo el modelo en español más pequeño y más malo, pero luego podrán experimentar con otros modelos.

```bash

$ python -m spacy download es_core_news_sm

```

También es necesario obtener los sonetos del siglo de oro español, los cuales se encuentran
a disposición de todo el mundo gracias a [Borja Navarro-Colorado](https://github.com/bncolorado),
quien hizo un esplendido trabajo con los sonetos, puestos a disposición de todo el público por la 
[Biblioteca Virtual Miguel de Cervantes](http://www.cervantesvirtual.com).

```bash

$ git clone https://github.com/bncolorado/CorpusSonetosSigloDeOro.git

```

Ahora si, ya puedes ejecutar la libreta de *jupyter* que se incluye en este repositorio.

Con el fin de afianzar los conocimientos, al final de la libreta se incluyen algunos ejercicios para practicar con el modelado de tópicos.


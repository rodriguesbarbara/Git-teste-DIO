##           Objetos Internos do Git



* **Blobs**: Contém o tipo do objeto. o tamanho da string, armazena *metadados*.
* **Trees**: Também tem metadados, aponta para um Blob, pode também apontar para uma outra árvore. Responsável por montar toda estrutura de onde estão os arquivos.
* **Commit:** O objeto mais importante de todos, ele aponta para uma árvore, para um parente, para o autor do arquivo e passa uma mensagem. Assim dando significado a todos esses diretórios e arquivos. Usamos ele para explicar qualquer alteração realizada.
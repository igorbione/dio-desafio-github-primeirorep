# Entendendo como o git funciona por debaixo dos panos

Curso: Introdução ao Git e ao Github
Tags: Prepare-se para a Jornada (Onboard)

### Tópicos fundamentais para entender o funcionamento do git

- SHA1

É um algoritmo de encriptação, que gera um conjunto de caracteres identificador de 40 dígitos. Por isso ele é extremamente eficiente em distinguir versões por menor que sejam.

- Objetos principais do GIT
    
    Blobs - Contém metadados do arquivos (como por exemplo seu SHA1)
    
    Tree - Armazenam Blobs, e tbm possui um SHA1 próprio.
    
    Commit - Aponta pra uma arvore, pra um commit e para um autor. Tbm possue um SHA1. Essa estrutura protege e permite que todo tipo de modificação seja vista.
    

![Untitled](Entendendo%20como%20o%20git%20funciona%20por%20debaixo%20dos%20pan%201589973f669d4c20adcb27934f15d269/Untitled.png)

- Chave SSH - Forma de estabelecer uma conexão segura entre duas máquinas.
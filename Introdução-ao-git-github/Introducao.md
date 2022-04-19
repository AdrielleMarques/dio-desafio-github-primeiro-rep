### Introdução ao Git

**Git** é um software de versionamento de código distribuído. 

**Github** é um repositório online. 

---

### Navegação via command line interface e instalação

Comandos de terminal:

| WINDOWS | UNIX |  |
| --- | --- | --- |
| - cd | - cd | mudar de diretório |
| - dir | - Is | listar |
| - mkdir | - mkdir | criar diretório |
| - del / rmdir | - rm -rf | deletar  |

**SHA1** significa Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA), ou seja algoritmo de encriptação. A encriptação gera conjunto de characteres identificador de 40 dígitos, que são únicos e servem como identificação. 

É uma forma curta de representar um arquivo. 


Objetos interno do Git: 

**Blobs** contem metadados do git

**Trees** armazena blobs, contem também metadados, guarda o nome do arquivo. Responsável por montar a estrutura de onde está os arquivos. Elas também tem o SHA1 dos metadados das arvores. 

**Commits** é o objeto que vai juntar tudo. 

**Chave SSH** uma forma de estabelecer uma conexão segura e encriptada entre duas maquinas.

**Git INIT** cria um repositório.
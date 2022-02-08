# DIO desafio github
Repositório do desafio de projeto gi/github da DIO

## Links úteis
[Sintaxe básica markdown](https://www.markdownguide.org/basic-syntax)

[W3Schools para compreender linguagens](https://www.w3schools.com)

## Notas das aulas de git
- **CMD:** comando usado para abrir um diretório
- **DIR:** comando para saber todas as pastas que há dentro do repositório local
- **CD:** comando para navegar entre pastas e o que esta dentro da pasta
    - utiliza-se cd sguido do nome da pasta que está dentro do repositório local
- **CLS:** comando utilizado para limpar o terminal 
- **TAB:** se quiser que o sistema complete o nome é só clicar e tab
- **MKDIR:** comando criar uma pasta
    - utiliza-se mkdir seguido do nome que deseja nomear essa nova pasta
- **ECHO:** comando para printar na tela
    - utliza-se echo seguido de um termo entre aspas para que seja printado na tela
- **DEL:** comando para deletar arquivos, porém não deleta repositórios
- **RMDIR:** comando para deletar repositórios
- **SHA1:** desenvolvida pela NSA, é um código encriptografado de 40 dígitos que de forma curta identifica um arquivo, já que a cada mudança o código do arquivo muda, mesmo que seja apenas uma vírgula 
- **MV:** mover uma pasta para outra pasta
- **GIT INIT:** cria o .git e inicialza o repertório
- **GIT ADD:** move o arquivo, seja ele untracked ou modified, para stage
    - a estrutura pode ser: git add nomeArquivo ou git add* ou git add.
-**GIT COMMIT -M "MENSAGEM":** pega os arquivos que estavam em staged, envelopou em uma mensagem, deu sentido para eles e levou eles para unmodified(repositório local)
-**GIT CINFIG --LIST:** configurações do git para fazer correlação com o github
-**GIT CONFIG --GLOBAL --UNSET:** redefinir o que quer
   - ex: "user.email/user.name..."
-**GIT REMOTE ADD ORIGIN:** passar o código local para remoto e primeiro colocasse a origem
-**GIT PUSH ORIGIN MASTER:** passar de local para remoto
-**GIT PULL ORIGIN MASTER:** puaxr o documento/arquivo remoto para seu repoditório local para que você entenda as mudanças e resolva antes de mandar de volta


## Objetos internos
- **BLOBS:** guarda objetos 
- **TREE:** armazena blobs e apontam para blobs diferentes ou outras árvores
- **COMMIT:** junta tudo

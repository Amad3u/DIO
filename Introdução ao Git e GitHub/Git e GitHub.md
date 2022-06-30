# Git e GitHub

**Oque é o Git?** 

Sistema de versionamento de dados distribuído.

**Benefícios do uso das tecnologias:**

- Controle de Versão;
- Armazenamento em Nuvem;
- Trabalho em equipe;
- Melhora no seu código;
- Reconhecimento

**Comandos Básicos de Navegação no Terminal**

- Windows
    - **dir**: Lista diretórios contidos na pasta situada.
    - **cd:** Usado para navegar entre pastas.
        - **“cd/”:** Direciona ao diretório base do sistema.
        - **“cd nomeDaPasta”:** Redireciona a pasta escolhida.
        - **“cd . .”:** Retrocede uma pasta.
    - **cls:** Limpa o terminal.
    - **mkdir nomeDaPasta**: Cria um diretório no sistema.
    - **echo:** Imprime no terminal o texto informado.
        - echo nomeDoArquivo > conteudoDoArquivo. (Criando um arquivo)
    - **rmdir:** Deleta um diretório e todo seu conteúdo.
    - **del:** Remove apenas arquivo.
- Linux
    - **ls:** Lista de diretórios contidos na pasta situada.
    - **cd:** Usado para navegar entre pastas.
        - **”cd/”:** Direciona ao diretório base do sistema.
        - **“cd . .”:** Retrocede uma pasta.
        - **“cd nomeDaPasta”:** Redireciona a pasta escolhida.
    - **clear:** Limpa o terminal.
    - **mkdir nomeDaPasta:** Cria um diretório no sistema.
    - **echo:** Imprime no terminal o texto informado.
        - echo nomeDoArquivo > conteudoDoArquivo. (Criando um arquivo)
    - **rm:** Apaga diretórios (Junto com as **flags -rf**).

**Chave SSH: Forma de estabelecer conexão segura e encriptada entre duas máquinas.**

**Comandos para criar chaves SHH**

- **ssh-keygen -t ed25519 -C seu_email:** Cria duas chaves SSH, uma pública e uma privada.
- **cat chave_ssh:** Mostra o conteúdo da chave pública.

**Comandos Básicos do Git (Por ordem de uso)**

- **git-init:** inicializa o git dentro do repositório.
- **git add ***
- **git commit -m “texto”**
- **git status:** mostra o status do arquivo
- **git remote add origin <link do repositório>**
- git push origin master
-
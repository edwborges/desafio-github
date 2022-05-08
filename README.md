# Projeto sobre Git/GitHub

 - ## Criação de projeto

    -  Crie um novo projeto no seu ambiente de desenvolvimento

    - Crie um novo repositório no Github
    - ATENÇÃO: na hora da criação do seu repositório no GitHub, selecione o .gitignore, Git usa um arquivo oculto chamado .gitignore para indicar quais arquivos ou tipos de arquivos não devem ser rastreados para o versionamento

    - Abra um terminal na pasta do seu projeto

    - IMPORTANTE: certifique-se de estar com o username e email no Git do seu computador.
 
    - ***git config --list***

    - ***git config --global user.name "Digite seu username do GitHub"***

    - ***git config --global user.email "Digite seu email usado no GitHub"***

##
 
 
 
 * ## Comandos para associar repositórios e enviar

    - Na pasta do seu projeto, abra o terminar do git e escreva  ***git init***,  isso inicia um repositório local na pasta do seu projeto.

    - a seguir digite:  ***git remote add origin https://github.com/username/projeto.git***,  isso associa seu repositório local ao repositório remoto.

    - ***git pull origin master***  isso atualiza seu repositório local em relação ao repositório remoto.

    - ***git status***  verifica arquivos.

    - ***git add .***  isso adiciona todos arquivos ao stage.

    - ***git commit -m "Primeiro commit"***  Salva uma nova versão do projeto.

    - ***git push -u origin master***  isso envia o repositório local para o repositório remoto, porem nas próximas vezes basta fazer: ***git push***


##



 *  ## Trabalhando com um projeto existente

    - ***git clone https://github.com/username/projeto.git***  para clonar um projeto para o seu ambiente de desenvolvimento.


##



 *  ## Outros

    - caso vocẽ queira desfazer tudo que fez desde o último commit, faça:  ***git clean -df***  e  ***git checkout -- .***

    - caso você precise remover o último commit, porém mantendo os arquivos do jeito que estão:  ***git reset --soft HEAD~1***.

    - caso queira alterar temporariamente os arquivos do projeto de modo a ficarem no estado do commit informado:  ***git checkout <código do commit>***.

    - para apagar o último commit:  ***git push -f origin HEAD^:master***.

    - caso queira mudar o seu repositório remoto "origin":  ***git remote set-url origin https://github.com/username/projeto.git***.

## 

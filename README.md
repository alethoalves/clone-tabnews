# clone-tabnews
Projeto para aprofundar meus conhecimentos em programação e tornar meus códigos mais profissionais
# Qual a diferença entre Git e GitHub?

# Primeiros passos:
## Instalar o node (é a FUNDAÇÃO), docker, docker-compose, nvm
- O node é a dependência mais importante para um projeto. Mas porquê? 
- O nvm (Node Version Manager) é um utilitário que serve para para alterar a versão do node que rodará no servidor 
- - nvm ls -> lista as versões do node
- - nvm install [nomeVersao] -> instala a versão do node no terminal
- - se houver o arquivo nvmrc, o comando para rodar o node é apenas nvm install
- - nvm alias default [nomeVersao] -> faz com que o apelido padrão do node seja alterado para a versão que é utilizada no projeto
- Ao criar um projeto, é importante informar aos futuros usuários do código qual versão do node o projeto utilizado. Isso é feito por meio do arquivo .nvmrc (Run Commands, são arquivos que possuem instruções de inicialização)  
## npm init 
Cria o package.json
## Instalar o next (são as PAREDES), react e react-dom
- NextJs é um framework para desenvolvimento web, análogo às paredes de uma casa, não define os objetos, orquestra tudo que acontece no projeto, definindo os limites de cada objeto tanto no back quanto no front
- - npm install next ou npm install next@13.1.6
- React define os objetos
- - npm install react ou npm install react@18.2.0
- - npm install react-dom ou npm install react-dom@18.2.0
## Alterando a versão padrão do node
Caso ao reabrir o terminar a versão do node for alterada, é possível alterar a versão padrão do node utilizando nvm alias default lts/hydrogen
## Criar um comando para rodar o site localmente
- - em package.json > "scripts", criar o comando "dev" que rodará: "next dev"
- - para rodar este comando: npm run dev
## CTRL L
- - comando substituto ao clear. O clear fica no historico de comandos, o CTRL L não.
## Criando uma url pública no codespaces
- - aula "Página Inicial"
- -  rodar o nom run dev
- - clicar no simbolo de antena do codespaces
- - alterar visibilidade
## Comandos GIT que rodam offline
- git log ver as fotos que tirei do repositório
- estágios do versionamento:
- - MODIFIED
- - STAGED git add [nomeArquivo]
- - COMMIT git commit
- git status
- git diff
## Comando que rodam online
- git commit -m "mensagem" - atalho para fazer novos commits.
- git push - empurrar alterações locais para o origin.
- git push --force - empurrar de forma forçada alterações locais para o origin.
- git push -f - a forma comprimida do comando anterior.

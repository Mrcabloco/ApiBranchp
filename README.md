# Criar projeto no github:

1. Criar um novo repositório
2. O gitignore deve ser: 'Node'
3. Clonar repositório na sua máquina:

No gitbash digitar:

git clone URL do repositório

# OBS: Lembrar de liberar os scripts:

Rodar o power Shell no modo adminitrador e executar e confirmar com 's':

1. Set-ExecutionPolicy RemoteSigned
2. s

# Instalar um projeto do zero (verificar se o node está intalado 'node -v'):

No terminal com o projeto aberto:

1. npm init -y
2. npm install express
3. CRIAR UM ARQUIVO index.js

# Rodar o projeto

1. node index.js
   OBS: Para alterar o projeto você deve parar o servidor (Ctrl+c) e rodar novamente

2. no navegador: http://localhost:3005/

# Fazer o commit:

No gitbash do seu repositório:

1. git status
2. git add .
3. git status
4. git commit -m "Nome do commit"
5. git push

6. OBS Se pedir para logar:

7. git config --global user.email "you@example.com"
8. git config --global user.name "Your Name"
9. E confirmar na caixa

# Branch

1. Criar uma nova branch chamada dev

No terminal:

1. git fetch
2. git checkout NOME DA BRANCH

No github: 3) Criar Pull Request e aprovar

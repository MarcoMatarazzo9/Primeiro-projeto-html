# COMO PUBLICAR UMA PAGINA NO GITHUB

O QUE VOCÊ PRECISA:
Conta no GitHub
Repositório com seu site (arquivos HTML)

PASSO A PASSO PARA PUBLICAR   V

1. Crie um repositório
Vá para github.com

Clique em "New repository"

Dê um nome

Marque a opção Public

Clique em Create repository

2. Envie seus arquivos do site
Você pode fazer isso de duas formas:

Pelo navegador:
Clique em "Add file" > "Upload files"

Faça o upload do seu index.html

Clique em "Commit changes"

Pelo Git (recomendado se você usa VS Code):
git clone https://github.com/seu-usuario/meu-site.git
cd meu-site
# Coloque os arquivos do site aqui (index.html)
git add .
git commit -m "Tanto faz"
git push origin main

3. Ative o GitHub Pages

Vá para a aba "Settings" do repositório

No menu lateral, clique em "Pages" ou "Pages" > "Deploy from a branch"

Em "Source", selecione:

Branch: main

Folder: / (root)

Clique em "Save"

Pronto
Após alguns segundos, o site estará no ar.

Você verá um link como este:
https://seu-usuario.github.io/meu-site/

# Prontinho/Marco Guilherme

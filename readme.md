Olá, esse projeto ensina você a usar o git.
Isto é uma alteração.


Salvar arquivo.
Abrir Git Bash na pasta do arquivo.
git init
git add NomedoArquivo.extensão
git status
git commit -m "título do comit"
git status

no site do github:
criar novo repositório (se for novo projeto), ou abrir repositório.
copiar link do repositório (no exemplo https://github.com/RodrigoRosa2022/ProjetGit.git)

no terminal gitbash:
git remote add origin linkDoRepositório
(usar ctrl+shift+insert para colar)
git push -u origin main

clear

para criar novas versões do arquivo, no tronco principal
git add .
(o ponto final puxa todos arquivos no endereço)
git status
git commit -m "titulo do commit"
(se já tiver feito conexão, não precisa fazer o git remote de novo)
git push origin main

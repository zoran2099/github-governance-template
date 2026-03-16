
npm install -D @commitlint/cli @commitlint/config-conventional

---
npm install --save-dev husky
 
npx husky install

echo "npx --no -- commitlint --edit \$1" > .husky/commit-msg

---

npm install --save-dev @commitlint/cz-commitlint

---
próximos passos

fazer readme

fazer docs glossario e tur

ai assist

desacoplar solução do projeto do desenvolvedor e torna-lo instalável

usando npmcomm

instalar na máquina com scprit, configurar alias para o comando `git commit` 

usar https://direnv.net/ ou configurar o alias apenas nos diretório dos projetos que vão usar o gitflow


fazer a instalação no ambiente do dev através do hook de pos-checkout da develop


plugins para IDEs (vscode, vi...).



adicionar suporte para parametros
 npm run commit -m 'teste'
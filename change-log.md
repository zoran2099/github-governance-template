
npm install -D @commitlint/cli @commitlint/config-conventional

---
npm install --save-dev husky
 
npx husky install

echo "npx --no -- commitlint --edit \$1" > .husky/commit-msg

---

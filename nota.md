# Notas

## sobre o projeto

O projeto trata de uma api rest, tem configuração com o redis, mongodb
serve para cadastrar e listar funcionários, é utiliza o express

## Configurando o ESLINT

Segundo Tiago Bussola, um código que não segue nenhum padrão,
(há aspas simples e duplas, variáveis sem utilizar, funçoes em padronização de nomes, probleams
com espaçamentos).
Este tipo de coisa prejutica a leitura e consequentemente pode afetar o entendimento
do código (pense por que ....)

Qual ferramenta o time usa para compartilhar as padronizações entre a equipe?

---

```sh
npm init @eslint/config@latest
Need to install the following packages:
@eslint/create-config@1.8.2
Ok to proceed? (y) y


> eslint-project@1.0.0 npx
> create-config

@eslint/create-config: v1.8.2

✔ What do you want to lint? · javascript, json, md, css
✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · none
✔ Does your project use TypeScript? · no / yes
✔ Where does your code run? · node
✔ What flavor of Markdown do you want to lint? · commonmark
The config that you've selected requires the following dependencies:

eslint, @eslint/js, globals, @eslint/json, @eslint/markdown, @eslint/css
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · npm
☕️Installing...

added 385 packages, and audited 386 packages in 23s

166 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Successfully created /home/tiago/projects/alura/4549-eslint/eslint.config.js file.
```


---

mongosh --host 192.168.10.5 --port 27017 --username mongouser --password xxxxxxx 


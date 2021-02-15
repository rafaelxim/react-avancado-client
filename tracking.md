# Comandos Executados

## Instalação do ESLint no projeto

`npx eslint --init`

#### Configurações utilizadas

✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ What format do you want your config file to be in? · JSON

#### Instalando dependências necessárias com yarn

`yarn add --dev eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest eslint@latest`

### Plugin para reforçar as regras dos hooks

`yarn add eslint-plugin-react-hooks --dev`
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

## Plugin para reforçar as regras dos hooks

`yarn add eslint-plugin-react-hooks --dev`

## Configurando Prettier
#### Instalar
`yarn add prettier --dev --exact`

#### Integrar com ESLint
`yarn add --dev eslint-config-prettier eslint-plugin-prettier`

## Git Hook
Executa validações antes de executar os comandos do GIT.

`yarn add husky@4.3.8 lint-staged`

## Configurando Jest
`yarn add --dev jest @babel/preset-typescript @types/jest `

## Configurando React Testing Library + Jest Dom
`yarn add --dev @testing-library/react @testing-library/jest-dom`

## Configurando o styled components
`yarn add --dev @types/styled-components babel-plugin-styled-components`
`yarn add styled-components`

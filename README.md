Projeto Semáforo de Trânsito em React Native
Este é um aplicativo simples em React Native que simula um semáforo de trânsito. O semáforo alterna entre as cores verde, amarelo e vermelho em intervalos regulares quando ativado.

Funcionalidades
O projeto consiste em criar um aplicativo, onde contenha um ícone, um botão liga/desliga (SWITCH) e a mudança de imagens. No caso de meu projeto, esta mudançao de imagens é a simulação da transição de cores de um semáforo.

Interruptor (Switch): Permite habilitar ou desabilitar a mudança de cores do semáforo.
Semáforo: Exibe as cores verde, amarelo ou vermelho.
Estrutura do Projeto
assets/: Contém as imagens utilizadas no aplicativo.
App.js: Código-fonte principal do aplicativo.
styles.js: Estilos definidos para o componente.
Documentação Oficial da API REACT NATIVE e EXPO
https://reactnative.dev/

https://expo.dev/

Instalação das Dependências
1. No prompt de comando (cmd) instale as dependências

  npm install -g expo
2. Clone este repositório caso queira testa-lo

3. No VScode, abra a pasta do projeto, abra o terminal e crie o projeto

  npx create-expo-app trafficlight => 'trafficlight' é o nome do seu aplicativo
4. Entre na pasta do aplicativo

  cd trafficlight
5. Instale estas dependências

  npx expo install react-native-web react-dom @expo/metro-runtime
6. Após o término da instalação das dependências, inicie a aplicação web com o comando

  npm run web
Autores
@octokatherine
Instituição de Ensino
Escola Senai - unidade Jaguariúna - SP

Curso de Desenvolvimento de Sistemas FullStack 2DES

Professor Robson aula de INDMO

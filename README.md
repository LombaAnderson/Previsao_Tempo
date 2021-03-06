# Previsao_Tempo
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/Previsao_Tempo/blob/main/LICENSE)

# Sobre o projeto
Previsao_Tempo é um projeto feito com Vuejs, Bootstrap, HTML e CSS no front-end; Nodejs e API OpenWeather(http://openweathermap.org/) no back-end. Houve a preocupação de organização do código em pastas e de maneira que o mesmo ficasse mais fluido. Primeiramente foi instalado e importado o Bootstrap Css para estilizar a página de pesquisa das localidades e em seguida foi montada a estrutura html dentro do componente App.vue, foi feita a importação do CSS personalizado para o arquivo único do projeto e prosseguindo com o mesmo foram criados os dados reativos Vue para poder acessar as cidades pesquisadas. Continuando foi feita a renderização dos dados reativos em tags html e implementado o 'Two way binding (V-model)' para alterar os valores inseridos no Javascript. Em seguida implementadas as funções no Vue, os chamados métodos e a implementação de async/await para simplificar o código de forma assíncrona, foi desenvolvido também o try/catch para tratamento de erros no momento de pesquisar as cidades ou países. Foi verificado também o clima atual e a hora do dia e foram tratados erros para quando nenhuma cidade fosse encontrada a plataforma acusasse. Por fim foi instalado o jest e efetuados testes para verificação do conteúdo do componente App.vue.

## Imagem web de Previsao_tempo
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/142774613-f15b79ef-fc8e-4af4-b926-44cccaa7fcc2.png" width="600" />
</div>

## Imagem da consulta da cidade ou país conforme localidade( se é dia ou noite) 
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/142775881-7bdadc25-77aa-4e8e-af08-cb42c9a42d91.png" width="800" />
</div>

## Imagem de erro caso a localidade não seja encontrada
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/142776028-9ed3548c-cc90-48a9-873a-0f829cc61e54.png" width="600" />
</div>

# Tecnologias utilizadas
## Front end
- Vuejs / CSS / JS / HTML

## Back end
- NodeJs
- API do OpenWeatherMap

# Testes unitários 
- Jest
- Vue-test-utils

# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/Previsao_Tempo

# Criação do projeto com o cli do Vuejs atráves do npm Nodejs
-npm -g install @vue/cli

# Criação do projeto com Vuejs
-vue create previsao-tempo

# Escolha na instalação do Vue CLI
> Default([Vue 2] babel, eslint)

# Para compilar o projeto
- cd previsao-tempo
-npm run serve

# Acesso ao navegador
- Local: http://localhost:8081/
- Network: http://192.168.100.40:8081/

# Instalação do Jest para testes
-vue add unit-jest

# Instalação do Vue Test Utils
-npm install --save-dev @vue/test-utils

# Criando pastas e fazendo testes
-Pasta components/tests 
- Criação do arquivo 'App.vue.spec.js' dentro da pasta tests
-Realização de teste de 22 componentes do projeto e todos Ok

```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço sobretudo a Deus e a minha esposa, minha companheira que torce muito por mim!

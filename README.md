# dyMoney - Trilha Ignite da Rocketseat

<p>A aplicação tem como finalidade oferecer uma forma do usuário fazer o controle de suas entradas e saídas, servindo como um controle financeiro.</p>
<p>Nesta aplicação foi desenvolvido um dashboard onde o usuário pode listar todas as suas entradas/saídas e ter um panorama do gastos e entradas totais. E também uma modal onde ele pode estar fazendo novos lançamentos.</p>
<p>A aplicação foi desenvolvida como parte do Segundo Capítulo da trilha Ignite da RocketSeat</p>

<br />

## ⚙️ Funcionalidades da Aplicação

<ul>
  <li>Inserção de novas "transações", podendo ser do tipo receita ou despesa.</li>
  <li>Uso de banco de dados MirageJS que simula um db local onde são inseridas as transações.</li>
  <li>Soma de todas entradas e saídas, retornando ao usuário o total de ambos e o total geral.</li>
</ul>

<br />

## 🔧 Instruções para executar a Aplicação localmente

<br />

<p>Primeiramente você precisa ter VS Code e o Node.js instalados na sua máquina.</p>
<p>Caso ainda não os tenha instalado, você pode fazer o download através dos links abaixo:</p>

* [Visual Studio Code](https://code.visualstudio.com/download)
* [Node.js](https://nodejs.org/en/download/)


Após isso, podemos seguir para o clone e execução da Aplicação!

<br />

1° - Faça o clone do repositório a partir do seu terminal:
```bash
  git clone git@github.com:JVMMiguel/dtmoney.git
```

2° - Acesse a pasta onde foi feito clone do repositório e instale as dependências necessárias:
```bash
  cd dtmoney && yarn
```

3º - Após instaladas todas as dependências, agora você já pode executar a aplicação através do comando: 
```bash
  yarn start
```

<br />

## 🛠️ Bibliotecas e Linguagens

<br />

 * [Axios](https://axios-http.com/docs/intro) - O Axios é um cliente HTTP baseado-em-promessas para o node.js e para o navegador. É isomórfico (= pode rodar no navegador e no node.js com a mesma base de código). No lado do servidor usa o código nativo do node.js - o modulo http, enquanto no lado do cliente (navegador) usa XMLHttpRequests;
 * [MirageJS](https://miragejs.com/) - Mirage JS é uma biblioteca JavaScript que permite simular APIs que podem ser usadas para construir, testar e compartilhar um aplicativo JavaScript full-stack;
 * [React](https://pt-br.reactjs.org/) - O React é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário em páginas web;
 * [Styled Components](https://styled-components.com/) - Styled Components é uma biblioteca que utiliza o conceito de CSS-in-JS, ou seja, que nos permite escrever códigos CSS dentro do Javascript. Criando códigos dessa forma, podemos reaproveitar o CSS de um website de forma mais rápida e ainda escrevê-lo sem revezar entre estilos diferentes de escrita;
 * [Typescript](https://www.typescriptlang.org/) - O Typescript é uma linguagem de código aberto desenvolvida pela Microsoft que foi construída em cima do Javascript, que é muito difundido atualmente. Esse “superset” foi criado para adicionar recursos de tipagem estáticas à linguagem original.
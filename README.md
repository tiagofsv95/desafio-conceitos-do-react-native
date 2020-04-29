<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://www.linkedin.com/in/tiago-felipe-sanches-vieira-457764139/r">
    <img alt="Made by Tiago Felipe" src="https://img.shields.io/badge/made%20by-Tiago%20Felipe-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, foi proposto continuar desenvolvendo a aplicação que irá armazenar repositórios, que você já foi desenvolvido no [desafio NodeJS](https://github.com/tiagofsv95/desafio-conceitos-node) e no [desafio ReactJS](https://github.com/tiagofsv95/desafio-conceitos-reactjs).

Para executar o projeto e necessario ter os repositorios citados acima clonado e rodando, pois **é o backend desta aplicação**. Depois basta dar um `git clone https://github.com/tiagofsv95/desafio-conceitos-do-react-native.git` no seu console e depois `yarn` para instalar as dependencias. Depois de instalar todas as dependencias basta executar `yarn react-native run-android`. Para isso é necessario ter um simulador de android em sua maquina.

## Ferramentas utilizadas na aplicação

-**react**;

-**react-native**;

-**axios**;


### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ❤️ by Tiago Felipe

# Netflix

> **Projeto acadêmico de simulação de documentação do aplicativo Netflix.**

Este repositório foi criado para uma atividade acadêmica sobre documentação de software utilizando **GitHub** e **Markdown**.

Nesta simulação, nosso grupo representa a equipe responsável pelo desenvolvimento do aplicativo **Netflix**.

---

## Sumário

- [Descrição](#descrição)
- [Público-alvo](#público-alvo)
- [Funcionalidades](#funcionalidades)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Requisitos técnicos](#requisitos-técnicos)
- [Desenvolvedores](#desenvolvedores)
- [Fontes](#fontes)

---

## Descrição

A **Netflix** é um serviço de entretenimento por assinatura que permite assistir a filmes, séries e outros conteúdos através da internet.

O aplicativo oferece uma experiência personalizada para cada usuário, permitindo pesquisar conteúdos, receber recomendações, criar perfis e assistir aos títulos disponíveis por meio de *streaming*.

A plataforma pode ser utilizada em diferentes dispositivos compatíveis, como:

- Smartphones;
- Tablets;
- Smart TVs;
- Computadores;
- Aparelhos de streaming;
- Videogames compatíveis.

### Para que serve?

O aplicativo Netflix é utilizado principalmente para consumir conteúdos de entretenimento sob demanda.

Por meio dele, o usuário pode escolher **o que deseja assistir e quando deseja assistir**, sem depender de uma programação fixa de televisão.

### Quando deve ser utilizado?

O aplicativo pode ser utilizado sempre que o assinante quiser acessar o catálogo da Netflix por meio de um dispositivo compatível e, para transmissões online, possuir conexão com a internet.

Alguns conteúdos também podem ser baixados em dispositivos compatíveis para serem assistidos posteriormente sem conexão.

---

## Público-alvo

O público-alvo da Netflix é formado por pessoas que procuram consumir **entretenimento digital sob demanda**.

A plataforma atende diferentes faixas etárias e tipos de público por meio de recursos como:

- Perfis individuais;
- Perfis infantis;
- Recomendações personalizadas;
- Diferentes idiomas;
- Legendas;
- Recursos de acessibilidade;
- Diferentes categorias de conteúdo.

---

## Funcionalidades

### Reprodução de conteúdo

O aplicativo permite reproduzir filmes, séries e outros conteúdos disponíveis no catálogo através de *streaming*.

### Pesquisa

O usuário pode pesquisar conteúdos disponíveis na plataforma e navegar entre diferentes categorias.

### Recomendações personalizadas

A Netflix possui sistemas de recomendação que ajudam cada usuário a encontrar conteúdos relacionados aos seus interesses.

As recomendações podem considerar fatores como:

- Conteúdos assistidos;
- Interações do usuário;
- Preferências do perfil;
- Características dos títulos;
- Comportamento de outros usuários com interesses semelhantes.

### Perfis

Uma conta pode possuir diferentes perfis.

Cada perfil pode apresentar sua própria experiência, incluindo:

- Recomendações;
- Histórico de visualização;
- Preferências;
- Minha Lista;
- Progresso de reprodução.

### Minha Lista

O recurso **Minha Lista** permite salvar títulos que o usuário pretende assistir posteriormente.

### Continuar assistindo

A Netflix registra o progresso de reprodução para permitir que o usuário continue um filme ou episódio a partir do ponto em que parou.

### Downloads

Em dispositivos compatíveis, determinados conteúdos podem ser baixados para serem assistidos sem conexão com a internet.

### Legendas e idiomas

Dependendo do título, o usuário pode selecionar diferentes opções de:

- Áudio;
- Idioma;
- Legendas;
- Legendas ocultas.

### Picture-in-Picture

Em dispositivos compatíveis, o recurso *Picture-in-Picture* permite continuar assistindo ao conteúdo em uma pequena janela enquanto outro aplicativo é utilizado.

### Jogos

A Netflix também disponibiliza jogos para dispositivos compatíveis como parte de seu ecossistema de entretenimento.

---

## Tecnologias utilizadas

> **Observação:** a Netflix possui uma infraestrutura de grande escala e diferentes versões de seus aplicativos para diversos dispositivos. Portanto, as tecnologias apresentadas abaixo são tecnologias oficialmente documentadas pela Netflix em sua plataforma e engenharia e não significam que todas sejam utilizadas simultaneamente em todas as versões do aplicativo.

### Node.js

A Netflix documenta o uso de **Node.js** no desenvolvimento de aplicações e serviços relacionados às suas interfaces.

`Node.js` permite executar código JavaScript fora do navegador e pode ser utilizado na construção de serviços que dão suporte às aplicações.

### React

A Netflix também documenta o uso de **React** na criação de interfaces de usuário.

React permite construir interfaces utilizando componentes reutilizáveis.

### RxJS

A plataforma utiliza **RxJS** em aplicações relacionadas à interface.

A biblioteca trabalha com o conceito de programação reativa e processamento de eventos assíncronos.

### Java e JVM

A engenharia da Netflix também utiliza tecnologias do ecossistema **Java/JVM** em diferentes serviços de sua infraestrutura.

### Cassandra

O **Apache Cassandra** é uma das tecnologias de banco de dados distribuído utilizadas pela Netflix.

Esse tipo de banco de dados é adequado para aplicações que precisam trabalhar com grandes quantidades de informações e alta disponibilidade.

### MySQL

A Netflix também documenta a utilização de **MySQL** entre suas tecnologias de persistência de dados.

### Redis

O **Redis** é utilizado em partes da infraestrutura relacionadas ao armazenamento e acesso rápido a dados.

### Amazon Web Services — AWS

A Netflix utiliza serviços de computação em nuvem da **Amazon Web Services (AWS)** em sua infraestrutura.

A computação em nuvem permite que os sistemas sejam distribuídos e dimensionados de acordo com a demanda.

### Netflix Open Connect

A Netflix possui sua própria infraestrutura de distribuição de conteúdo chamada **Open Connect**.

O Open Connect funciona como uma **CDN — Content Delivery Network** e ajuda a entregar os conteúdos da plataforma de forma eficiente aos usuários.

De maneira simplificada:

```text
Usuário
   |
   v
Aplicativo Netflix
   |
   v
Serviços da Netflix
   |
   v
Infraestrutura em nuvem
   |
   v
Netflix Open Connect
   |
   v
Reprodução do conteúdo
```

O Open Connect permite aproximar os conteúdos dos provedores de internet e, consequentemente, dos usuários que irão reproduzi-los.

---

## Requisitos técnicos

Os requisitos podem variar conforme o dispositivo utilizado.

### Android

Para utilizar a versão mais recente do aplicativo Netflix em celulares e tablets Android, é necessário:

- Android 9 ou superior;
- Dispositivo compatível;
- Aplicativo Netflix;
- Conta Netflix;
- Conexão com a internet para streaming.

Para realizar downloads, também é necessário espaço de armazenamento disponível.

### iPhone e iPad

Para utilizar a versão mais recente do aplicativo Netflix:

- iOS 18 ou superior no iPhone; ou
- iPadOS 18 ou superior no iPad;
- Dispositivo compatível;
- Aplicativo Netflix;
- Conta Netflix;
- Conexão com a internet para streaming.

### Outros dispositivos

A Netflix também está disponível em diversos outros dispositivos compatíveis, incluindo:

- Smart TVs;
- Computadores;
- Videogames;
- Dispositivos de streaming;
- Decodificadores compatíveis.

Os requisitos podem variar de acordo com o fabricante, modelo, sistema operacional e versão do aplicativo.

---

## Desenvolvedores

Nesta **simulação acadêmica**, os integrantes abaixo representam a equipe responsável pelo desenvolvimento do aplicativo Netflix:

1. **Luccas Machado Soares**
2. **Nome completo do integrante 2**
3. **Nome completo do integrante 3**
4. **Nome completo do integrante 4**
5. **Nome completo do integrante 5**
6. **Nome completo do integrante 6**
7. **Nome completo do integrante 7**
8. **Nome completo do integrante 8**

---

## Fontes

As informações apresentadas neste README foram pesquisadas em fontes oficiais relacionadas à Netflix:

- **Netflix Help Center**
- **Netflix Open Source Software Center**
- **Netflix Technology Blog**
- **Netflix Open Connect**
- **About Netflix**

As tecnologias apresentadas correspondem às informações disponibilizadas oficialmente pela empresa sobre sua plataforma, infraestrutura e engenharia.

---

## Sobre este repositório

Este repositório foi desenvolvido exclusivamente para uma **atividade acadêmica de simulação de documentação de software**.

O grupo **não possui vínculo com a Netflix** e não participou do desenvolvimento real da plataforma.

> **Netflix e suas marcas relacionadas pertencem à Netflix, Inc.**

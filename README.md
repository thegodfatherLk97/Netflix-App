# Netflix

![Logo da Netflix](images/Netflix-Logo%281%29.png)

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

O aplicativo Netflix é utilizado principalmente para consumir **conteúdos de entretenimento sob demanda**.

Por meio dele, o usuário pode escolher **o que deseja assistir e quando deseja assistir**, sem depender de uma programação fixa de televisão.

### Quando deve ser utilizado?

O aplicativo pode ser utilizado sempre que o assinante quiser acessar o catálogo da Netflix por meio de um dispositivo compatível.

Para transmissões por *streaming*, é necessária uma conexão com a internet. Alguns conteúdos também podem ser baixados em dispositivos compatíveis para serem assistidos posteriormente sem conexão.

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
- Comportamentos de usuários com interesses semelhantes.

### Perfis

Uma conta pode possuir diferentes perfis, permitindo uma experiência personalizada para cada usuário.

![Tela de perfis da Netflix](images/Perfis%281%29.jpg)

*Exemplo da tela de seleção e gerenciamento de perfis.*

Cada perfil pode possuir sua própria experiência, incluindo:

- Recomendações;
- Histórico de visualização;
- Preferências;
- Minha Lista;
- Progresso de reprodução.

### Minha Lista

O recurso **Minha Lista** permite salvar títulos que o usuário pretende assistir posteriormente.

![Minha Lista da Netflix](images/Minha_Lista%281%29.jpg)

*Exemplo da funcionalidade Minha Lista.*

### Continuar assistindo

A Netflix registra o progresso de reprodução para permitir que o usuário continue um filme ou episódio a partir do ponto em que parou.

![Continuar assistindo](images/Continuar_assistindo%281%29.jpg)

*Exemplo da funcionalidade Continuar assistindo e das recomendações personalizadas.*

### Downloads

Em dispositivos compatíveis, determinados conteúdos podem ser baixados para serem assistidos sem conexão com a internet.

### Legendas e idiomas

Dependendo do título, o usuário pode selecionar diferentes opções de:

- Áudio;
- Idioma;
- Legendas;
- Legendas ocultas;
- Audiodescrição, quando disponível.

![Idiomas e legendas](images/Legendas_Idiomas%281%29.jpg)

*Exemplo das opções de áudio e legendas disponíveis durante a reprodução.*

### Picture-in-Picture

Em dispositivos compatíveis, o recurso *Picture-in-Picture* permite continuar assistindo ao conteúdo em uma pequena janela enquanto outro aplicativo é utilizado.

### Jogos

A Netflix também disponibiliza jogos para dispositivos compatíveis como parte de seu ecossistema de entretenimento.

---

## Tecnologias utilizadas

> **Observação:** a Netflix possui uma infraestrutura de grande escala e diferentes versões de seus aplicativos para diversos dispositivos. As tecnologias abaixo são oficialmente documentadas pela engenharia da Netflix, mas isso não significa que todas sejam utilizadas simultaneamente em todas as versões do aplicativo.

### Java e JVM

A engenharia da Netflix utiliza tecnologias do ecossistema **Java/JVM** em diferentes serviços de sua infraestrutura.

![Java](images/Java_Logo.png)

O Java é utilizado em serviços de backend e em sistemas distribuídos responsáveis por diferentes operações da plataforma.

### Apache Cassandra

O **Apache Cassandra** é um banco de dados distribuído utilizado pela Netflix em aplicações críticas.

![Apache Cassandra](images/Apache_Cassandra.png)

A própria Netflix documenta o uso do Cassandra em sistemas relacionados a áreas como:

- Membros;
- Cobrança;
- Recomendações;
- Assinaturas.

Sua arquitetura distribuída permite trabalhar com grandes volumes de dados e alta disponibilidade.

### Apache Kafka

O **Apache Kafka** é uma plataforma distribuída utilizada para processamento e transmissão de eventos entre diferentes sistemas.

![Apache Kafka](images/Kafka_apache.png)

A Netflix documenta o uso do Kafka em partes de sua infraestrutura para comunicação entre serviços e processamento de eventos.

### MySQL

O **MySQL** também aparece em sistemas e projetos documentados pela engenharia da Netflix.

![MySQL](images/MySQL.png)

É um sistema de gerenciamento de banco de dados relacional utilizado para armazenar e organizar informações estruturadas.

### Machine Learning

A Netflix utiliza técnicas de **Machine Learning** em diferentes partes de sua plataforma, principalmente para personalização da experiência do usuário.

Entre suas aplicações estão:

- Recomendações de filmes e séries;
- Personalização da página inicial;
- Organização e classificação de conteúdos;
- Identificação de conteúdos relevantes para cada perfil.

O objetivo é apresentar ao usuário títulos com maior probabilidade de corresponder aos seus interesses.

---

## Requisitos técnicos

Os requisitos podem variar conforme o dispositivo utilizado.

### Android

Para utilizar a versão mais recente do aplicativo Netflix em celulares e tablets Android, é necessário:

- Android 9 ou superior;
- Dispositivo compatível;
- Aplicativo Netflix;
- Conta Netflix;
- Conexão com a internet para *streaming*.

Para realizar downloads, também é necessário espaço de armazenamento disponível.

### iPhone e iPad

Para utilizar a versão mais recente do aplicativo Netflix, é necessário:

- iOS 18 ou superior no iPhone; ou
- iPadOS 18 ou superior no iPad;
- Dispositivo compatível;
- Aplicativo Netflix;
- Conta Netflix;
- Conexão com a internet para *streaming*.

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

- [Netflix](https://www.netflix.com/)
- [About Netflix](https://about.netflix.com/)
- [Netflix Help Center](https://help.netflix.com/)
- [Netflix Technology Blog](https://netflixtechblog.com/)
- [Netflix Open Source Software Center](https://netflix.github.io/)
- [Netflix Open Connect](https://openconnect.netflix.com/)

### Referências técnicas

- [The Evolution of Cassandra Data Movement at Netflix](https://netflixtechblog.com/the-evolution-of-cassandra-data-movement-at-netflix-6e13329c80a1)
- [Learning a Personalized Homepage](https://netflixtechblog.com/learning-a-personalized-homepage-aa8ec670359a)
- [Simone — A Distributed Simulation Service](https://netflixtechblog.com/https-medium-com-netflix-techblog-simone-a-distributed-simulation-service-b2c85131ca1b)

As tecnologias apresentadas correspondem às informações disponibilizadas oficialmente pela empresa sobre sua plataforma, infraestrutura e engenharia.

---

## Sobre este repositório

Este repositório foi desenvolvido exclusivamente para uma **atividade acadêmica de simulação de documentação de software**.

O grupo **não possui vínculo com a Netflix** e não participou do desenvolvimento real da plataforma.

> **Netflix e suas marcas relacionadas pertencem à Netflix, Inc.**

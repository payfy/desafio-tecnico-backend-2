# Desafio Técnico Payfy
Nesse desafio, você vai ter que criar uma API REST para controle de usuarios no sistema

### Descrição da Aplicação
Nesse app você vai criar uma RESTful API, aonde o usuario pode se registrar e criar um time de pokemons, os pokemons tem q ser alimentados ou eles desmaiam(estilo tamagoshi).

### Funcionalidades obrigatórias
* criar o projeto em um repositorio aonde o examinador possa acessar(publico ou adicionar o examinador como contribuidor do repo)
* consumir a PokeAPI (https://pokeapi.co/docs/v2#pokemon)
* Poder criar um pokemon baseado no id dele(deve ser salvo o nome do pokemon)
* poder buscar seu time ou um pokemon especifico
* poder alimentar o pokemon
* cada vez que um pokemon é alimentado sua fome deve diminuir em 20, nunca pode ter menos que zero de fome
* a fome do pokemon deve aumentar em 1 por cada minuto sem ser alimentado, se a fome chegar a 150 o pokemon desmaia e não pode mais ser alimentado

### Funcionalidades não obrigatórias, porem legal de se ter
* arquivo de testes
* documentação das rotas
* DockerFile da aplicação
* estar rodando em um servidor publico para teste
* ser em elixir/phoenix

### Observações
* Qualquer duvida você pode ou perguntar para quem lhe passou o desafio, ou assumir a resposta e documentar todas suas assunções no read-me do seu projeto

### Critérios de avaliação
* código está bem estruturado
* código faz o uso correto de Design Patterns
* sabe explicar o motivo das decisões de implementações
* o projeto realiza todas as funcionalidades básicas requeridas
* o README do projeto tem todos os detalhes que precisam para rodar o projeto em outro computador

### Sugestão de Estudo
* [Clean Code - Guia e Exemplos](https://balta.io/artigos/clean-code)
* [Elixir School - Lições sobre a linguagem de programação Elixir](https://elixirschool.com/pt/)

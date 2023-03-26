
# Bem vindo ao desafio DevOps

Esse desafio se encaixa como júnior. Não será necessario saber como mexer nas linguagens do projeto, apenas ler sobre como é feito o build no readme e aplicar no CI do github actions ou plataforma que preferir

# Requisitos para desafio

1. Conta aws free tier
	* Link de ajuda para criar sua conta: https://www.youtube.com/watch?v=DQj8_yZsH_E
2. Conhecimento de logica de programação
3. Escolher um dos projetos para realizar o desafio
	* Back end: [Projeto php symfony](a)
	* Front end: [Projeto react js](a)
4. Docker para conteiners
5. Plataforma de CI (github actions, azure pipeline, aws codebuild e etc... Escolha uma)
6. Terraform ou ansible ( automatização de cloud e maquinas )

## Como realizar o desafio

### Amazon web service
Primeiramente, você vai precisar de uma conta free tier na AWS e saber como automatizar, pois iremos utilizar dentro da Orange Labs BR. A automatização pode ser feita com Terraform. Se você não souber utilizar o Terraform, podemos te passar um mini-curso simples de 1 hora. O mini-curso deve ser requisitado para a pessoa que te enviou o desafio.

##### Obs: Da mesma maneira que nos próximos avisos, não precisa usar módulos e coisas mais avançadas. Iremos te ajudar quando entrar na empresa.

### Back-end php
Se você entrar no projeto, terá outro `readme.md` que explicará o básico de build e outras coisas. O que eu, autor do desafio, quero que crie um `Dockerfile`. Se não souber criar, pesquise no youtube "dockerfile example" para ter uma base e consulte a documentação.

##### Obs: Não é necessário que o `Dockerfile` esteja perfeito com multi-stage, otimização ou outras coisas avançadas, apenas que esteja funcionando. Mas se não estiver completo, envie mesmo assim que vamos analisar.

### Front end react js
Do mesmo modo do back-end, no projeto de front-end, você terá que fazer o `build` manual e outras coisas do tipo. No final, você deve criar a imagem Docker e levantar a máquina com Docker.

### Considerações
Dentro do CI realizado, enviar a imagem Docker para um Docker Hub. Mas se não conseguir, avisa para te auxiliar.

## Critérios de avaliação

### O desafio será avaliado com base em:

* Funcionalidade da automação do build
* Conhecimento das ferramentas e como foi utilizadas
* Imagem docker criada

Boa sorte e divirta-se!

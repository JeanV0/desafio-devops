
# Bem-vindo ao desafio DevOps para a posição de júnior

Este desafio é destinado a candidatos que sejam iniciantes na área e não é necessário ter conhecimento prévio das linguagens utilizadas nos projetos. O objetivo é ler sobre como é feito o build no README e aplicar no CI do Github Actions ou na plataforma de sua preferência.

# Requisitos para desafio

1. Conta aws free tier
	* Para criar a conta, você pode seguir o tutorial disponível em: https://www.youtube.com/watch?v=DQj8_yZsH_E
2. Conhecimento básico de lógica de programação e sistemas
3. Plataforma de CI/CD (Github Actions, Azure Pipeline, AWS CodeBuild, etc. Escolha uma)
4. Terraform para cloud

## Como realizar o desafio

### Amazon web service e terraform
Primeiramente, você vai precisar de uma conta free tier na AWS e saber como automatizar, pois iremos utilizar dentro da Orange Labs BR. A automatização pode ser feita com Terraform. Se você não souber utilizar o Terraform, podemos te passar um mini-curso simples de 1 hora. O mini-curso deve ser requisitado para a pessoa que te enviou o desafio.
###
Os codigos do terraform deverá estar dentro da pasta `terraform`.
### Passos:
1. Criar um sistema no terraform que levante 1 maquina ec2
2. Cria um grupo de segurança para ssh para a maquina
3. Amazenar estado do terraform com opcao backend na S3 ou aonde preferir (tfstate)
4. Implementar esse sistema via CI no github actions para automatizar

### Considerações
Se tiver com problemas com alguma coisa e não acha a solução, manda uma pergunta que podemos dar uma dica ou alguma coisa

## Critérios de avaliação

### O desafio será avaliado com base em:

* Funcionalidade da automação do build
* Conhecimento das ferramentas e como foi utilizadas
* Codigo terraform realizado 

Boa sorte e divirta-se!

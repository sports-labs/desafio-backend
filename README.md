# Desafio Back-end Sports A&T

Primeiramente, agradecemos pelo seu interesse em fazer parte da nossa equipe. Somos uma empresa de tecnologia especializada no mercado de iGaming, com um foco total no desenvolvimento de software de alta qualidade.

## Antes de começar

Para iniciar o desafio, siga estas etapas:

1. Crie um repositório no seu GitHub, mas não mencione nada relacionado ao desafio.
2. Faça commits no seu repositório à medida que avança no desenvolvimento.
3. Familiarize-se com o processo de entrevista.
4. Não hesite em perguntar qualquer dúvida aos recrutadores.

Envie um e-mail com as seguintes informações:

- Seu nome - Desafio Técnico
- Link do repositório no GitHub
- Link do seu perfil no LinkedIn

## Ambiente da aplicação

Você tem a liberdade de escolher a tecnologia com a qual se sente mais confortável para trabalhar, pois não temos exigências específicas a esse respeito. No entanto, evite o uso excessivo de métodos prontos ou "mágicos". Valorizamos muito a organização do código.

## Entrevista técnica

Na data agendada para a entrevista, certifique-se de que a aplicação está funcionando na sua máquina. Realizaremos testes e validações, revisando o código juntos, como se você já fosse parte da equipe.

## Objetivo: API de Livescores

Na Sports A&T, nosso principal foco é fornecer dados de eventos ao vivo, como partidas de futebol, por exemplo. Portanto, seu desafio é desenvolver uma aplicação simplificada que forneça esses dados.

Normalmente, nossa aplicação recebe dados através de brokers, mas, para simplificar este desafio, consideraremos o recebimento de dados por meio de requisições HTTP.

Requisitos:

- Cada evento possui N participantes, cada um com nome, link da imagem e ID.
- Além disso, cada competição possui os mesmos atributos.
- Os eventos têm informações como horário de início, ID e status (ao vivo, a iniciar e finalizado).
- IDs não podem se repetir.
- A aplicação deve fornecer dados de eventos ao vivo.
- A aplicação deve fornecer dados de eventos por data.
- A aplicação deve fornecer dados de eventos finalizados por data.
- A aplicação deve ser capaz de receber dados para popular os eventos.
- Este serviço deve ser implementado de acordo com os princípios RESTful.

Faça uma proposta de payload para a rota POST /events, por exemplo:

POST /events
```json
{
  "id": "1321",
  "teamA": {...},
  "teamB": {...},
  "competition": {...},
  ...
}
```

## Avaliação

Apresente sua solução usando o framework de sua escolha, justificando a escolha. Certifique-se de atender à maioria dos requisitos, pois a avaliação considerará tanto o cumprimento completo quanto parcial deles.

O que será avaliado e valorizado:

- Documentação completa e clara.
- Se você está se candidatando a uma vaga sênior, foque no desenho da arquitetura.
- Código limpo e bem organizado, incluindo a nomenclatura.
- Demonstração de conhecimento de padrões como PSRs, design patterns e princípios SOLID.
- Coerência nas escolhas feitas e habilidade para justificá-las.
- Modelagem de dados eficaz.
- Manutenibilidade do código.
- Tratamento adequado de erros.
- Considerações de segurança.
- Uma arquitetura bem pensada antes da implementação.
- Esforço em desacoplar componentes, usando camadas como service e repository.

Com base nos critérios acima, avaliaremos o seu teste para decidir se avançaremos para a entrevista técnica. Caso não atinja um nível aceitável nessas áreas, o processo não prosseguirá.

O que **NÃO** será avaliado ⚠️:

- Frontend.
- Autenticação.

O que será um diferencial:

- Uso de Docker.
- Implementação de testes de integração e unitários.
- Aplicação de Design Patterns.
- Documentação completa.
- Propostas de melhorias na arquitetura.

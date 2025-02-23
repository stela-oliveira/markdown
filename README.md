# Metodologias Ágeis e Scrum

## Introdução às Metodologias Ágeis
As metodologias ágeis surgiram como uma alternativa aos modelos tradicionais de desenvolvimento de software, como o modelo cascata. Elas enfatizam a *flexibilidade*, **colaboração** e entrega contínua de valor ao cliente.

> "A melhor maneira de prever o futuro é criá-lo." — Peter Drucker

### Princípios do Manifesto Ágil
O Manifesto Ágil foi criado em 2001 e define quatro valores principais:

| **Valor Ágil** | **Descrição** |
|--------------|-------------|
| **Indivíduos e interações** | Mais que processos e ferramentas |
| **Software em funcionamento** | Mais que documentação abrangente |
| **Colaboração com o cliente** | Mais que negociação de contratos |
| **Responder a mudanças** | Mais que seguir um plano |

Além disso, apresenta 12 princípios que guiam as práticas ágeis, como entregas frequentes, colaboração entre equipes e adaptação contínua. Para mais detalhes, consulte o blog [Manifesto Ágil: entenda como surgiu e conheça os 12 princípios](https://robsoncamargo.com.br/blog/Manifesto-Agil-entenda-como-surgiu-e-conheca-os-12-principios).

### O Conceito do The Heart Of Agile
_COLABORAR_ &rarr _ENTREGAR_ &rarr _REFLETIR_ &rarr _ MELHORAR!_

## Scrum
O **Scrum** é uma das metodologias ágeis mais utilizadas. Ele é baseado em ciclos iterativos chamados **Sprints**, que geralmente duram de 1 a 4 semanas.

### Papéis no Scrum
- **Scrum Master**: responsável por garantir que a equipe siga os princípios do Scrum e remover impedimentos.
- **Product Owner (PO)**: responsável pelo backlog do produto e por definir as prioridades.
- **Equipe de Desenvolvimento**: equipe responsável pela implementação das tarefas dentro do Sprint.

### Artefatos do Scrum

| **Artefato** | **Descrição** |
|-------------|-------------|
| **Product Backlog** | Lista priorizada de funcionalidades e melhorias a serem desenvolvidas. |
| **Sprint Backlog** | Conjunto de itens do Product Backlog selecionados para serem desenvolvidos no Sprint atual. |
| **Incremento** | Entrega de valor ao final de cada Sprint, garantindo software funcional. |

### Eventos do Scrum
1. **Sprint Planning**: reunião para definir quais itens do backlog serão trabalhados no Sprint.
1. **Daily Scrum**: reunião diária para alinhamento do time sobre o progresso e impedimentos.
1. **Sprint Review**: apresentação do que foi desenvolvido no Sprint para stakeholders.
1. **Sprint Retrospective**: reunião para análise do que funcionou bem e o que pode ser melhorado no próximo Sprint.

## Benefícios do Scrum
- __*Maior adaptabilidade às mudanças.*__
- __*Entregas contínuas e frequentes.*__
- __*Melhor colaboração entre equipes e stakeholders.*__
- __*Transparência no processo de desenvolvimento.*__

## Implementação do Scrum
- [x] Definir o **Scrum Master**, **Product Owner** e **Equipe de Desenvolvimento**
- [x] Criar e priorizar o **Product Backlog**
- [x] Planejar o **Sprint Backlog**
- [x] Realizar reuniões diárias (**Daily Scrum**)
- [x] Revisar o progresso ao final do Sprint (**Sprint Review**)
- [x] Refletir sobre melhorias no processo (**Sprint Retrospective**)

## Exemplo de Backlog no Scrum (Código YAML)
```yaml
backlog:
  - id: 1
    título: "Implementar login de usuário"
    prioridade: alta
  - id: 2
    título: "Criar tela de dashboard"
    prioridade: média
```

## Imagem Representativa do Scrum
![Scrum Framework](https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Scrum_process.svg/1200px-Scrum_process.svg.png)

## Conclusão
O **Scrum** é uma abordagem ágil eficaz para desenvolvimento de software, garantindo entregas rápidas e iterativas, além de promover a colaboração e melhoria contínua. Seu uso adequado pode levar a produtos de maior qualidade e maior satisfação do cliente.

Para mais informações sobre Scrum, acesse a [guia oficial do Scrum](https://www.scrum.org/resources/scrum-guide).
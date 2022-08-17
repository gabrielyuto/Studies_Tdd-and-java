# 🧪 TDD e Java: testes automatizados com JUnit

Este repositório contém os principais pontos abordados durante o curso "TDD e Java: testes automatizados com JUnit" que realizei junto à plataforma da Alura.
Inclusive, valeu Alura!

Além de uma contextualização inicial sobre a parte de testes automatizados em Java (repositório JUnit), temos um projeto que simula um sistema de folha de pagamento de Recursos Humanos que orientou os estudos dos testes (repositório TDD-sistema-folha-pagamentos).

Assim, foi posível testar classes, utilizar as anotações de testes, assetivas, e também utilizar a abordagem TDD (Desenvolvimento Guiado por Teste) e o refactoring na aplicação!

Aqui deixo também algumas notas de aula pessoais e do próprio curso para guiar os estudos com testes em Java!

## 📘 Notas:

Testes Manuais:

- Chatos, lentos e sujeito a falhas (fator humano).

Testes automatizados:

- Automatização.
- Feedback mais rápido.
- Segurança ao mexer no código.
- Favorece a melhoria do código (refactoring).

JUnit:

- Biblioteca padrão para escrita de testes automatizados em Java.
- Criado em 1995 por Kent Beck (pai dos testes automatizados) e Erich Gamma (um dos autores do livro Design Patterns).
- Gratuito e open source (https://github.com/junit-team/junit5).
- Foco em testes de unidade (testes unitários).

### Test Driven Development (TDD)

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/62525280/185215074-053289f2-934d-48bf-9cd5-18b274945242.png">
</p>


- Código já sai "testado”.
- Evita testes "viciados" na implementação.
- Refatoração faz parte do processo.
- Ajuda a manter o foco.
- Temos uma “tendência” em escrever um código mais simples.

**  O que testar na aplicação?  **

- Não devemos testar todas as classes. O que é importante testar são as classes que tenham regra de negócio e que possivelmente sofrerão bastante modificações.


# NutriCraft - Protocolo Nutracêutico

Repositório destinado à entrega da atividade prática da disciplina de **Modelos e Padrões de projeto** ministrada pela professora Cristiane Palomar.

## Sobre a Atividade
O objetivo deste trabalho foi desenvolver uma aplicação web para montagem e personalização de protocolos nutricionais e nutracêuticos, aplicando na prática os padrões de projeto **Builder** e **Prototype**. O sistema permite a construção passo a passo de uma dieta personalizada com base nos dados do usuário (padrão Builder) e a clonagem/utilização de templates de dietas pré-definidas (padrão Prototype), facilitando a criação, o armazenamento no histórico e a edição de novos protocolos.

## O que foi entregue neste repositório:
- **Interface Web (Front-end):** Código da página interativa (Painel Build e Painel Preview) para geração visual dos protocolos.
- **Lógica de Padrões de Projeto (JavaScript):** Implementação das classes `DietBuilder` (responsável pelo processo de construção e cálculo da dieta) e `NutraceuticDiet` com sua função de `.clone()` (responsável pela prototipação e clonagem).
- **Sistema de Gerenciamento:** Estrutura para manter o histórico de dietas criadas, permitindo que o usuário clone, visualize e edite as informações geradas (modal de edição).

## Tecnologias Utilizadas:
- HTML5 e CSS3
- JavaScript (Vanilla)

## Integrantes:
- Maria Julia Loureiro
- Sophia Araujo
- Rafaela Riganti

# Desenvolvimento de um Jogo no Estilo SimCity em C++

## Introdução

Este projeto tem como base os conceitos apresentados no livro *Aprendendo C++* de Tom Swan.

## Objetivos do Projeto

- Implementar um simulador de cidade utilizando C++.
- Aplicar conceitos de orientação a objetos, como herança e polimorfismo.
- Implementar um sistema de gestão de recursos (energia, água, dinheiro, etc.).
- Criar um sistema de crescimento populacional baseado nas ações do jogador.
- Implementar eventos dinâmicos como desastres naturais e variações climáticas.

## Estrutura do Jogo

O jogo será estruturado com base nos seguintes componentes:

### 1. **Classes Base**
- **Cidade:** A classe principal que gerencia os aspectos da cidade (população, recursos, infraestruturas).
- **Edificio:** Classe para representar os diferentes tipos de edifícios (residenciais, comerciais, industriais).
- **Recurso:** Representa os recursos gerenciados pela cidade, como água, eletricidade e finanças.
- **Jogador:** Responsável por armazenar informações sobre as ações e o progresso do jogador.

### 2. **Classes Derivadas**
- **Residencial, Comercial, Industrial:** Estas classes derivam de *Edificio* e representam os diferentes tipos de zonas que podem ser construídas.
- **CentralEnergia, EstacaoTratamentoAgua:** Classes específicas que derivam de *Recurso* para fornecer serviços essenciais à cidade.

## Conceitos Utilizados

- **Orientação a Objetos (OO):**
  O projeto será amplamente baseado em OO, utilizando princípios como encapsulamento, herança e polimorfismo para organizar e estruturar o código.

- **Herança e Polimorfismo:**
  As classes *Edificio* e *Recurso* servirão como bases para as diversas especializações, facilitando a expansão do jogo com novos tipos de edifícios e recursos.

- **Manipulação de Arquivos:**
  O estado do jogo será salvo e carregado por meio de arquivos, permitindo ao jogador salvar o progresso e continuar a cidade em outro momento.

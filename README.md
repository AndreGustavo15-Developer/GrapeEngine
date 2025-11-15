# 🍇 Grape Engine  
*Uma game engine modular escrita em Zig + C, inspirada na metáfora de um cacho de uvas.*

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![GitHub issues](https://img.shields.io/github/issues/AndreGustavo15-Developer/GrapeEngine.svg)](https://github.com/AndreGustavo15-Developer/GrapeEngine/issues)  
[![GitHub stars](https://img.shields.io/github/stars/AndreGustavo15-Developer/GrapeEngine.svg)](https://github.com/AndreGustavo15-Developer/GrapeEngine/stargazers)

---

## Sumário

- [🌱 Visão Geral](#-visão-geral)  
- [🍇 Filosofia Central](#-filosofia-central)  
- [🎯 Objetivo Inicial](#-objetivo-inicial)  
- [🛠️ Estado Atual do Projeto](#-estado-atual-do-projeto)  
- [📘 Documentação](#-documentação)  
- [📂 Estrutura Inicial do Repositório (proposta)](#-estrutura-inicial-do-repositório-proposta)  
- [🤝 Como Contribuir](#-como-contribuir)  
- [📄 Licença](#-licença)  
- [👤 Autor](#-autor)  
- [🌐 Futuro: Fundação](#-futuro-fundação)  

---

## 🌱 Visão Geral

A **Grape Engine** é uma engine de jogos em desenvolvimento, construída sobre o conceito de **modularidade orgânica**.  
Inspirada na metáfora de um *cacho de uvas*, cada módulo da engine — chamado de “baga” — funciona como uma parte independente, capaz de ser adicionada, removida ou modificada sem afetar o núcleo central.

O objetivo é criar uma engine que **cresce e evolui como um organismo**, permitindo que funcionalidades sejam cultivadas de maneira natural, flexível e escalável.

> **Status:** Design em desenvolvimento.  
> O TDD (Technical Design Document) está em constante evolução e o projeto ainda não possui uma arquitetura técnica final definida.

---

## 🍇 Filosofia Central

### 🌿 **Modularidade como cacho de uvas**
- Cada módulo é uma *baga* independente.  
- O núcleo funciona como o *pedúnculo* que conecta tudo.  
- Novas funcionalidades podem surgir sem desequilibrar o todo.  
- A engine deve amadurecer de forma orgânica, assim como um cacho real.

Essa filosofia é o único elemento **100% definido e estável** neste estágio do projeto.

---

## 🎯 Objetivo Inicial
 
- Definir uma arquitetura clara e profundamente modular.  
- Estabelecer um ecossistema que permita expansão natural e colaborativa.  
- Evoluir a engine para um futuro **projeto AAA open-source**.

---

## 🛠️ Estado Atual do Projeto

O projeto está em fase **pré-arquitetura**, com foco em:

- Estruturação da documentação  
- Desenvolvimento do TDD  
- Definição do núcleo conceitual  
- Planejamento da modularidade  
- Identidade e filosofia base da engine  

Ainda **não existe**:  
- ECS definido  
- Pipeline gráfico definido  
- Estrutura de código formal  
- Editor  
- Subsistemas (física, áudio etc.)  

Esses elementos serão definidos posteriormente no TDD.

---

## 📘 Documentação

A documentação será mantida dentro de:

```
/docs
/TDD
```

Atualmente, esta pasta contém (ou conterá) a versão inicial do TDD, que será expandida conforme o projeto evolui.

---

## 📂 Estrutura Inicial do Repositório (proposta)

```
GrapeEngine/
│
├── src/
│   ├── core/
│   │   └── mod.zig
│   ├── graphics/
│   │   └── mod.zig
│   └── ecs/
│       └── mod.zig
│
├── docs/
│   └── tdd/
│   └── TDD.md
│
├── examples/
│
└── (README.md, LICENSE, build.zig, ...)
```

> Esta estrutura pode mudar conforme o TDD evolui.

---

## 🤝 Como Contribuir

Neste estágio inicial, você pode ajudar com:

- Abrindo issues para discutir ideias e design  
- Propondo melhorias para a documentação e TDD  
- Enviando sugestões para a organização do projeto  

Quando a arquitetura estiver definida, receberemos contribuições técnicas e código.

**Por favor, antes de enviar PRs, abra uma issue para alinharmos a proposta!**

---

## 📄 Licença

**MIT License** — permitindo uso educacional, pessoal e comercial sem restrições.

---

## 👤 Autor

Criado e mantido por **[André Gustavo](https://github.com/AndreGustavo15-Developer)**, como projeto acadêmico com ambição de longo prazo para tornar-se um ecossistema open-source modular e orgânico.

---

## 🌐 Futuro: Fundação

No futuro, a engine poderá ser mantida pela:

**Grape Engine Foundation** *(nome preliminar)*

Com foco em governança, roadmap, padronização e sustentabilidade do projeto.

---

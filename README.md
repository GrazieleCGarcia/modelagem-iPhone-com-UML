# 📱 Projeto iPhone UML - (mermaidchart)

Este projeto simula as funcionalidades básicas de um iPhone de primeira geração, utilizando conceitos de **Programação Orientada a Objetos** em Java. O objetivo é demonstrar o uso de **interfaces** e **polimorfismo** para representar diferentes comportamentos de um dispositivo multifuncional.

---

## 🧩 Estrutura do Projeto

O projeto é composto por três interfaces principais:

### 🎵 `ReprodutorMusical`
Define métodos relacionados à reprodução de músicas:
- `tocar()`
- `pausar()`
- `selecionarMusica(String musica)`

### 📞 `AparelhoTelefonico`
Define métodos relacionados à funcionalidade de telefone:
- `ligar(String numero)`
- `atender()`
- `iniciarCorreioVoz()`

### 🌐 `NavegadorInternet`
Define métodos relacionados à navegação na web:
- `exibirPagina(String url)`
- `adicionarNovaAba()`
- `atualizarPagina()`

A classe `iPhone` implementa todas essas interfaces, simulando um dispositivo que pode executar múltiplas funções.

---

## 📐 Diagrama UML

Abaixo está o diagrama UML que representa a estrutura do projeto e a implementação das interfaces pela classe `iPhone`:

<img width="3840" height="1343" alt="Untitled diagram _ Mermaid Chart-2025-08-30-165414" src="https://github.com/user-attachments/assets/3e7dd600-0e6a-429d-820b-2264af25ebd0" />

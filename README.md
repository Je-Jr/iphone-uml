# Projeto de Implementação do Iphone

## Visão Geral

Este projeto fornece uma implementação básica de uma classe `Iphone` em Java, que integra funcionalidades de um reprodutor musical, um aparelho telefônico e um navegador de internet. A classe `Iphone` implementa três interfaces: `ReprodutorMusical`, `AparelhoTelefonico` e `NavegadorInternet`.

## Interfaces

### ReprodutorMusical

Esta interface define os métodos necessários para um reprodutor musical:

- `void tocar()`: Toca uma faixa de música.
- `void pausar()`: Pausa a faixa de música atual.
- `void selecionarMusica(String musica)`: Seleciona uma faixa de música específica.

### AparelhoTelefonico

Esta interface define os métodos necessários para um aparelho telefônico:

- `void ligar(String numero)`: Faz uma chamada para um número fornecido.
- `void atender()`: Atende uma chamada recebida.
- `void iniciarCorreioVoz()`: Inicia o correio de voz.

### NavegadorInternet

Esta interface define os métodos necessários para um navegador de internet:

- `void exibirPagina(String url)`: Exibe uma página web a partir de um link.
- `void adicionarNovaAba()`: Adiciona uma nova aba no navegador.
- `void atualizarPagina()`: Atualiza a página atual.

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- `Iphone.java`: Implementação da classe `Iphone` que integra as funcionalidades das três interfaces.
- `ReprodutorMusical.java`: Interface que define os métodos para o reprodutor musical.
- `AparelhoTelefonico.java`: Interface que define os métodos para o aparelho telefônico.
- `NavegadorInternet.java`: Interface que define os métodos para o navegador de internet.

## Como Executar

1. Clone o repositório para sua máquina local:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git

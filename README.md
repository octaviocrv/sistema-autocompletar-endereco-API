<h1 align="center"> Autocompletar Endereço por CEP </h1>


<img width="1142" height="628" alt="image" src="https://github.com/user-attachments/assets/838546f2-adaf-4c15-9a07-766892dca5da" />


<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/API_ViaCEP-000000?style=for-the-badge&logo=json&logoColor=white" alt="ViaCEP API" />
</p>

> Otimização de formulários e melhoria na experiência do usuário através do preenchimento automático de dados de endereço.

## Sobre o Projeto

Este projeto consiste no desenvolvimento de uma interface de cadastro focada em usabilidade e agilidade. A aplicação atua especificamente na etapa de endereço de um fluxo de checkout ou registro, utilizando a integração direta com a API pública ViaCEP.

Ao digitar um CEP brasileiro válido, o sistema intercepta os dados, realiza uma requisição assíncrona e preenche automaticamente os campos de endereço (Rua, Bairro, Cidade e Estado), reduzindo o esforço do usuário e as chances de abandono do formulário.

---

## Principais Funcionalidades

- **Preenchimento Automático:** Consumo da API para buscar os dados de localização de forma instantânea.
- **Validação de Entrada:** Verificação do padrão de 8 dígitos para o CEP antes de acionar a requisição.
- **Interface Intuitiva:** Design moderno em modo escuro (dark theme) focado na redução de atrito durante o cadastro.
- **Indicador de Progresso (Stepper):** Feedback visual indicando as etapas do processo (Criação de conta, Endereço e Pagamento).

---

## Tecnologias Utilizadas

A aplicação foi construída visando alta performance e execução no lado do cliente (Client-side), utilizando as linguagens fundamentais da web:

- **HTML5** — Estruturação semântica do formulário e dos campos de entrada de dados.
- **CSS3** — Estilização da interface, alinhamento de elementos e aplicação da paleta de cores.
- **JavaScript (Vanilla)** — Lógica de manipulação do DOM, eventos de teclado e requisições HTTP utilizando a `Fetch API`.
- **ViaCEP API** — Webservice gratuito e de alto desempenho para consulta de Códigos de Endereçamento Postal (CEP) do Brasil.

---

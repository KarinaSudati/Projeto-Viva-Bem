# 🩺 Viva Bem | Saúde Preventiva e Autocuidado

Página moderna e responsiva desenvolvida para promover a importância de exames de rotina e o autocuidado. Este projeto foi construído seguindo estritas diretrizes de layout, utilizando puramente **Flexbox** para toda a estruturação e garantindo a responsividade em diversos dispositivos.

---

## 🎯 Objetivo do Projeto

O principal objetivo deste desafio foi construir uma interface clara, acessível e acolhedora, denominada "Viva Bem", focada na saúde preventiva para homens e mulheres. O layout é harmonioso, utilizando cores que remetem ao bem-estar e uma tipografia de fácil leitura.

## ✨ Tecnologias e Metodologia

* **HTML5 Semântico:** Estrutura limpa e bem organizada.
* **SCSS (Sass):** Utilizado para pré-processamento, com foco em variáveis, aninhamento e organização modular para cores, tipografia e espaçamentos.
* **Flexbox:** **Obrigatório** para toda a estrutura de layout (Header, Cards, Alertas e Footer), garantindo alinhamento e distribuição sem o uso de `Grid` ou `Position`.
* **Responsividade:** Design adaptável a Mobile, Tablet e Desktop (utilizando `rem`, `vw/vh`, `%` e Media Queries).

## 🚀 Deploy e Visualização

Este projeto está hospedado e pode ser visualizado online:

| Plataforma | Link |
| :--- | :--- |
| **Página (Deploy)** | [https://projeto-viva-bem-gamma.vercel.app] |
| **GitHub** | [https://github.com/KarinaSudati/Projeto-Viva-Bem] |

---

## 💻 Estrutura do Layout

A página é dividida em seções principais, todas construídas usando o modelo Flexbox:

1.  **Header & Hero:** Barra de navegação com gradiente e banner principal com título e CTAs.
2.  **Importância:** Cards informativos sobre Detecção Precoce, Cuidado Familiar e Qualidade de Vida (Layout de 3 Colunas Flex).
3.  **Prevenção Feminina & Masculina:** Cards detalhados de exames de rotina por faixa etária (Layout de 3 Colunas Flex com `flex-wrap`).
4.  **Alertas Importantes:** Destaques sobre Autoexames, Vacinas e Saúde Mental (Layout de 2x2 Flex).
5.  **Footer:** Rodapé com três colunas (Links Úteis e Contato) e faixa de copyright (Layout de 3 Colunas Flex).

## 🧩 Regras do Desafio (Concluídas)

Todas as restrições e requisitos do desafio foram cumpridos com sucesso:

| Regra | Status | Detalhes |
| :--- | :--- | :--- |
| Uso de **Flexbox** | ✅ Concluído | Usado para todas as seções, incluindo cards e rodapé. |
| **Responsividade** | ✅ Concluído | Utilização de `rem`, `vw`, `%` e Media Queries. |
| Boas Práticas SCSS | ✅ Concluído | Uso de variáveis para cores, fontes e aninhamento. |
| **Proibição de Grid** | ✅ Concluído | Não foi utilizada a propriedade `display: grid;`. |
| **Proibição de Position** | ✅ Concluído | Não foram utilizadas `position: absolute`, `relative`, `fixed`, etc. |

---

## ⚙️ Como Executar Localmente

Para clonar e rodar o projeto em sua máquina:

1.  Clone o repositório:
    ```bash
    git clone [Link do seu repositório]
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd nome-do-projeto
    ```
3.  **Compile o SCSS:** Este projeto utiliza SCSS. Você precisará de um compilador (como o Live Sass Compiler no VS Code ou o CLI do SASS) para gerar o arquivo `style.css` a partir do `style.scss`.
4.  Abra o arquivo `index.html` em seu navegador.

---
*Desenvolvido por: Karina Sudati/ KarinaSudati

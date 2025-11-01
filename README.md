# Projeto IMPACTA+ – Plataforma de Engajamento Social

## Descrição do Projeto

A **IMPACTA+** é uma plataforma web desenvolvida para fortalecer o impacto social de ONGs que atuam nas áreas de educação, saúde e cidadania.

O sistema tem como objetivo facilitar o gerenciamento de projetos sociais, o engajamento de voluntários e a captação de doações, criando uma ponte entre pessoas e causas que transformam vidas.

Construído com **HTML5, CSS3 e JavaScript**, o projeto aplica os princípios de semântica, responsividade, acessibilidade e desempenho. A **Entrega II** focou na aplicação de um **Sistema de Design** robusto, utilizando **CSS Grid** e **Flexbox** para criar uma interface visual profissional, responsiva e compatível com qualquer dispositivo.

Acesse o site 🔗 [Versão publicada: https://glauberdias-tech.github.io/Atividade2_ong_impacta_mais](https://glauberdias-tech.github.io/Atividade2_ong_impacta_mais)

---

## Estrutura e Páginas do Projeto

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | Página inicial apresentando a missão, visão e valores da ONG IMPACTA+, com informações institucionais, histórico e contatos. |
| `projetos.html` | Apresenta os principais projetos sociais da organização em um layout de **Cards Responsivos**. |
| `cadastro.html` | Formulário completo para cadastro de voluntários e apoiadores, com validação HTML5 e máscaras automáticas de CPF, telefone e CEP. O layout utiliza **CSS Grid** para o posicionamento dos campos. |

### Estrutura de Pastas

impacta-plus/ │ ├── index.html ├── projetos.html ├── cadastro.html │ ├── css/ │ └── style.css # Arquivo principal de estilos (Layout, Componentes e Sistema de Design) │ ├── js/ │ └── masks.js # Script responsável pelas máscaras de CPF, Telefone e CEP │ ├── assets/ │ └── img/ # Imagens otimizadas (.webp) │ └── README.md # Documentação completa do projeto

---

## Tecnologias e Recursos Implementados (Atividade 2)

O design foi construído em um fluxo **Mobile-First**, garantindo que a experiência em dispositivos móveis seja priorizada, conforme as **Especificações Técnicas Obrigatórias** da entrega.

### 🎨 Sistema de Design & Estilização

* **Variáveis CSS Customizadas:** Utilizadas para definir o Sistema de Design.
* **Paleta de Cores:** Definida com tons de **Azul** (primária) e **Laranja** (secundária/acento), com no mínimo 8 variações.
* **Tipografia Hierárquica:** 5 tamanhos de fonte definidos (`xs`, `sm`, `md`, `lg`, `xl`) para garantir a hierarquia visual.
* **Espaçamento Modular:** Utilização de múltiplos de 8px (8, 16, 24, 32, 48, 64) para consistência.

### 📐 Leiautes Responsivos

* **Leiaute Principal:** Utiliza **CSS Grid** para a estrutura geral (como na página inicial) e **Flexbox** para componentes (como o Header).
* **Breakpoints:** Implementação de no mínimo 5 breakpoints responsivos.
* **Sistema de Cards:** A página de projetos exibe **Cards Responsivos** utilizando **CSS Grid** que se adaptam de 1 a 4 colunas.
* **Formulários Estilizados:** Utilizam **CSS Grid** e incluem **Validação Visual** (`:valid`, `:invalid`).

### 📱 Navegação Interativa

* **Menu Principal:** Navegação sofisticada e interativa, adaptável ao tamanho da tela.
* **Menu Hambúrguer (Mobile):** Implementado para navegação em dispositivos móveis, com transição CSS e acessibilidade (`aria-expanded`).

---

## Missão da IMPACTA+

A ONG IMPACTA+ atua para transformar vidas por meio da educação, saúde e cidadania, promovendo oportunidades que geram autonomia e dignidade. Acreditamos que o verdadeiro progresso nasce quando cada pessoa tem acesso ao conhecimento, ao cuidado e à participação ativa na sociedade. Por meio de projetos sociais, parcerias e ações sustentáveis, trabalhamos para construir um futuro mais justo, solidário e humano — um impacto que começa em cada indivíduo e se espalha pela comunidade.
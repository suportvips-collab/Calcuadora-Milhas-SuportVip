# ✈️ Calculadora de Milhas Suportvip

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Technology](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Styling](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success.svg)

**Simulador de Lucro Real** desenvolvido para agilizar, automatizar e trazer clareza financeira para operações de compra e venda de milhas aéreas. Focado na experiência do usuário e na precisão dos dados.

---

## 📋 Sobre o Projeto

Esta ferramenta é uma *Single Page Application* (SPA) leve e responsiva que permite simular cotações das principais companhias aéreas (Azul, Latam e Smiles). Diferente de calculadoras simples, este projeto foca no **Lucro Líquido Real**, permitindo dedução automática de impostos, gestão de CPFs (Pax) e alertas de conformidade.

O projeto reflete a missão da **Suportvip** de utilizar tecnologia e automação para garantir que processos operacionais fluam com o mínimo esforço possível.

## ✨ Funcionalidades Principais

* **🏢 Multi-Cia:** Suporte nativo para Azul, Latam e Smiles com identidade visual dinâmica.
* **🧮 Calculadora de Custo Avançada:**
    * Painel expansível para cálculo de CPM (Custo por Milheiro) baseado no valor do carrinho, pontuação total e bônus de transferência (%).
* **📊 Indicadores Financeiros em Tempo Real:**
    * Cálculo automático de Receita Bruta, Custo de Fabricação e Lucro Líquido.
    * Exibição da **Margem Real (%)** e valor de **Empate (Break-even)**.
* **⚖️ Configuração Fiscal:**
    * Opção de ativar/desativar cálculo de impostos.
    * Alíquota configurável (ex: 6% sobre o lucro).
* **👥 Gestão de Risco (Compliance):**
    * Monitoramento de média de milhas por CPF (Pax).
    * Alertas visuais para volumes de alto risco (>300k ou >360k por CPF).
* **💾 Persistência de Dados:** Salva automaticamente as últimas cotações e configurações no navegador (`localStorage`), permitindo retomar o trabalho de onde parou.
* **📱 Interface Otimizada:**
    * Design limpo utilizando **Tailwind CSS**.
    * Modo "Minimizado" para manter a calculadora discreta na tela enquanto trabalha em outras abas.
    * Geração de **Relatório Copiável** com um clique para envio rápido em CRMs ou WhatsApp.

## 🚀 Como Usar

Não é necessária nenhuma instalação complexa (Node.js, Python, etc), pois o projeto roda inteiramente no navegador via CDN.

### Opção 1: Rodar Localmente
1.  Baixe o arquivo `calculadora_suportvip.html`.
2.  Dê um duplo clique para abrir em seu navegador padrão (Chrome, Edge, Firefox).

### Opção 2: Hospedagem (GitHub Pages)
1.  Suba o arquivo HTML para este repositório com o nome `index.html`.
2.  Vá em **Settings** > **Pages**.
3.  Em "Source", selecione a branch `main`.
4.  Acesse o link gerado pelo GitHub.

## 🛠️ Tecnologias Utilizadas

* **HTML5 / JavaScript (Vanilla):** Lógica rápida e sem dependências pesadas.
* **Tailwind CSS (CDN):** Estilização moderna e responsiva.
* **Lucide Icons:** Ícones vetoriais leves para uma interface intuitiva.

## 📸 Estrutura do Relatório

A ferramenta gera relatórios automáticos formatados para colar no WhatsApp/Trello:

```text
✈️ Relatório Suportvip
📊 LATAM Pass

📦 Volume: 100k
👥 Pax: 1 CPFs (Média: 100.0k/pax)
💰 Lucro/Pax: R$ 100,00
...
💎 LUCRO LÍQUIDO: R$ 100,00
🚀 MARGEM REAL: 4.17%

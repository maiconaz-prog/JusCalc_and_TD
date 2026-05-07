# JusCalc - Cálculos Jurídicos & Análises Históricas do Tesouro Direto

O **JusCalc** é uma plataforma especializada no desenvolvimento de ferramentas para cálculos judiciais complexos e análise técnica de títulos públicos (Tesouro Direto). O projeto visa unir a precisão financeira necessária para o mercado de capitais com o rigor normativo exigido no âmbito jurídico brasileiro.

## ⚖️ Visão Geral

O sistema permite que advogados, peritos judiciais e investidores realizem simulações de rentabilidade retroativa, correções monetárias de ativos e avaliações de impacto tributário sobre títulos da dívida pública.

## ✨ Funcionalidades Principais

* **Calculadora Judicial:** Aplicação de índices de correção (IPCA-E, SELIC, TR) em conformidade com as teses fixadas pelo STF e STJ.
* **Histórico do Tesouro Direto:** Base de dados abrangente com preços e taxas históricas de títulos como Tesouro IPCA+, Tesouro Prefixado e Tesouro Selic.
* **Análise de Volatilidade:** Visualização de marcação a mercado (MtM) para entender perdas e ganhos em resgates antecipados.
* **Relatórios PDF:** Geração de memórias de cálculo detalhadas para anexação em processos ou apresentações de consultoria.

## 🚀 Tecnologias Utilizadas

* **Frontend:** React.js / Next.js (Interface reativa e otimizada).
* **Backend:** Node.js / Python (Processamento de grandes volumes de dados históricos).
* **Dados:** Integração com APIs oficiais do Tesouro Nacional e Banco Central (BCB).
* **Estilização:** Tailwind CSS para um design sóbrio e profissional.

## 🛠️ Instalação e Execução

Para rodar o projeto localmente:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/usuario/juscalc.git
    ```
2.  **Instale as dependências:**
    ```bash
    cd juscalc
    npm install
    ```
3.  **Configure as variáveis de ambiente:**
    Crie um arquivo `.env` seguindo o modelo `.env.example` com as chaves de API necessárias.
4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```

## 📊 Estrutura de Dados

O JusCalc organiza as análises históricas em três pilares:
1.  **Indexadores:** Evolução mensal de índices de inflação.
2.  **Curva de Juros:** Comparativo entre a taxa contratada e a praticada pelo mercado.
3.  **Simulação de Resgate:** Cálculo líquido considerando alíquotas regressivas de IR e taxas da B3.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
*Desenvolvido para transformar dados complexos em decisões jurídicas fundamentadas.*

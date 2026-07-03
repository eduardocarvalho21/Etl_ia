# Pipeline de ETL Inteligente: Geração de Mensagens de Marketing com IA

Este projeto foi desenvolvido em parceria com a **DIO (Digital Innovation One)**, com o objetivo de criar um pipeline de ETL (Extract, Transform, Load) completo utilizando Python e Inteligência Artificial Generativa.

O pipeline extrai dados simplificados de usuários, utiliza a API do **Google Gemini** para gerar mensagens de marketing personalizadas de forma dinâmica e exporta os resultados finais em formatos estruturados para a tomada de decisão.

---

## 🚀 Arquitetura do Pipeline (ETL)

1. **Extract (Extração):** Definição da estrutura inicial do projeto e simulação da extração de dados dos usuários (como nomes e interesses de consumo).
2. **Transform (Transformação):** Integração com o SDK do Gemini (`google-genai`) para analisar o perfil de cada usuário e gerar mensagens promocionais altamente engajadoras e personalizadas.
3. **Load (Carga):** Consolidação dos dados transformados e exportação final em relatórios estruturados nos formatos **CSV** e **Excel** utilizando a biblioteca Pandas.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3** (Ambiente de execução Google Colab)
* **Google Gemini API** (Gerenciamento de IA Generativa via SDK oficial)
* **Pandas** (Manipulação, tratamento de dados e exportação)
* **Git & GitHub** (Controle de versão e boas práticas com Conventional Commits)

---

## 📂 Estrutura de Arquivos no Repositório

* `relatorio_marketing_gemini.csv`: Amostra de dados gerada no formato CSV.
* `relatorio_marketing_gemini.xlsx`: Amostra de dados gerada no formato Excel.
* `README.md`: Documentação oficial do projeto.

---

## 🔐 Configuração de Segurança

O projeto utiliza o gerenciamento seguro de chaves de API por meio do recurso **Secrets** do Google Colab, garantindo que credenciais sensíveis (como tokens do GitHub e chaves da API do Gemini) fiquem protegidas e não sejam expostas publicamente no código-fonte.

---
Desenvolvido por [Eduardo Carvalho](https://github.com/eduardocarvalho21) em colaboração com a comunidade da **DIO**.
"""

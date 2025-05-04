# Know Your Fan — Desafio FURIA (Notebook MVP)

Este notebook apresenta uma solução baseada em dados para identificar e entender fãs de organizações de esports, alinhada à estratégia “Know Your Fan” da FURIA. O objetivo é simular um sistema capaz de coletar, enriquecer e interpretar informações do usuário para apoiar experiências e serviços personalizados.

## O que a solução faz

- **Coleta dados estruturados** do fã: nome, CPF, localização, interesses, atividades e compras.
- **Valida documentos de identificação** com lógica simulada de IA (baseada em prompt do ChatGPT).
- **Analisa perfis em redes sociais** em busca de conteúdo ligado a esports (limitado por restrições da plataforma).
- **Avalia links de perfis em sites de esports** (como Liquipedia e Steam), identificando relevância com base em palavras-chave e nome do usuário.
- **Classifica o tipo de fã** com base em pontuação: casual, engajado ou competitivo.

## Funcionalidades

| Componente                   | Status                                      |
| ---------------------------- | ------------------------------------------- |
| Entrada de dados do usuário  | Simulada                                    |
| Validação de documento (IA)  | Simulada                                    |
| Análise de redes sociais     | Parcial - Twitter/X bloqueado para scraping |
| Validação de perfis externos | Implementada com scraping real              |
| Classificação do tipo de fã  | Baseada em regras simples                   |

## ⚙️ Tecnologias utilizadas

- Python 3
- Jupyter Notebook
- pandas
- requests
- BeautifulSoup
- Renderização em Markdown

> As etapas com IA são simuladas, mas a estrutura permite fácil substituição por APIs reais (como OpenAI).

## Observações

- **Twitter/X bloqueia scraping sem autenticação.** Os links são aceitos, mas não processados.
- **Este é um protótipo.** Os dados são fictícios e a validação de documentos é simplificada.
- Nenhuma informação real é coletada ou armazenada.

## Como executar

1. Abra o Notebook [KYF-FURIA](https://colab.research.google.com/drive/1O1XE2oXjp0W5tzWvGT2ar761yCvIcptq?usp=sharing) e execute as células na ordem.

## Arquivos

| Arquivo               | Descrição                                |
| --------------------- | ---------------------------------------- |
| `know_your_fan.ipynb` | Notebook principal com lógica e execução |
| `README.md`           | Este arquivo                             |

## Sobre o autor

Desenvolvido por Lucas Martins como parte do desafio técnico do processo seletivo da FURIA.  
Foco em backend, manipulação de dados e integração prática de IA.

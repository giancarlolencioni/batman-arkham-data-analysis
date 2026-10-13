#  Análise de Dados — Franquia Batman: Arkham

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Análise de Dados](https://img.shields.io/badge/An%C3%A1lise_de_Dados-EDA-blue?style=for-the-badge)

##  Visão Geral do Projeto
Este projeto realiza uma Análise Exploratória de Dados (EDA) e consolida um Dashboard interativo focado no volume de vendas estimadas, avaliações da crítica e de utilizadores, duração dos jogos e engajamento da comunidade na Steam para a franquia de jogos *Batman: Arkham*.

---

##  Objetivos
- **Avaliações:** Comparar a perceção entre críticos e utilizadores.
- **Duração:** Analisar o tempo médio de jogo (história principal vs. conclusão a 100%).
- **Vendas:** Comparar o volume estimado de vendas globais por desenvolvedora.
- **Engajamento na Steam:** Observar a evolução do pico de jogadores simultâneos ao longo dos lançamentos.
- **Padrões de Mercado:** Identificar relações entre notas, orçamento e desempenho comercial.

---

##  Ferramentas
- **Microsoft Excel:** Tratamento e limpeza de dados, modelagem com Tabelas Dinâmicas e construção de Dashboard interativo.
- **Análise Exploratória de Dados (EDA):** Identificação de métricas-chave, discrepâncias de desempenho e padrões de mercado.

---

##  Dashboard
<img width="935" height="430" alt="Captura de tela 2026-10-13 064338" src="https://github.com/user-attachments/assets/316f9810-12d5-4547-9ad7-985052ac65f7" />

---

##  Principais Observações

###  Destaques por Jogo
* **Batman: Arkham Asylum:** Estabeleceu a base da franquia com vendas estimadas (9,5M) e avaliações médias superiores às de *Arkham Knight*, sendo o título mais compacto da série (~12h de história e 25h para 100%).
* **Batman: Arkham City:** Registou o maior volume de vendas estimadas (~12,5M) e as maiores médias de avaliação entre críticos (93,6) e utilizadores (87,6).
* **Batman: Arkham Origins:** Apresentou o menor volume de vendas estimadas da amostra (~7,0M) e a menor nota média da crítica (73,0).
* **Batman: Arkham Knight:** Alcançou o maior pico de jogadores simultâneos na Steam (27.406) e a maior duração de campanha (~17h de história e 51,5h para 100%).

###  Padrões e Análise de Mercado
* **Duração dos Jogos:** O tempo necessário para concluir a história e atingir os 100% apresentou uma tendência contínua de crescimento ao longo da franquia.
* **Impacto Técnico em Arkham Knight:** A versão para PC enfrentou problemas técnicos graves no lançamento, o que resultou numa penalização severa na nota média dos utilizadores (66,3).
* **Relação Custo x Desempenho:** Apesar de *Arkham Knight* ter contado com um orçamento significativamente superior, as suas vendas estimadas (~7,5M) ficaram abaixo de *Asylum* e *City*, aproximando-se do volume de *Origins*.
* **Comparativo de Desenvolvedoras:** A *Rocksteady Studios* concentrou cerca de **80,8% do volume total de vendas estimadas** (~29,5M de unidades na amostra), acumulando aproximadamente **4,2x mais vendas** do que a *WB Games Montréal* (~7,0M).

---

## ⚠️ Limitações e Contexto dos Dados
> **Escopo da Amostra:** As observações referem-se exclusivamente aos quatro jogos base analisados, não representando a totalidade de relançamentos, edições *Remaster* ou títulos derivados da franquia.

1. **Estimativas de Vendas:** Os valores correspondem a estimativas provenientes de agregadores de mercado (HackerNoon e VGChartz) e não a relatórios financeiros oficiais.
2. **Pico de Jogadores na Steam:** Os registos históricos do SteamDB refletem acessos simultâneos no PC e podem não traduzir integralmente o comportamento da base de jogadores no período original de lançamento nas consolas.
3. **Avaliações e Notas:** As notas de críticos e utilizadores representam uma média consolidada das plataformas analisadas (PC, PlayStation e Xbox), calculada a partir das edições base de cada jogo.

---

##  Fontes
* **Metacritic:** Avaliações de críticos e utilizadores
* **HowLongToBeat:** Duração dos jogos (Main Story / 100%)
* **SteamDB:** Pico de jogadores simultâneos no PC
* **HackerNoon e VGChartz:** Estimativas de vendas globais

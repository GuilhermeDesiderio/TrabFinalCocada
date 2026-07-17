# Sistema Híbrido de Recomendação de Filmes

Recomendador de filmes combinando filtragem colaborativa (SVD) e filtragem baseada em conteúdo (TF-IDF), aplicado ao dataset MovieLens 32M. Projeto final da disciplina CoCada — IC/UFRJ.

## Como funciona

- **SVD** sobre a matriz usuário-item de avaliações (filtragem colaborativa)
- **TF-IDF** sobre gêneros e tags dos filmes (filtragem baseada em conteúdo)
- As duas pontuações são combinadas por um parâmetro alpha, com análise de sensibilidade documentada no relatório

## Estrutura

- `CineSVD.ipynb` — pipeline completo
- `Relatorio.pdf` — relatório escrito
- `relatorio_assets/` — figuras do relatório
- `movies.csv`, `tags.csv`, `links.csv` — dados auxiliares

## Dataset

`ratings.csv` não incluído (>800MB). Baixe em [MovieLens 32M](https://grouplens.org/datasets/movielens/32m/) e coloque na raiz do projeto.

## Como rodar

## Autor

Guilherme Desiderio — Ciência da Computação, IC/UFRJ

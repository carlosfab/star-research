# STAR Research Institute

Repositorio de materiais complementares para alunos da [STAR Research Institute](https://starresearch.institute).

Este repositorio contem notebooks, codigos e referencias utilizados nas aulas, workshops e programas de pesquisa da STAR Research.

## Como usar

Clone o repositorio e instale as dependencias com [uv](https://docs.astral.sh/uv/):

```bash
git clone https://github.com/carlosfab/star-research.git
cd star-research
uv sync
```

Para abrir os notebooks:

```bash
uv run jupyter notebook
```

## Materiais

| Material | Tema | Notebook |
|----------|------|----------|
| Ant Colony Optimization | Implementacao de papers: ACO aplicado ao TSP (Dorigo et al., 2006) | [notebooks/ant-colony-optimization](notebooks/ant-colony-optimization) |

## Estrutura do repositorio

```
star-research/
├── notebooks/       # Jupyter notebooks organizados por tema
├── tests/           # Testes automatizados
├── docs/            # Documentacao adicional
├── assets/          # Imagens e recursos estaticos
├── pyproject.toml   # Dependencias do projeto (gerenciado por uv)
└── README.md
```

## Contato

Site: [starresearch.institute](https://starresearch.institute)

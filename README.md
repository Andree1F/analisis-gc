# Análisis de Contenido GC en Genes Humanos

Proyecto de bioinformática desarrollado como parte de mi aprendizaje autodidacta.

## ¿Qué hace?
Analiza el contenido GC (guanina-citosina) de secuencias de ADN de genes humanos
relacionados con cáncer y genera una visualización comparativa.

## Genes analizados
- **BRCA1** — gen supresor de tumores, implicado en cáncer de mama y ovario
- **TP53** — "guardián del genoma", mutado en más del 50% de los cánceres humanos
- **MYC** — oncogén que regula la proliferación celular

## Resultados
| Gen | Longitud | Contenido GC |
|-----|----------|--------------|
| BRCA1 | 59 pb | 37.3% |
| TP53 | 58 pb | 58.6% |
| MYC | 59 pb | 52.5% |

## Herramientas utilizadas
- Python 3.12
- Biopython
- Matplotlib

## Cómo ejecutarlo
```bash
jupyter notebook analisis_contenido_gc.ipynb
```

## Autor
Andree Fierro — Ing. en biotecnología

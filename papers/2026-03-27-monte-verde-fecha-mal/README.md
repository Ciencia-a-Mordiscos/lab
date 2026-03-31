# Monte Verde no es un sitio arqueológico antiguo

Durante casi 50 años, Monte Verde II en Chile fue la evidencia más sólida de presencia humana en Sudamérica antes de la cultura Clovis, con una fecha de ~14,500 años B.P. Un nuevo equipo tomó muestras independientes y encontró que una capa de ceniza volcánica (tefra) datada en ~11,000 años B.P. está *debajo* de la capa arqueológica — lo que sugiere que los artefactos no pueden ser tan antiguos como se pensaba.

**El hallazgo:** Las nuevas dataciones de radiocarbono y luminiscencia apuntan a que Monte Verde II corresponde al Holoceno Medio (8,200-4,200 años B.P.) — unos 6,000 años más reciente que la fecha original.

## Gráfica clave

![Dataciones por estrato](figuras/dataciones_por_estrato.png)

## Reproducir

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-27-monte-verde-fecha-mal/notebook.ipynb)

O localmente:
```bash
pip install pandas matplotlib numpy scipy
jupyter execute notebook.ipynb
```

## Datos

- `datos/dataciones_c14.csv` — 23 dataciones de radiocarbono (Lab ID, estrato, material, profundidad, edad ¹⁴C ± σ, edad calendario calibrada con rango 2σ)
- `datos/dataciones_luminiscencia.csv` — 6 dataciones de luminiscencia IR50 (dosis equivalente, tasa de dosis, edad corregida por fading)

## Links

- **Video:** [Ver en YouTube](https://youtube.com/watch?v=04c87eYoTV4)
- **Paper:** [Science — DOI: 10.1126/science.adw9217](https://doi.org/10.1126/science.adw9217)
- **Datos originales:** Tables 1-2 del paper

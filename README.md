# 🌽 Simulador Bioeconómico - Fertilización en Maíz

**Autores:** María Isabel Díaz Granados, Anais Díaz Granados, Channy González, Ronald Gómez, Hernán Corredor
**Institución:** Universidad de Santa Marta - Ingeniería Agrícola
**Año:** 2026

## 📖 Descripción
Simulador web interactivo que optimiza la dosis de fertilizante nitrogenado en maíz usando un modelo cuadrático de rendimiento y ecuaciones lineales de costos.

## 🧮 Modelo Matemático
- **Rendimiento:** y(d) = a·d² + b·d + c
- **Dosis óptima agronómica:** d* = -b/(2a)
- **Dosis óptima económica:** deco = -(p·b - Cv)/(2·p·a)
- **Costo total:** C(d) = Cf + Cv·d
- **Utilidad:** U(d) = p·y(d) - C(d)

## 🚀 Demo
👉 [Ver simulador](https://TU-USUARIO.github.io/simulador-maiz/)

## 📜 Licencia
MIT
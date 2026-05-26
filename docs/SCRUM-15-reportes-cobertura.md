# SCRUM-15: Reportes de Cobertura con Badges

## Objetivo
Generar reportes de cobertura de codigo con badges visibles en el README.

## Configuracion
- Herramienta: pytest-cov + coverage-badge
- Umbral minimo: 80 pct de cobertura
- Badge dinamico integrado en README.md

## Comandos
pytest --cov=src --cov-report=html --cov-report=term-missing


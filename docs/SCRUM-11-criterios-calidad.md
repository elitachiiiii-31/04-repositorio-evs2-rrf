# SCRUM-11: Criterios de Calidad y Métricas para EVS2

## Objetivos
Definir criterios de calidad y métricas para asegurar la calidad del proyecto EVS2.

## Criterios de Calidad
- Cobertura de pruebas: >= 80%
- Densidad de defectos: < 1 defecto por 100 líneas
- Complejidad ciclomática: <= 10 por función
- Deuda técnica: < 5% del tiempo total

## Métricas
| Métrica | Umbral | Herramienta |
|---------|--------|-------------|
| Cobertura de pruebas | >= 80% | pytest-cov |
| Densidad de defectos | < 1/100 LOC | SonarCloud |
| Duplicación de código | < 3% | SonarCloud |
| Complejidad ciclomática | <= 10 | pylint |

## Estándares Aplicados
- ISO/IEC 25010: Modelo de calidad del producto
- IEEE 730: Plan de aseguramiento de calidad

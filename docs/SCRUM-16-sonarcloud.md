# SCRUM-16: Configurar SonarCloud para Analisis Estatico

## Objetivo
Integrar SonarCloud para analisis estatico de codigo automatizado.

## Configuracion
- Plataforma: SonarCloud.io
- Integracion con GitHub Actions
- Analisis en cada Pull Request

## sonar-project.properties
```properties
sonar.projectKey=port4folio_04-repositorio-evs2-rrf
sonar.organization=port4folio
sonar.sources=src
sonar.tests=tests
sonar.python.coverage.reportPaths=coverage.xml

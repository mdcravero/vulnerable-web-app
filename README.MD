# Examen Final DevSecOps & Cloud Security

### Sast

**En este paso se realizan 4 checkeo**
- Escaneo de secretos con horusec y generación de un artefacto
- Escaneo de vulnerabilidades con trivi y envió a Security Tab
- Escaneo de dependencias con npm-audit y generaciń de un artefacto
- Escaneo de dependencias con better-npm-audit y visualización de los resultados por consola


### Deploy

Se realiza un despliegue de la aplicación a Heroku solo si se completa el análisis de Sast

### Dast

Se realiza un análisis del endpoint de la aplicación con owasp, si esta se desplegó con éxito, y se envia el informe a Faraday


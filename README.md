# sonar-slack-notifier-2025
Versión compilada y actualizada del plugin sonar-slack-notifier de zyclonite. Compatible con Java 17 y SonarQube 10.x+. Incluye binarios (.jar) listos para descargar.

# SonarQube Slack Notifier Plugin (Updated Build)

Este repositorio contiene una versión **compilada y lista para usar** del plugin [sonar-slack-notifier-plugin](https://github.com/zyclonite/sonar-slack-notifier-plugin) mantenido originalmente por `zyclonite`.

### 🚀 ¿Por qué existe este repositorio?
El repositorio original de `zyclonite` (que a su vez es un fork de `kogisin`) contiene el código fuente actualizado para las versiones modernas de SonarQube, pero **actualmente no ofrece "Releases" (binarios) oficiales para descargar**.

Como SysAdmin, compilar código Java en entornos de producción no siempre es viable. Este repositorio provee el archivo `.jar` ya compilado con **Java 17**, listo para instalar en instancias modernas de SonarQube.

### 📋 Compatibilidad
- **SonarQube:** Probado en versiones 9.x y 10.x.
- **Java Runtime:** Requiere Java 17 (versión estándar en las imágenes docker de SonarQube actuales).

### 📥 Instalación Rápida

1. Descarga el último `.jar` desde la sección de **[Releases](https://github.com/TU-USUARIO/TU-REPO/releases)**.
2. Copia el archivo en la carpeta de plugins de tu servidor:
   ```bash
   cp sonar-slack-notifier-*.jar /opt/sonarqube/extensions/plugins/
3. Reinicia SonarQube.

⚖️ Créditos y Licencia

Todo el crédito del código fuente pertenece a zyclonite y los autores originales. Este repositorio solo sirve como canal de distribución de los binarios compilados.

Licencia: GNU LGPL 3.0 (Heredada del proyecto original).


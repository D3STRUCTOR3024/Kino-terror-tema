# Terror Nocturno | Tema Halloween para Kino TV

Tema de Halloween/terror nocturno: negro absoluto, degradado violeta espectral, verde tóxico y acentos naranja calabaza.

## Archivos
- `kino-plugin.json`: manifiesto apiVersion 18, tema, ajustes y logo vectorial integrado.
- `plugin.js`: punto de entrada requerido.
- `logo-preview.png`: imagen horizontal de presentación.
- `logo-icon.png`: icono cuadrado de 512 × 512 para GitHub.

**Nota:** Kino dibuja el logo del tema con los vectores declarados en `kino-plugin.json`. Los PNG son imágenes de presentación para el repositorio, no archivos que el campo `logo` cargue dentro de Kino.

## Compatibilidad
Requiere Kino 0.9.81 o posterior. Los bordes personalizados requieren Kino 0.9.82 o posterior.

## Instalación
1. Crea un repositorio público en GitHub.
2. Sube estos archivos a la raíz.
3. Instala el plugin desde Ajustes → Plugins con `usuario/repositorio` o la URL del manifiesto, según las opciones de tu versión.
4. Ve a Ajustes → Apariencia y selecciona **Terror Nocturno**.

## Validación
Con el kit oficial de Kino:
```bash
node sdk/validate.mjs .
```

# Generador de Contraseñas Personalizadas

Una aplicación web moderna diseñada para generar contraseñas seguras y predecibles para tus diferentes servicios y cuentas, operando 100% de manera local.

## ¿Qué hace esta aplicación?

En lugar de generar contraseñas aleatorias que son imposibles de recordar, esta aplicación utiliza un **algoritmo determinista**. Esto significa que si le das los mismos datos de entrada (el nombre de un servicio, una fecha y tu "Base Fija" personal), **siempre te devolverá la misma contraseña**. 

De esta manera, no necesitas almacenar tus contraseñas en ninguna base de datos; simplemente puedes regenerarlas cada vez que las necesites.

## Características Principales

- **100% Offline y Segura:** Todo el procesamiento ocurre exclusivamente en tu navegador. Ningún dato sale de tu dispositivo, garantizando máxima privacidad.
- **Base Fija Protegida:** Tu "Base Fija" se cifra localmente utilizando el estándar militar AES-GCM (vía Web Crypto API) y se bloquea con un PIN, protegiendo tu secreto incluso si alguien accede a tu dispositivo.
- **Diseño Moderno:** Interfaz limpia con soporte automático para Modo Oscuro y herramientas para copiar fácilmente tu contraseña.
- **Configuración Personalizable:** Puedes activar o desactivar componentes de la contraseña final (como el año o caracteres especiales) según los requisitos de seguridad de cada servicio.

## Cómo ejecutar de forma local

Si deseas clonar y ejecutar este proyecto en tu propia máquina:

1. Clona el repositorio.
2. Instala las dependencias con `npm install`.
3. Inicia el servidor de desarrollo con `npm run dev`.
4. Abre la dirección proporcionada (usualmente `http://localhost:5173`) en tu navegador web.

---
*Nota: Este proyecto fue diseñado como una herramienta de uso personal para mejorar la seguridad sin depender de gestores de contraseñas de terceros.*

## Licencia y Uso

Creado por Antonio G.

Este software está disponible **exclusivamente para uso personal y no comercial**. Eres libre de utilizar el código para fines personales, pero **no está permitido** distribuirlo, modificarlo para reventa, ni utilizarlo (total o parcialmente) en proyectos con fines lucrativos o comerciales sin autorización expresa de Antonio G.

Para más detalles, revisa el archivo [LICENSE](LICENSE) incluido en este repositorio.

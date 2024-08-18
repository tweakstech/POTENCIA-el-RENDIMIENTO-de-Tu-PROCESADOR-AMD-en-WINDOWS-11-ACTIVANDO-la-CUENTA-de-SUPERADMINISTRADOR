# POTENCIA el RENDIMIENTO de Tu PROCESADOR AMD en WINDOWS 11 ACTIVANDO la CUENTA de SUPERADMINISTRADOR

- Se ha descubierto que activar la cuenta de superadministrador en Windows puede mejorar el rendimiento del Ryzen 9700X en juegos. Esta cuenta, que está oculta por defecto, debe ser activada manualmente a través de la línea de comandos.
- La diferencia en el rendimiento parece estar relacionada con las restricciones de las cuentas normales, más que con un fallo en sí. Esto no es una novedad y puede suceder también al ejecutar juegos como administrador. El fenómeno destaca cómo las restricciones de seguridad de Windows pueden impactar en el rendimiento de los juegos.

> [!TIP]
> Activar la cuenta de superadministrador puede proporcionar un aumento de rendimiento en juegos y aplicaciones que dependen en gran medida del procesamiento del CPU.

**¿Qué sucede?**

- **Rendimiento Mejorado:** Al activar la cuenta de superadministrador, el rendimiento en juegos del Ryzen 9700X puede aumentar en un 3.8%.
- **Privilegios de Superadministrador:** Las cuentas normales o de administrador pueden no tener permisos suficientes para aprovechar al máximo el procesador. La cuenta de superadministrador elimina estas restricciones.

> [!WARNING]
> Activar la cuenta de superadministrador puede exponer tu sistema a mayores riesgos de seguridad. Usa esta opción con precaución y asegúrate de comprender las implicaciones.

**¿Es un fallo?**

- **No necesariamente:** Aunque algunos consideran que esto es un "fallo" de Windows, en realidad se trata de un ajuste de seguridad estándar. Las cuentas de superadministrador tienen menos restricciones, lo que puede permitir un mejor rendimiento en juegos.
- **Comparaciones Limitadas:** No se ha probado este efecto con procesadores Intel, por lo que no se puede confirmar si es un problema exclusivo de los Ryzen o de Windows en general.

> [!IMPORTANT]
> Aunque activar la cuenta de superadministrador puede mejorar el rendimiento, esta acción debe ser realizada con conocimiento de los riesgos. La seguridad de tu sistema podría verse comprometida.

### Activar la Cuenta de Superadministrador para Mejorar el Rendimiento del Ryzen 9700X

1. **Método 1: Usando Línea de Comandos**

   - **Activar Superadministrador:**
     `net user administrador /activate:yes`

   - **Desactivar Superadministrador:**
     `net user administrador /activate:no`

2. **Método 2: Usando la Consola de Usuarios Locales**

   - Presiona `Windows + R` y escribe:
     `lusrmgr.msc`

   - **Para desactivar la cuenta:**
     1. Selecciona **Usuarios** en el panel izquierdo.
     2. Haz clic derecho en **Administrador** y selecciona **Propiedades**.
     3. Marca la opción **La cuenta está deshabilitada** y aplica los cambios.

   - **Para activar la cuenta:**
     1. Sigue el mismo proceso, pero desmarca la opción **La cuenta está deshabilitada** y selecciona **La cuenta nunca expira**.
     2. Aplica los cambios.

> [!CAUTION]
> Asegúrate de desactivar la cuenta de superadministrador cuando no la necesites. Mantener esta cuenta activa puede dejar tu sistema vulnerable a ataques y accesos no autorizados.

**Nota de Seguridad:** Ten en cuenta que activar la cuenta de superadministrador puede comprometer la seguridad de tu sistema. Aunque esto puede ofrecer mejoras en el rendimiento, no siempre es recomendable debido a los riesgos asociados con una mayor exposición a vulnerabilidades. Usa esta opción con precaución y solo si estás dispuesto a asumir las posibles consecuencias.


---


## Licencia

 Este proyecto se encuentra bajo la licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Consulta el archivo `LICENSE` para más detalles.

© 2024 tweakstech

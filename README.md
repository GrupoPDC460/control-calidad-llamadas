# Control y Calidad de Llamadas · AVON · PDC

Evaluación de calidad de llamadas de cobro (criterios, auto-fail, fichas firmadas y ranking por equipo).

- **Publicado en:** Vercel (team PDCGroup), deploy automático en cada push a `main`.
- **Datos:** Supabase (`cq_evals`, `cq_config`), solo a través de funciones `cq_*` del servidor.
- **Acceso:** ver no requiere sesión (teléfono, código y firmas se ocultan). Para evaluar, firmar, eliminar o editar equipos/logos se entra con el correo y la contraseña del equipo (mismos usuarios que *Reporte de llamadas*). Cada cambio queda en la huella `rl_auditoria`.
- **Marca:** línea gráfica Grupo PDC (Navy #00216F, Naranja #FF5100).

Producción: https://control-calidad-llamadas-pdcg-roup.vercel.app

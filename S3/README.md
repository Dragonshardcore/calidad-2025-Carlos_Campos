# Sesión 3 — ISO/IEC 25010
Objetivo: clasificar problemas de MediTurnos con el modelo y escribir requisitos medibles.
Entregables: Matriz CSV completa + 3–5 hallazgos en este README.

## Parte D — Hallazgos 

1. El sistema presenta **problemas críticos de rendimiento y seguridad**, especialmente en la carga del listado de médicos y el cierre automático de sesión.
2. Se detectaron **fallos de usabilidad**, como mensajes de error poco claros y botones mal ubicados que provocan errores del usuario.
3. La **interoperabilidad** con plataformas externas (Outlook Calendar) no está completamente implementada, lo que afecta la compatibilidad.
4. La aplicación **no conserva el estado** al actualizar la página, lo que impacta la fiabilidad y genera pérdida de datos.
5. Se requiere implementar **validaciones funcionales adicionales** para evitar turnos solapados, mejorando la corrección funcional del sistema.

**Conclusiones**

En general, el sistema cumple con su objetivo principal de gestionar turnos médicos, pero las pruebas revelaron varios aspectos que pueden mejorarse para lograr una experiencia más fluida, segura y confiable. 
Los hallazgos relacionados con el rendimiento, la seguridad de las sesiones y la usabilidad en distintos dispositivos nos muestran que aún hay espacio para optimizar tanto la parte técnica como la interacción del usuario. Estos ajustes no solo mejorarán la eficiencia del sistema, sino también la confianza de quienes lo usan a diario.

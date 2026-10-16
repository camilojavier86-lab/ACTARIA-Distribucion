# ACTARIA · Canal de distribución

Canal público para distribuir **únicamente** instaladores aprobados de ACTARIA (Windows y Android) y los avisos de actualización.

El código fuente y la base de datos de ACTARIA pertenecen al repositorio privado de la aplicación. Ninguna orden de compra, recepción, acta, factura, registro personal ni documento institucional debe publicarse aquí.

## Estado del canal
**EN PREPARACIÓN. No hay instaladores aprobados para actualización automática.**

- Se publicarán versiones mediante GitHub Releases, acompañadas por un resumen de mejoras y huellas SHA-256 para verificar su integridad.
- Android utilizará una firma de publicación permanente. Las APK antiguas de depuración no pueden instalarse encima de una APK firmada con otra clave.
- Windows solicitará autorización antes de instalar una actualización.
- Cada versión se publicará después de pruebas HTML, pruebas de instalación y aprobación.

## Manifiesto
El archivo `version.json` es el manifiesto público previsto para la aplicación. Mientras su estado sea `inactive`, no debe anunciarse una actualización.

**Seguridad:** nunca publicar claves de firma, contraseñas, tokens, datos institucionales, respaldos ni código fuente.

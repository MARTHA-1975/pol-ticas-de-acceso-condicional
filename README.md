🔎 Explicación del ejemplo
DisplayName: nombre de la política.

State: activada (enabled).

Conditions:

Users: todos los usuarios.

Applications: todas las aplicaciones.

Devices: condición que exige que el dispositivo esté marcado como compatible en Microsoft Entra.

GrantControls: en este caso usamos block para denegar acceso si no cumple.

🚀 Buenas prácticas
Empieza probando en modo “reportOnly” para ver qué usuarios serían bloqueados.

Aplica primero a un grupo piloto antes de extenderlo a toda la organización.

Documenta la política con su objetivo: “Proteger datos corporativos asegurando que solo dispositivos compatibles accedan”.

👉 Con este ejemplo ya tienes dos escenarios distintos:

Exigir MFA fuera de Colombia.

Bloquear acceso desde dispositivos no compatibles.

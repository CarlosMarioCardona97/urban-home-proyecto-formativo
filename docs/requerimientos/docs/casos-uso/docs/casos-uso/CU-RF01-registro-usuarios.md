# CU-RF01 - Registro de usuarios

## Actor principal

Persona interesada en utilizar Urban Home.

## Precondición

La persona no tiene una cuenta registrada en la plataforma.

## Flujo principal

1. La persona selecciona la opción de registro.
2. Ingresa sus datos personales y correo electrónico.
3. Selecciona su rol: arrendador o arrendatario.
4. El sistema valida los campos obligatorios y verifica que el correo no exista.
5. El sistema crea la cuenta.
6. El sistema envía un correo de confirmación.

## Resultado esperado

La persona queda registrada en Urban Home con el rol seleccionado y puede continuar con el proceso de autenticación.

## Escenarios alternativos

- Si falta un campo obligatorio, el sistema informa el dato que debe completarse.
- Si el correo ya está registrado, el sistema muestra un mensaje e impide crear una cuenta duplicada.
- Si el correo tiene un formato inválido, el sistema solicita corregirlo.

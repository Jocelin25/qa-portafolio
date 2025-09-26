# Bug Report: Registro permite contraseña demasiado corta

| ID Bug | Módulo   | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|--------|----------|-----------|-----------|-------------|------------------------|-----------------|--------------------|--------------------|--------|
| BUG003 | Registro | Media     | Media     | El sistema permite registrar una contraseña de menos de 6 caracteres | 1. Abrir la aplicación <br> 2. Ir a la pantalla de registro <br> 3. Ingresar un correo válido <br> 4. Ingresar contraseña: "123" <br> 5. Completar resto de los campos <br> 6. Hacer clic en "Registrarse" | Email: bug3@test.com <br> Password: 123 | El sistema debería **rechazar el registro** y mostrar mensaje: *"La contraseña debe tener al menos 6 caracteres"* | El sistema **acepta el registro** y crea el usuario con contraseña inválida | Abierto |

# Caso de Prueba: Inicio de Sesión con credenciales inválidas

| ID Caso | Módulo | Descripción | Precondiciones | Pasos | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|---------|--------|-------------|----------------|-------|-----------------|--------------------|--------------------|--------|
| TC002   | Login  | Verificar que el sistema no permita iniciar sesión con credenciales inválidas | Usuario no registrado o credenciales incorrectas | 1. Abrir la aplicación <br> 2. Ingresar usuario no registrado <br> 3. Ingresar contraseña inválida <br> 4. Hacer clic en “Iniciar sesión” | Usuario: `fake@test.com` <br> Contraseña: `WrongPass123` | El sistema muestra un mensaje de error: “Usuario o contraseña inválidos” y no permite el acceso | - | Pendiente |

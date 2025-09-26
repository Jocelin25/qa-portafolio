# Bug Report: Login permite acceso con credenciales inválidas

| ID Bug | Módulo | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido |
|--------|--------|-----------|-----------|-------------|-----------------------|-----------------|--------------------|--------------------|
| BUG002 | Login  | Crítica   | Alta      | El sistema permite ingresar con usuario/contraseña inválidos | 1. Abrir la aplicación <br> 2. Ingresar usuario no registrado <br> 3. Ingresar contraseña inválida <br> 4. Hacer clic en “Iniciar sesión” | Usuario: fake@test.com <br> Contraseña: WrongPass123 | El sistema debe rechazar el acceso y mostrar mensaje de error: "Usuario o contraseña inválidos" | El sistema permite ingresar y muestra el panel principal |

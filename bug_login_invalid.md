# Bug Report: Login permite acceso con credenciales inválidas

| ID Bug | Módulo | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|--------|--------|-----------|-----------|-------------|-----------------------|-----------------|--------------------|--------------------|--------|
| BUG001 | Login  | Alta      | Alta      | El sistema permite acceder con credenciales inválidas | 1. Abrir la aplicación <br> 2. Ingresar usuario `fake@test.com` <br> 3. Ingresar contraseña `WrongPass123` <br> 4. Hacer clic en "Iniciar sesión" | Usuario: fake@test.com <br> Contraseña: WrongPass123 | El sistema debe rechazar el acceso y mostrar mensaje de error | El sistema permite acceder al panel principal | Abierto |

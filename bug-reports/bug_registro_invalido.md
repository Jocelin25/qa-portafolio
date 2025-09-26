# Bug Report: Registro permite correo duplicado

| ID Bug  | Módulo   | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|---------|----------|-----------|-----------|-------------|-----------------------|-----------------|--------------------|--------------------|--------|
| BUG001  | Registro | Alta      | Alta      | El sistema permite registrar un correo ya existente en la BD | 1. Abrir la aplicación <br> 2. Ir a la pantalla de registro <br> 3. Ingresar un correo ya registrado <br> 4. Completar el resto de los campos <br> 5. Hacer clic en "Registrarse" | Email: jocelin@test.com <br> Password: Pass123 | El sistema debería rechazar el registro y mostrar mensaje: "El correo ya está en uso" | El sistema permite crear el usuario duplicado | Abierto |

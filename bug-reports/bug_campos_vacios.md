# Bug Report: Login permite intento con campos vacíos

| ID Bug | Módulo | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|--------|--------|-----------|-----------|-------------|------------------------|-----------------|--------------------|--------------------|--------|
| BUG008 | Login  | Alta      | Alta      | El sistema permite presionar "Iniciar sesión" sin completar los campos obligatorios. | 1. Abrir la aplicación <br> 2. Dejar campo usuario vacío <br> 3. Dejar campo contraseña vacío <br> 4. Hacer clic en "Iniciar sesión" | Usuario: *(vacío)* <br> Contraseña: *(vacío)* | El sistema debe rechazar el intento y mostrar mensaje: **"Los campos no pueden estar vacíos"** | El sistema permite procesar el intento sin mostrar mensaje de validación | Abierto |

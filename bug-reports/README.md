# Reportes de Bugs 🐞

Este directorio contiene los **reportes de bugs** encontrados durante las pruebas.  
Cada bug se documenta en un archivo individual con formato Markdown (`.md`).  

---

## 📂 Estructura de los archivos
- Cada archivo corresponde a **un bug específico**.  
- El nombre sigue el formato:  

Ejemplo:  

---

## 📝 Formato de los reportes de bugs

Cada reporte sigue esta estructura:

| ID Bug | Módulo | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|--------|--------|-----------|-----------|-------------|-----------------------|-----------------|--------------------|--------------------|--------|
| BUGXXX | [ej: Login] | [Crítica / Alta / Media / Baja] | [Alta / Media / Baja] | [¿Qué pasa mal?] | 1. Paso 1 <br> 2. Paso 2 <br> 3. Paso 3 | Usuario: xxx@test.com <br> Contraseña: YYY | [¿Qué debería pasar?] | [¿Qué pasó en realidad?] | [Abierto / Cerrado] |

---

## 📌 Ejemplo
```markdown
# Bug Report: Login permite acceso con credenciales inválidas

| ID Bug | Módulo | Severidad | Prioridad | Descripción | Pasos para Reproducir | Datos de Prueba | Resultado Esperado | Resultado Obtenido | Estado |
|--------|--------|-----------|-----------|-------------|-----------------------|-----------------|--------------------|--------------------|--------|
| BUG002 | Login | Crítica | Alta | El sistema permite ingresar con usuario/contraseña inválidos | 1. Abrir la aplicación <br> 2. Ingresar usuario no registrado <br> 3. Ingresar contraseña inválida <br> 4. Hacer clic en “Iniciar sesión” | Usuario: fake@test.com <br> Contraseña: WrongPass123 | El sistema debe rechazar el acceso y mostrar mensaje: “Usuario o contraseña inválidos” | El sistema permite ingresar y muestra el panel principal | Abierto |

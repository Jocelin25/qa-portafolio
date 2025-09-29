# Pruebas manuales
# Pruebas manuales

Este directorio contiene los **casos de prueba funcionales y de regresión** documentados en formato Markdown (`.md`).  
Aquí se definen pruebas manuales enfocadas en **login, registro, logout** y otras funcionalidades críticas de la aplicación.

---

## 📂 Estructura de los archivos
- Cada archivo corresponde a un **caso de prueba individual**.
- El nombre sigue el formato:  
  `caso_prueba_<funcionalidad>.md`  
  Ejemplo: `caso_prueba_login.md`

---

## 📋 Formato de los casos de prueba

Cada caso de prueba sigue esta estructura:

| ID | Título | Descripción | Precondiciones | Pasos | Datos de Prueba | Resultado Esperado | Estado |
|----|--------|-------------|----------------|-------|-----------------|--------------------|--------|

---

## ✅ Ejemplo de caso de prueba

| ID     | Título                  | Descripción                                | Precondiciones             | Pasos                                                                 | Datos de Prueba           | Resultado Esperado                           | Estado   |
|--------|-------------------------|--------------------------------------------|----------------------------|----------------------------------------------------------------------|---------------------------|-----------------------------------------------|----------|
| TC001  | Login válido            | Verificar acceso con credenciales correctas | Tener usuario registrado   | 1. Abrir la app <br> 2. Ingresar usuario y contraseña válidos <br> 3. Hacer clic en "Iniciar sesión" | Usuario: test@test.com <br> Password: Pass123 | El sistema permite el acceso y muestra el panel principal | Pendiente |

---

## 📌 Estado de los casos
- **Pendiente:** Caso creado, aún no ejecutado.  
- **En ejecución:** Caso en proceso de prueba.  
- **Ejecutado:** Caso completado.  
- **Bloqueado:** No se puede ejecutar por error previo o dependencia.  

---

✍️ Con esta estructura podrás mantener organizadas todas tus **pruebas manuales** y mostrar un portafolio profesional.

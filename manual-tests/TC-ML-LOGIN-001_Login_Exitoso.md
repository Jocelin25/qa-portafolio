# Caso de Prueba: Login exitoso - MercadoLibre

**ID:** TC-ML-LOGIN-001  
**Título:** Login exitoso con usuario registrado y credenciales válidas  
**Módulo:** Autenticación / Login  
**Prioridad:** Alta  
**Tipo de prueba:** Funcional, Positiva, UI Web  
**Versión:** 1.0  
**Autor:** Jocelin Contreras  
**Fecha:** (completa tú la fecha de hoy)

---

## 1. Descripción

Verificar que un usuario **ya registrado** en MercadoLibre puede iniciar sesión correctamente en el sitio web utilizando un correo y contraseña válidos, y que el sistema lo redirige a la pantalla principal mostrando su cuenta iniciada.

---

## 2. Precondiciones

1. El usuario cuenta con un navegador web compatible (por ejemplo: Google Chrome actualizado).
2. El usuario tiene conexión a Internet estable.
3. El usuario ya posee una cuenta registrada en MercadoLibre.
4. Se conoce un par de credenciales válidas (correo + contraseña) del usuario de prueba.  
   - *Ejemplo (no real):*  
     - Correo: usuario.prueba.qa@mail.com  
     - Contraseña: ********
5. El usuario no está logueado previamente en MercadoLibre en el navegador (cerrar sesión antes de ejecutar, si aplica).

---

## 3. Datos de prueba

| #  | Dato                  | Valor de ejemplo                         |
|----|-----------------------|------------------------------------------|
| 1  | URL                   | https://www.mercadolibre.cl              |
| 2  | Correo electrónico    | usuario.prueba.qa@mail.com               |
| 3  | Contraseña            | ********                                 |
| 4  | Navegador             | Google Chrome  versión XX (indicar)      |
| 5  | Sistema Operativo     | Windows 10 / 11 (indicar)                |

*(Reemplaza los datos con los de tu usuario de prueba real si tienes uno.)*

---

## 4. Pasos de ejecución

1. Abrir el navegador web.
2. Ingresar la URL de MercadoLibre en la barra de direcciones:  
   `https://www.mercadolibre.cl` y presionar **Enter**.
3. Esperar a que cargue la página principal de MercadoLibre.
4. Hacer clic en el botón o enlace **“Ingresá”** (suele estar en la parte superior derecha).
5. En la pantalla de login, ingresar en el campo **Correo electrónico** la dirección de correo registrada.
6. Hacer clic en el botón **“Continuar”**.
7. En la pantalla siguiente, ingresar la **contraseña** correspondiente a ese correo.
8. Hacer clic en el botón **“Ingresar”** (o similar).
9. Esperar a que el sistema procese las credenciales y redirija al usuario.

---

## 5. Resultado esperado

1. El sistema acepta las credenciales y **no** muestra mensajes de error.
2. El usuario es redirigido a la página principal de MercadoLibre con sesión iniciada.
3. En la parte superior de la página se muestra alguna indicación de usuario logueado, por ejemplo:
   - Nombre del usuario
   - Menú de cuenta
   - Opción para **“Salir”** / **“Cerrar sesión”**.
4. La URL corresponde a una página válida dentro de MercadoLibre (no página de error).
5. No se muestran mensajes de error ni advertencias inesperadas.

---

## 6. Resultado obtenido

- **Resultado al ejecutar:** (Completar después de hacer la prueba)
  - [ ] Pasó  
  - [ ] Falló  
- **Evidencia:**  
  - Captura de pantalla de la página principal con el usuario logueado  
  - Otra evidencia necesaria (logs, consola del navegador, etc., si aplica)

---

## 7. Observaciones / Notas

- Indicar cualquier comportamiento adicional observado, por ejemplo:
  - Demora excesiva en el login
  - Mensajes de seguridad (verificación adicional)
  - Redirecciones intermedias
- Registrar si el sitio solicita verificación en dos pasos (2FA) y cómo impacta el flujo del caso de prueba.

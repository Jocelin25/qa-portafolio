# Caso de Prueba: Login fallido – Contraseña incorrecta

**ID:** TC-ML-LOGIN-002  
**Título:** Login fallido utilizando contraseña incorrecta  
**Módulo:** Autenticación / Login  
**Prioridad:** Alta  
**Tipo de prueba:** Funcional, Negativa, UI Web  
**Versión:** 1.0  
**Autor:** Jocelin Contreras  
**Fecha:** (completar)

---

## 1. Descripción
Validar que el sistema muestre un mensaje de error adecuado cuando un usuario intenta iniciar sesión con un correo válido pero contraseña incorrecta.

---

## 2. Precondiciones
1. El usuario ya está registrado en MercadoLibre.
2. Se conoce un correo válido perteneciente a una cuenta existente.
3. Se usa una contraseña inválida para probar el error.
4. El usuario no está logueado previamente.

---

## 3. Datos de prueba

| Dato | Valor de ejemplo |
|------|-----------------|
| URL | https://www.mercadolibre.cl |
| Correo válido | usuario.prueba.qa@mail.com |
| Contraseña incorrecta | 12345678 |
| Navegador | Google Chrome versión XX |

---

## 4. Pasos de ejecución
1. Abrir el navegador.
2. Ingresar la URL https://www.mercadolibre.cl
3. Hacer clic en **“Ingresá”**.
4. Ingresar el correo válido y presionar **Continuar**.
5. Ingresar una **contraseña incorrecta**.
6. Hacer clic en **Ingresar**.
7. Observar el comportamiento del sistema.

---

## 5. Resultado esperado
- El sistema debe rechazar el inicio de sesión.
- Se debe mostrar un mensaje de error claro, por ejemplo:
  **“La contraseña es incorrecta”** o similar.
- El usuario permanece en la pantalla de login.
- No debe iniciarse sesión bajo ningún motivo.

---

## 6. Resultado obtenido
- [ ] Pasó  
- [ ] Falló  
**Evidencia:** Captura del mensaje de error

---

## 7. Observaciones
Registrar el texto exacto del mensaje mostrado por el sistema.

# Bug Report: Mensaje de error en login con contraseña incorrecta – MercadoLibre

**ID:** BR-LOGIN-001  
**Título:** Mensaje de error al intentar login con contraseña incorrecta  
**Producto/Sitio:** MercadoLibre Chile  
**Módulo:** Autenticación / Login  
**Prioridad:** Alta  
**Severidad:** Media  
**Estado:** Nuevo  
**Reportado por:** Jocelin Contreras  
**Fecha:** 17-11-2025

---

## 1. Descripción
Al intentar iniciar sesión utilizando un correo válido y una contraseña incorrecta, el sistema muestra un mensaje de error. Se necesita validar que el mensaje sea claro, correcto y que no permita el acceso.

---

## 2. Entorno
- **URL:** https://www.mercadolibre.cl  
- **Navegador:** Google Chrome  
- **SO:** Windows 11  
- **Dispositivo:** Desktop

---

## 3. Pasos para reproducir

1. Abrir navegador e ingresar a https://www.mercadolibre.cl
2. Hacer clic en **“Ingresá”**
3. Ingresar un correo válido registrado.
4. Hacer clic en **“Continuar”**
5. Ingresar una contraseña incorrecta.
6. Hacer clic en **“Ingresar”**
7. Observar resultado.

---

## 4. Resultado actual
El sistema muestra un mensaje similar a:  
> “La contraseña es incorrecta”

---

## 5. Resultado esperado
- El usuario no debe acceder.
- Se debe mostrar un mensaje claro, comprensible y completo, por ejemplo:
> “La contraseña ingresada es incorrecta. Vuelve a intentarlo.”

---

## 6. Evidencia
- (Agregar captura cuando se ejecute la prueba real)
- Anotar cualquier comportamiento adicional relevante.

---

## 7. Notas
- Verificar si existe bloqueo después de múltiples intentos.

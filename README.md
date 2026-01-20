# 🧪Lab 04: Colaboración Segura con Invitados (B2B)

## 🎯 Objetivo
Permitir acceso a terceros usando sus credenciales (B2B), sin gestionar contraseñas internas, y gobernar el acceso mediante grupos.

## 🛠️ Tareas realizadas
1. Invitación B2B a un correo real (externo).
2. Creación del grupo **GRP_Consultores_Externos** y asignación del invitado al grupo.
3. Aceptación de la invitación por parte del invitado (acceso verificado).
4. Verificación en Microsoft Entra del estado **Guest** + **Accepted**.

## 📸 Evidencias

### 1) Grupo **GRP_Consultores_Externos** con el invitado añadido
[<img src="images/02-grupo-externos.png" width="800">](images/02-grupo-externos.png)

### 2) Invitado accede tras aceptar (ventana incógnito)
[<img src="images/01-guest-accepted.png" width="800">](images/01-guest-accepted.png)

### 3) Invitado registrado en Entra como **Guest** con estado **Accepted**
[<img src="images/02-guest-accepted.png" width="800">](images/02-guest-accepted.png)

> Nota: Se omite la captura del email recibido para evitar ruido.

## ✅ Checklist de verificación
- [x] Invitado aparece como **Guest**
- [x] Estado **Accepted**
- [x] Acceso siempre por **grupos** (no individual)

## 🗣️ Qué le diría al cliente / entrevista
“B2B evita gestionar credenciales de terceros y facilita una revocación rápida del acceso mediante grupos, manteniendo control y trazabilidad.”

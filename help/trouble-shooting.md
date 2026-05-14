---
title: Solución de problemas del Panel de control
description: Obtenga información sobre cómo solucionar problemas del Panel de control.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
source-git-commit: 9b8483fbaa7dce7f908c79e929d3b9628fd8fa44
workflow-type: tm+mt
source-wordcount: 353
ht-degree: 70%

---

# Solución de problemas del [!UICONTROL Panel de control]

## Inicio de sesión y página de inicio

### Síntoma: no se puede iniciar sesión en Experience Cloud

**Qué hacer:**
El usuario debe localizar su ID de organización de IMS (xxx). El administrador debe añadir el usuario al Perfil de productos “Campaign-xxx-Admins” para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: los vínculos de la página principal de Experience Cloud para acceder al [!UICONTROL Panel de control] no aparecen para un usuario.

**Causa:**
Los usuarios no verán los vínculos hasta que se añadan como usuarios al Perfil de productos _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: una instancia no aparece en la lista del [!UICONTROL Panel de control]

**Causa:**
Es muy probable que el usuario deba añadirse como *usuario* Perfil de producto _Campaign-xxx-Administradores/Admin_ para la instancia que falta

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como “usuario”.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*ID de organización IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Cómo añadir un administrador a los administradores de perfil de productos para poder usar el [!UICONTROL Panel de control] (01:03 min)*

### Documentación útil

* [Descubra el Panel de control](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)
* [Administración de permisos en el [!UICONTROL Panel de control]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Permite incluir en la lista de permitidos] la dirección IP desde la que se conecta al servidor SFTP
* Par de claves públicas/privadas que debe registrarse con Adobe Campaign
* Para conectarse directamente al servidor SFTP, también necesitará el software de cliente SFTP

### Documentación útil {#helpful-docs}

* [Inicio de sesión en el servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)

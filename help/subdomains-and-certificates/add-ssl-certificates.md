---
title: Añadir certificados SSL
description: Aprenda a añadir certificados SSL para proteger los subdominios.
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 1b1efe35c2ddcf379d1e847064ffa8be18d276b3
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 62%

---

# Añadir certificados SSL

Adobe Campaign [!UICONTROL Control Panel] le permite añadir certificados SSL para proteger sus subdominios.

## Acceso a la administración del subdominio con el panel de control de Campaign

Para acceder a la administración de subdominios en panel de control de Campaign, vaya a:

* [Página de inicio de Experience Cloud](https://experience.adobe.com/#/home) > Selector de soluciones: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** tarjeta > **[!UICONTROL Subdomains & Certificates]** tarjeta

   o
* Directamente desde la dirección URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Pasos para añadir los certificados SSL

Para añadir los certificados SSL se requieren tres pasos:

### 1. Generar solicitudes de firma de certificado.

La solicitud de firma de certificado (CSR) es necesaria para la compra de un certificado SSL. Debe generarse para la instancia y los subdominios que planea proteger.

En el siguiente vídeo se describe cómo generar una solicitud de firma de certificado en el panel de control de Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12&learn=0n)

*Generar solicitudes de firma de certificado (2:36 min)*

>[!NOTE]
>
>Se han llevado a cabo varias mejoras en el proceso de generación de CSR:
>
>* Al generar una CSR, ahora puede seleccionar uno de los subdominios incluidos como Nombre común.
>* Ahora puede copiar el resumen de la CSR antes de generarla.
>* Una vez que se ha generado una CSR, puede descargarla de nuevo desde los registros de trabajos. Esta función no se aplica a los certificados generados antes de esta versión.
>
>![Descargar CSR](/help/assets/download-csr.gif)
>
>Consulte la [documentación del producto](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) para obtener más información.

### 2. Comprar certificados SSL

Después de obtener la CSR, debe adquirir el certificado SSL de una entidad emisora de certificados aprobada por su organización.

### 3. Instalar certificados SSL

Una vez obtenido el certificado SSL, debe instalarse para los subdominios que planea proteger.

El siguiente vídeo explica cómo instalar los certificados SSL en [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12&learn=0n)

*Instalar certificados SSL (1:25 min)*



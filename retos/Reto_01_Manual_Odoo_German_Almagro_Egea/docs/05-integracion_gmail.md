# 05 — Integración con Gmail (OAuth GCP + Add-on)


## Requisitos
- Cuenta Google Cloud (GCP).



## Pasos resumidos
1. **Activar plugin de correo** 

En Ajustes Generales y, dentro de esta pantalla, busca la sección de Integraciones.
Una vez allí, marca la casilla para activar el "Plugin de correo" y asegúrate de guardar los cambios en la esquina superior izquierda.

![Activar](../assets/img/05-integracion_gmail/paso01_activar.png)

En gmail le daremos al + que aparece en la parte derecha e instalaremos el Odoo Inbox Addin

![Activar](../assets/img/05-integracion_gmail/paso02_addin.png)

Iniciamos sesion y ponemos la url de nuestra base de datos

![Activar](../assets/img/05-integracion_gmail/paso03_inst.png)



2. En **Google Cloud Console**:

En la misma pestaña de opciones seleccionaremos Autenticacion OAuth

![Activar](../assets/img/05-integracion_gmail/paso01_activar.png)


En google, buscamos google cloud le daremos a crear proyecto y buscamos la api de gmail

![Activar](../assets/img/05-integracion_gmail/paso04_api.png)

creamos los credenciales, en permisos, seleccionamos agregar o quitar permisos y buscamos google api, seleccionaremos esto:
![Activar](../assets/img/05-integracion_gmail/paso05_creden.png)

![Activar](../assets/img/05-integracion_gmail/paso06_credenci.png)

![Activar](../assets/img/05-integracion_gmail/paso07_mail.png)

![Activar](../assets/img/05-integracion_gmail/paso08_apimail.png)

En la pantalla de credenciales seleccionamos la cuenta que hemos creado y rellenamos los datos

![Activar](../assets/img/05-integracion_gmail/paso010_cliente.png)

Volvemos a odo y ponemos la id del cliente, lo permitimos y guardamos 

![Activar](../assets/img/05-integracion_gmail/paso011_crear.png)

Y completamos los campos 

![Activar](../assets/img/05-integracion_gmail/paso012_confi.png)



3. Copiar **Client ID/Secret** a Odoo 



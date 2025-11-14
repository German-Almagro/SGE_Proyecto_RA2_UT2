# 06 — Instalación de Odoo

> Elige uno de los métodos y documenta tu elección.

## ENlace fuente:

    https://www.odoo.com/documentation/19.0/es/administration/on_premise/packages.html


   ```bash
    wget -q -O - https://nightly.odoo.com/odoo.key | sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg

   echo 'deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/19.0/nightly/deb/ ./' | sudo tee /etc/apt/sources.list.d/odoo.list

   sudo apt-get update && sudo apt-get install odoo
   ```




> Resultado esperado: binarios/código de Odoo instalados.

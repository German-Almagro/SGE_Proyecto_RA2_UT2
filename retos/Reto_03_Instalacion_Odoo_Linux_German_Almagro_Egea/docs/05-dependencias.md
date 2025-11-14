# 05 — Dependencias (Python, wkhtmltopdf, librerías)

1. Instala Python y paquetes de compilación:
   ```bash
   sudo apt -y install python3 python3-pip python3-venv build-essential libxslt1-dev libzip-dev libldap2-dev libsasl2-dev libjpeg-dev libpq-dev
   ```

   ![Servicio PostgreSQL](../assets/img/05-dependencias/paso01.png "Estado del servicio")


2. Instala **wkhtmltopdf** compatible (para reportes PDF).

![Servicio PostgreSQL](../assets/img/05-dependencias/paso02.png "Estado del servicio")


3. Verifica versiones:
   ```bash
   python3 --version
   wkhtmltopdf --version
   ```

   ![Servicio PostgreSQL](../assets/img/05-dependencias/paso03.png "Estado del servicio")


> Resultado esperado: dependencias instaladas y comprobadas.

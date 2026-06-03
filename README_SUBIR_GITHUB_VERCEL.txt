INSTRUCCIONES PARA GITHUB + VERCEL

1) Sube estos 4 archivos a tu repositorio:
   - index.html
   - manual-instrucciones.pdf
   - certificado-estandar-ue.pdf
   - certificado-lfgb.pdf

2) Si tu proyecto es una landing HTML simple:
   Pon los 3 PDF en la misma carpeta donde esta index.html.

3) Si tu proyecto es Next.js / React / Vite:
   Pon los 3 PDF dentro de la carpeta public/.
   En el codigo los enlaces ya estan como:
   /manual-instrucciones.pdf
   /certificado-estandar-ue.pdf
   /certificado-lfgb.pdf

4) No uses enlaces de GitHub tipo /blob/ ni raw de un repositorio privado.
   Eso puede dar 401. Los PDFs deben servirse desde el dominio de Vercel.

5) Despues de subirlo, haz redeploy en Vercel.
   Prueba estas URLs:
   https://TU-DOMINIO.vercel.app/manual-instrucciones.pdf
   https://TU-DOMINIO.vercel.app/certificado-estandar-ue.pdf
   https://TU-DOMINIO.vercel.app/certificado-lfgb.pdf

6) HubSpot:
   El formulario ya esta embebido con:
   portal-id: 148610000
   form-id: 7113aa3b-543d-4b84-a217-06f7f2faf172
   region: eu1
   Ademas he anadido el tracking code de HubSpot en el <head>.

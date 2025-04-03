# Parte 2

## **Certificado Autofirmado: yeray.proyecto9.com**

![alt text](<img/Detalle_Certificado.png>)

1. **Enviado a:**
   - Nombre común (CN): `yeray.proyecto9.com`
   - Organización (O): `Mi Organización`
   - Unidad organizativa (OU): ``

2. **Emitido por:**
   - Nombre común (CN): `yeray.proyecto9.com`
   - Organización (O): `Mi Organización`
   - Unidad organizativa (OU): ``

   **Nota:** El emisor es el mismo que el destinatario, lo cual es típico de los certificados autofirmados.

3. **Periodo de validez:**
   - Emitido el: miércoles, 2 de abril de 2025
   - Vencimiento el: jueves, 2 de abril de 2026

4. **Huella digital SHA-256:**
   - Certificado: `5cacb1b89e5bf2269f1126d44eded7a0ae64ffa20dfa3897535f6b530511553`
   - Clave pública: `54e08fc52fe9da7865a247c5ae8512404d36d1a8dd53b612823238574c106`

5. **Observaciones:**
   - Este certificado no está validado por una autoridad de certificación (CA), por lo que los navegadores lo consideran no confiable.
   - Es útil para pruebas locales o entornos internos, pero no para producción.

---

## Error al entrar por primera vez

![alt text](<img/Error_del_Navegador.png>)


## Certificado Verificado: .github.io

![alt text](<img/Detalle_Certificado_Otra_Pagina.png>)

1. **Enviado a:**
   - Nombre común (CN): `*.github.io`
   - Organización (O): ``
   - Unidad organizativa (OU): ``

2. **Emitido por:**
   - Nombre común (CN): `Sectigo RSA Domain Validation Secure Server CA`
   - Organización (O): `Sectigo Limited`
   - Unidad organizativa (OU): ``

   **Nota:** El emisor es una autoridad de certificación reconocida globalmente (Sectigo), lo que garantiza la confiabilidad del certificado.

3. **Periodo de validez:**
   - Emitido el: viernes, 7 de marzo de 2025
   - Vencimiento el: domingo, 8 de marzo de 2026

4. **Huella digital SHA-256:**
   - Certificado: `7d1122ea969852341e8dd92bcc07ecc009603d14da734d7ca42d5b54a2b2097`
   - Clave pública: `4d5b60917974e7d644e439b528822cca348aacf9d128d64d80c06df4c6db`

5. **Observaciones:**
   - Este certificado está validado por una autoridad de certificación confiable, lo que permite su uso en producción y garantiza la seguridad y confianza para los usuarios.
   - Los navegadores no muestran advertencias al acceder a sitios con este tipo de certificados.

---

## Comparativa de los certificados

| Aspecto                     | Certificado Autofirmado                 | Certificado Verificado                  |
|-----------------------------|-----------------------------------------|-----------------------------------------|
| **Emisor**                  | El mismo servidor (`yeray.proyecto9.com`) | Autoridad certificadora confiable (`Sectigo Limited`) |
| **Confiabilidad**           | No confiable para navegadores           | Confiable para navegadores             |
| **Uso**                     | Pruebas locales o entornos internos     | Producción y acceso público seguro     |
| **Validación**              | No validado por CA                      | Validado por una CA reconocida         |
| **Periodo de validez**      | 1 año                                   | 1 año                                  |
| **Advertencia del navegador** | Sí                                     | No                                      |
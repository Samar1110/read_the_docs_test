# Exportar clave pública (Xpub)

Crea monederos de solo lectura en tu software de Bitcoin favorito exportando tu clave pública. Esto te permite monitorear saldos y preparar transacciones sin exponer tus claves privadas.

## Proceso completo paso a paso con todas las capturas de pantalla

1. **Acceder a Exportar**: Desde la pantalla principal de la semilla, seleccione **"Exportar Xpub"**

![Menú principal de Seed con la opción Exportar Xpub](images/SeedMenuView_wl_es.png){w=250px align=center}

2. **Seleccionar el tipo de firma**:
     - **"Monofirma"** - Para monederos personales estándar
     - **"Multifirma"** - Para monederos multifirma que requieren varios dispositivos

![Selección del tipo de firma Xpub](images/SeedExportXpubSigTypeView_wl_es.png){w=250px align=center}

3. **Seleccionar el tipo de script**:
     - **Native Segwit** (bech32) - Recomendado para las comisiones más bajas
     - **Nested Segwit** (P2SH) - Para compatibilidad con sistemas antiguos
     - **Taproot** - Para funciones avanzadas de privacidad y contratos inteligentes

![Selección del tipo de script para Xpub](images/SeedExportXpubScriptTypeView_wl_es.png){w=250px align=center}

4. **Elegir el software de billetera**: Seleccione su billetera preferida entre las opciones compatibles

![Selección del software de billetera](images/SeedExportXpubCoordinatorView_wl_es.png){w=250px align=center}

5. **Aceptar la advertencia de privacidad**: Pulse **"Entiendo"** después de leer las implicaciones de privacidad de Xpub

![Pantalla de advertencia de privacidad de Xpub](images/SeedExportXpubWarningView_wl_es.png){w=250px align=center}

6. **Generar código QR**: Selecciona **"Exportar XPub"** para mostrar el código QR para compartir.

![Código QR generado por XPub](images/SeedExportXpubDetailsView_wl_es.png){w=250px align=center}

7. **Importar a la billetera**: Escanea el código QR con el software de billetera que elijas.

![Código QR generado por XPub](images/SeedExportXpubQRView_wl_es.png){w=250px align=center}

> **🔒 Advertencia de privacidad**: Tu XPub (clave pública extendida) revela todas tus direcciones de Bitcoin e historial de transacciones. Compártela únicamente con un software de billetera de confianza y nunca la publiques en línea.

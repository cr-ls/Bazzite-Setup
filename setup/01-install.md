# Fase 1: Instalación del Sistema

Este apartado es únicamente para la instalación desde cero de Bazzite.

## 1. Preparación de Medios
- **ISO:** Descargada desde [bazzite.gg](https://bazzite.gg)
- **Opciones elegidas en el asistente web:**
  - **Hardware:** Desktop.
  - **GPU:** AMD (RX 4XX+ | AI).
  - **Desktop Environment:** KDE.
  - **Steam Gaming Mode:** No (Traditional desktop experience).

- **Herramienta de Flasheo:** Utilicé [BalenaEtcher](https://etcher.balena.io/).
  - *Nota:* Ventoy arrojó errores durante las pruebas.

## 2. Configuración de BIOS
- **Secure Boot:** Puede estar activo, pero si hay problemas con drivers mejor desactivarlo.
- **Orden de Arranque:** Priorizar la unidad USB.

## 3. Primer Inicio y Actualización
1. Seguir el instalador gráfico hasta completar la instalación en el disco.
2. Al iniciar, actualizar las aplicaciones base desde la tienda **Bazaar**.
3. Configurar periféricos básicos (actualmente uso los AirPods 3 como audio principal).
4. **Actualizar el sistema completo:** Abrir la terminal y ejecutar:
   ```bash
   ujust update
**IMPORTANTE** Una vez termine la actualización, REINICIA LA PC.


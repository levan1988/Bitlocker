# Bitlocker
Activar Bitlocker por scripts
# Script de Activación de BitLocker

Este repositorio contiene un script en PowerShell para **habilitar y configurar BitLocker** en equipos con Windows.  
El script fue desarrollado con fines de **automatización y aprendizaje**, y puede usarse como base para entornos de prueba o producción bajo responsabilidad del usuario.

---

## 🚀 Características
- Habilita BitLocker en la unidad de sistema
- Permite configurar el método de protección (TPM, contraseña, clave de recuperación).
- Verifica el estado de BitLocker antes de aplicarlo.
- Genera claves de recuperación y las guarda en tanto AD local como en EntraID/Intune

---

## 📋 Requisitos
- Windows 10 / 11 (Pro, Enterprise o Education).
- Ejecutar con permisos de **Administrador**.
- **TPM 2.0** habilitado en BIOS/UEFI (si se usa TPM).
- PowerShell 5.1 o superior.
  
## 🔧 Uso

1. Clona este repositorio o descarga el script:

   ```powershell
   git clone https://github.com/levan1988/Bitlocker.git
   cd Bitlocker
   Abre PowerShell ISE como Administrador.

Ejecuta el script:

.\BitlockerScript.ps1

## Hacer monitoreo del proceso 
Abre CMD como administrador y poner el comando:
manage-bde -status c:


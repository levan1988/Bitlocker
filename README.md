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

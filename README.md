# ☁️ Azure Security & Networking Sandbox

Bienvenido a mi entorno de pruebas destructible en la nube. Este repositorio contiene plantillas de Infraestructura como Código (IaC) y scripts de Azure CLI para desplegar y destruir laboratorios de seguridad en Microsoft Azure en cuestión de minutos.

## 🏗️ Arquitectura del Sandbox

Los scripts de este repositorio levantan arquitecturas que incluyen:
*   **Virtual Networks (VNets):** Segmentación por subredes (Frontend, Backend, Management).
*   **Network Security Groups (NSGs):** Reglas estrictas de filtrado de tráfico (Zero Trust / Deny All).
*   **Azure Bastion:** Acceso seguro por SSH/RDP sin exponer puertos públicos a internet.
*   **Azure Firewall & Service Endpoints:** Inspección de tráfico y protección de servicios PaaS.

## 🗂️ Contenido

*   📄 `deploy-secure-vnet.azcli`: Script automatizado para aprovisionar una VNet segura con sus respectivas subredes y reglas NSG base de denegación.

## 🚀 Uso
Clona este repositorio, autentícate en Azure CLI (`az login`) y ejecuta los scripts. ¡Recuerda destruir los recursos (`az group delete`) cuando termines el laboratorio para evitar costos!

---
*Mantenido por Marcelo Bugallo (DarthChelo).*

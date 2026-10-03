# Infraestructura 1 — VPN Site-to-Site

## 🎥 Video demostrativo

[▶️ Ver video demostrativo]([ENLACE_DEL_VIDEO](https://itlaedudo-my.sharepoint.com/:v:/g/personal/20250885_itla_edu_do/IQDQO4M0s3gORIx395wP4CiBAfPVDv1NKQBRSCM7lypT-Kc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KNyizC))

---

## 🎯 Propósito del laboratorio

El propósito de esta infraestructura es implementar una comunicación
segura entre una red de usuarios y un servidor Web mediante una VPN
Site-to-Site entre dos dispositivos FortiGate.

La infraestructura debe permitir comprobar que la comunicación entre
el usuario y el servidor solamente es posible cuando el enlace VPN
se encuentra activo.

---

## 🏗️ Infraestructura

La topología está compuesta por:

- 2 FortiGate.
- 1 ISP.
- 2 switches Cisco.
- 1 servidor Web HTTPS.
- 1 red de usuarios.
- VLAN 10.
- DHCP.
- VPN Site-to-Site.
- NAT.
- Traceroute.

Cada lado de la infraestructura cuenta con un switch Cisco.
La interfaz GigabitEthernet0/0 del switch se conecta hacia el
FortiGate o equipo de red correspondiente, mientras que
GigabitEthernet0/1 se conecta hacia el servidor o usuario.

---

## 🌐 Topología

![Topología de red](02-Diagramas/topologia-fisica.png)

---

## 📚 Documentación

- [Propósito](01-Documentacion/01-Proposito.md)
- [Topología](01-Documentacion/02-Topologia.md)
- [Direccionamiento IP](01-Documentacion/03-Direccionamiento-IP.md)
- [Configuración de FortiGate](01-Documentacion/04-Configuracion-FortiGate.md)
- [Configuración de Switches](01-Documentacion/05-Configuracion-Switches.md)
- [Servidor Web](01-Documentacion/06-Configuracion-Servidor-Web.md)
- [Usuarios](01-Documentacion/07-Configuracion-Usuarios.md)
- [VPN Site-to-Site](01-Documentacion/08-VPN-Site-to-Site.md)
- [NAT](01-Documentacion/09-NAT.md)
- [Pruebas](01-Documentacion/10-Pruebas.md)

---

## ⚙️ Configuraciones

Los running-config de los dispositivos utilizados se encuentran en:

`03-Configuraciones/`

---

## 🧪 Evidencias

Las evidencias de configuración y pruebas se encuentran en:

`05-Evidencias/`

# Infraestructura 1 — VPN Site-to-Site

## 🎥 Video demostrativo
https://itlaedudo-my.sharepoint.com/:v:/g/personal/20250885_itla_edu_do/IQDQO4M0s3gORIx395wP4CiBAfPVDv1NKQBRSCM7lypT-Kc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=RbFuGs

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

<img width="521" height="565" alt="image" src="https://github.com/user-attachments/assets/0330df03-30d1-480e-babf-adced80084a6" />



---

## 📚 Documentación

- [Documentacion](Documentacion)


---

## ⚙️ Configuraciones

Los running-config de los dispositivos utilizados se encuentran en:

`Documentacion`

---

## 🧪 Evidencias

Las evidencias de configuración y pruebas se encuentran en:

`Documentacion`

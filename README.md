# 🌐 CCNA Labs — De la teoría a la consola

**50 laboratorios prácticos de redes, configurados y verificados en EVE-NG**, rumbo a la certificación Cisco CCNA.

![Labs completados](https://img.shields.io/badge/labs%20completados-2%2F50-blue)
![Simulador](https://img.shields.io/badge/simulador-EVE--NG-orange)
![Cisco IOS](https://img.shields.io/badge/plataforma-Cisco%20IOS-1ba0d7)
![Licencia](https://img.shields.io/badge/licencia-MIT-lightgrey)

---

## 📖 Sobre este repositorio

Este es mi cuaderno de bitácora público mientras recorro el camino hacia la certificación **CCNA**. Cada carpeta corresponde a uno de los 50 laboratorios del curso, con su topología armada y probada en **EVE-NG**, la configuración completa de los dispositivos y las verificaciones que confirman que todo funciona como debe.

La idea es simple: aprender en público, documentar cada paso y terminar con un portafolio técnico que demuestre no solo la teoría, sino la capacidad real de levantar, configurar y depurar una red desde cero.

## 🧰 Stack utilizado

| Herramienta | Uso |
|---|---|
| **EVE-NG** | Emulación de topologías con IOS/IOSv reales (routers y switches Cisco) |
| **Cisco IOS CLI** | Configuración de dispositivos vía consola/SSH |
| **Markdown** | Documentación de cada solución |
| **Git & GitHub** | Control de versiones y publicación del progreso |

## 🗂️ Estructura del repositorio

```
ccna-labs/
├── README.md
├── LICENSE
└── labs/
    ├── lab-01-basic-switch-configuration/
    │   ├── SOLUCION.md
    │   └── topologia.png
    ├── lab-02-configure-ssh/
    │   ├── SOLUCION.md
    │   └── topologia.png
    └── lab-XX-.../              👈 se irán agregando en el mismo formato
```

Cada carpeta de laboratorio contiene:

- **`SOLUCION.md`** — objetivo del laboratorio, direccionamiento IP, configuración completa en CLI y comandos de verificación.
- **`topologia.png`** — captura de la topología armada en EVE-NG (la imagen incluida por ahora es un diagrama de referencia; se reemplaza por la captura real de cada laboratorio).

> ⚖️ **Nota sobre derechos de autor:** los enunciados originales de las prácticas pertenecen a Cisco Networking Academy (NetAcad) y no se redistribuyen en este repositorio. Lo que aquí se publica es mi propia solución, configuración y documentación de cada ejercicio.

## 🚀 Cómo usar cada laboratorio

1. Entra a la carpeta del laboratorio que te interese (`labs/lab-XX-.../`).
2. Revisa `SOLUCION.md` para ver el direccionamiento IP y la configuración paso a paso.
3. Reproduce la topología en tu propio EVE-NG y aplica la configuración para practicar.
4. Compara tus resultados de verificación con los del documento.

## ✅ Progreso — 50 laboratorios CCNA

| # | Laboratorio | Estado |
|---|---|---|
| 01 | Configuración básica del switch (modo físico) | ✅ |
| 02 | Configurar SSH | ✅ |
| 03 | Configurar interfaces del router | ⏳ |
| 04 | Verificar redes directamente conectadas | ⏳ |
| 05 | Implementar una red pequeña | ⏳ |
| 06 | Configurar parámetros básicos del router | ⏳ |
| 07 | Configuración de VLAN | ⏳ |
| 08 | Configurar VLANs y trunking | ⏳ |
| 09 | Configurar DTP | ⏳ |
| 10 | Router-on-a-Stick — Inter-VLAN Routing | ⏳ |
| 11 | Layer 3 Switching e Inter-VLAN Routing | ⏳ |
| 12 | Solucionar problemas de Inter-VLAN Routing | ⏳ |
| 13 | Investigar la prevención de bucles con STP | ⏳ |
| 14 | Configurar EtherChannel | ⏳ |
| 15 | Solucionar problemas de EtherChannel | ⏳ |
| 16 | Implementar EtherChannel | ⏳ |
| 17 | Guía de configuración de HSRP | ⏳ |
| 18 | Implementar Port Security | ⏳ |
| 19 | Configuración de seguridad del switch | ⏳ |
| 20 | Configurar una red inalámbrica | ⏳ |
| 21 | Configurar una WLAN básica en el WLC | ⏳ |
| 22 | Configurar una WLAN WPA2 Enterprise en el WLC | ⏳ |
| 23 | Solucionar problemas de WLAN | ⏳ |
| 24 | Configuración de WLAN | ⏳ |
| 25 | Rutas estáticas y predeterminadas IPv4/IPv6 | ⏳ |
| 26 | Solucionar problemas de rutas estáticas y predeterminadas | ⏳ |
| 27 | OSPFv2 de área única punto a punto | ⏳ |
| 28 | Determinar el DR y el BDR | ⏳ |
| 29 | Modificar OSPFv2 de área única | ⏳ |
| 30 | Propagar una ruta predeterminada en OSPFv2 | ⏳ |
| 31 | Verificar OSPFv2 de área única | ⏳ |
| 32 | Configuración de OSPFv2 de área única | ⏳ |
| 33 | Demostración de ACL | ⏳ |
| 34 | Configurar ACLs IPv4 estándar numeradas | ⏳ |
| 35 | Configurar ACLs IPv4 estándar nombradas | ⏳ |
| 36 | Configurar y modificar ACLs IPv4 estándar | ⏳ |
| 37 | Configurar ACLs IPv4 extendidas | ⏳ |
| 38 | Configurar NAT estático | ⏳ |
| 39-41 | NAT / PAT | ⏳ |
| 42 | Usar CDP para mapear una red | ⏳ |
| 43 | Usar LLDP para mapear una red | ⏳ |
| 44 | Configurar y verificar NTP | ⏳ |
| 45 | Respaldar archivos de configuración | ⏳ |
| 46 | Usar TFTP y flash para administrar configuraciones | ⏳ |
| 47 | Procedimientos de recuperación de contraseñas | ⏳ |
| 48 | Usar un servidor TFTP para actualizar el IOS | ⏳ |
| 49 | Configurar CDP, LLDP y NTP | ⏳ |
| 50 | Solucionar problemas en redes empresariales | ⏳ |

## 🤝 Autor

**Felipe Varillas** — [@fvarillas](https://github.com/fvarillas)

Si este repositorio te sirve para estudiar o repasar, una ⭐ es más que bienvenida.

## 📜 Licencia

Este proyecto se distribuye bajo la licencia MIT — ver [`LICENSE`](LICENSE) para más detalles.

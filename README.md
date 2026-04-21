# 🚀 Cisco Command Studio · CheatSheet + Constructor Visual de Topologías

![Cisco Command Studio](https://img.shields.io/badge/Cisco-Packet%20Tracer-0099ff?style=for-the-badge&logo=cisco&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 📖 Descripción

**Cisco Command Studio** es una herramienta web todo-en-uno diseñada para estudiantes, profesionales de redes y entusiastas de **Cisco Packet Tracer**. Combina un **CheatSheet interactivo de comandos** con un **constructor visual de topologías** que genera automáticamente scripts de configuración listos para pegar en la CLI.

### ✨ Características Principales

- 📚 **CheatSheet Completo**: Todos los comandos esenciales de Routing, VLANs, ACLs y Router-on-a-stick extraídos de documentación oficial.
- 🎨 **Sintaxis Destacada**: Colores de terminal con prompts diferenciados (`Router>`, `Switch#`, `Router(config-if)#`, etc.).
- 🏗️ **Constructor Visual de Topologías**: 
  - Arrastra y suelta PCs, Switches y Routers en un lienzo interactivo.
  - Conecta dispositivos visualmente (Switch ↔ Router, Router ↔ Router Serial, Switch ↔ Switch).
  - Configura propiedades detalladas: IPs, VLANs, puertos específicos, rangos de interfaces y más.
- ⚡ **Generación Automática de Scripts**: Obtén la configuración exacta para cada dispositivo basada en tu topología.
- 🎯 **Soporte para Escenarios Avanzados**:
  - Enlaces Seriales entre routers con IPs /30 y `clock rate`.
  - Subinterfaces para Router-on-a-stick (802.1Q).
  - Rangos de puertos (`interface range fa0/1-5`) para asignación masiva de VLANs.
  - Trunks configurables con VLANs permitidas.
  - Rutas estáticas y por defecto.
- 📋 **Copiar al Portapapeles**: Un solo clic para copiar todo el script generado.
- 🌙 **Interfaz Moderna**: Diseño oscuro profesional con efectos de vidrio esmerilado, gradientes y animaciones fluidas.
- 📱 **Totalmente Responsive**: Funciona en escritorio, tablet y dispositivos móviles.

---

## 🖼️ Capturas de Pantalla

| CheatSheet Interactivo | Constructor Visual de Topologías |
|:----------------------:|:-------------------------------:|
| ![CheatSheet](https://via.placeholder.com/400x250/0a111c/3e9cff?text=CheatSheet+Comandos) | ![Constructor](https://via.placeholder.com/400x250/0a111c/3e9cff?text=Constructor+Visual) |

---

## 🚀 Cómo Usar

### Opción 1: Usar Online (GitHub Pages)
1. Visita la [demo en vivo](https://h4ck3nd.github.io/cheatsheet_cisco_packet_tracert/).
2. Explora el CheatSheet usando las pestañas superiores.
3. Construye tu topología en el panel izquierdo.
4. Haz clic en **"Generar configuración"**.
5. Copia el script y pégalo en Packet Tracer.

### Opción 2: Ejecutar Localmente

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/cisco-command-studio.git

# Entrar al directorio
cd cisco-command-studio

# Abrir en el navegador
open index.html
```

---

## 🛠️ Tecnologías Utilizadas

- HTML5 - Estructura semántica.

- CSS3 - Diseño avanzado con Flexbox, Grid, gradientes, backdrop-filter y animaciones.

- JavaScript (ES6+) - Lógica del constructor visual, generación de scripts y manipulación del DOM.

- LeaderLine - Librería para dibujar conexiones visuales entre dispositivos.

- Font Awesome - Iconografía profesional.

---

## 📂 Estructura del Proyecto

```
cisco-command-studio/
│
├── index.html          # Archivo principal (todo incluido)
├── README.md           # Este archivo
└── assets/             # (Opcional) Imágenes y recursos
```
> Nota: Todo el código (HTML, CSS, JavaScript) está contenido en un único archivo `index.html` para facilitar su distribución y uso sin dependencias externas.

---

## 🧠 Comandos Incluidos en el CheatSheet

Categoría	Comandos Destacados
Routing + VLANs	enable, vlan, switchport mode trunk, encapsulation dot1Q, ip route, show vlan brief
Routing	ip routing, show ip route, ip route 0.0.0.0 0.0.0.0, show ip interface brief
VLANs	vlan 10, name VLAN10, switchport access vlan 10, show interfaces trunk
ACLs	access-list, ip access-list extended, deny ip, permit icmp, ip access-group

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar esta herramienta:

1. Haz un fork del repositorio.

2. Crea una rama con tu feature (`git checkout -b feature/nueva-funcionalidad`).

3. Haz commit de tus cambios (`git commit -m 'Añadir nueva funcionalidad'`).

4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).

5. Abre un Pull Request.

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

---

## 👨‍💻 Autor

Creado con ❤️ por D1se0

---

## ⭐ Agradecimientos

- A la comunidad de Cisco Networking Academy.

- A los desarrolladores de Packet Tracer por una herramienta increíble.

- A LeaderLine por la librería de conexiones visuales.

¿Te ha sido útil? ¡Dale una ⭐ al repositorio y compártelo con tus compañeros de redes!

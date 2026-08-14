# 🔴 Red Team — Explotación y Escalada de Privilegios en Linux

![Kali Linux](https://img.shields.io/badge/OS-Kali_Linux-blue?style=flat&logo=kali-linux)
![Tools](https://img.shields.io/badge/Tools-Nmap%20|%20Gobuster%20|%20Searchsploit-orange)
![Category](https://img.shields.io/badge/Type-Pentesting_&_Red_Team-red)

## 📌 Descripción del Proyecto
Proyecto práctico enfocado en fases ofensivas de ciberseguridad sobre una máquina objetivo en un entorno de laboratorio aislado. Se cubren todas las etapas de un test de penetración (*pentest*): reconocimiento, análisis de vulnerabilidades, explotación inicial y escalada local de privilegios hasta obtener acceso total como `root`.

---

## 🛠️ Herramientas y Tecnologías Utilizadas
* **Sistema Atacante:** Kali Linux
* **Reconocimiento y Enumeración:** `Nmap`, `Gobuster`
* **Explotación y Análisis:** `Searchsploit`, Metasploit Framework / Exploits manuales
* **Escalada de Privilegios:** Exploits de kernel (`Dirty COW`, `PwnKit / pkexec`), análisis de permisos SUID / sudoers.

---

## 🎯 Fases de la Auditoría

1. **Reconocimiento & Escaneo de Puertos:**
   * Descubrimiento de hosts activos y puertos abiertos con `Nmap`.
   * Enumeración de directorios web ocultos mediante `Gobuster`.
2. **Análisis de Vulnerabilidades & Explotación:**
   * Detección de servicios desactualizados y vulnerables.
   * Ejecución de vector de ataque para obtención de Remote Code Execution (RCE) y captura de credenciales expuestas.
3. **Escalada de Privilegios:**
   * Identificación de vectores de escalada locales.
   * Compilación y ejecución exitosa de exploits de kernel para la obtención de una *shell* con privilegios de `root`.

---

## 📂 Archivos del Repositorio
* `docs/`: Contiene el informe técnico completo con capturas de pantalla, evidencias del proceso (*PoC*) y comandos ejecutados paso a paso.

---

> ⚠️ **Descargo de Responsabilidad:** Este proyecto se ha realizado exclusivamente en un entorno de laboratorio controlado con fines educativos y de entrenamiento ético.

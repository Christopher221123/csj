# MANUAL DE GESTIÓN DEL CICLO DE VIDA DE SOFTWARE
**Dossier de Ingeniería - CSJ Software Develop**

| Propiedad | Detalle |
| :--- | :--- |
| **Código** | [cite_start]DOC-MST-001 [cite: 2] |
| **Estado** | [cite_start]VIGENTE [cite: 2] |
| **Clasificación** | [cite_start]INTERNO [cite: 2] |
| **Fecha** | [cite_start]28/01/2026 [cite: 3] |
| **Ubicación** | [cite_start][POR DEFINIR] [cite: 5] |
| **Responsable** | [cite_start]Juan Martín Charvet Andrade – Director de Tecnología [cite: 5] |

---

## 📋 Historial de Versiones
| Versión | Fecha | Autor | Descripción | Revisado por |
| :--- | :--- | :--- | :--- | :--- |
| 1.0 | 28/01/2026 | Juan Martín Charvet Andrade | Creación inicial del sistema de gestión de ingeniería | [cite_start]Christopher Muzo Trujillo [cite: 7] |

## ✅ Aprobación
| Rol | Nombre |
| :--- | :--- |
| **Gerente General** | [cite_start]Christopher Muzo Trujillo [cite: 9] |
| **QA Lead** | [cite_start]Said Estefano Soriano Adame [cite: 9] |

---

## 1. Introducción y Propósito
[cite_start]El presente Manual establece el marco oficial de ingeniería de **CSJ Software Develop** para la planificación, desarrollo, aseguramiento de calidad, despliegue y mantenimiento de productos de software[cite: 29].

**Este manual adopta como base las siguientes normas:**
* [cite_start]**ISO/IEC 12207:** Procesos del ciclo de vida del software[cite: 31].
* [cite_start]**ISO/IEC 25010:** Modelos de calidad de producto[cite: 32].
* [cite_start]**ISO/IEC/IEEE 29148:** Ingeniería de requisitos[cite: 33].

**Propósitos del documento:**
1.  [cite_start]Estandarizar la forma de trabajo en todos los proyectos[cite: 35].
2.  [cite_start]Garantizar trazabilidad completa desde requisitos hasta producción[cite: 36].
3.  [cite_start]Asegurar que la calidad sea medible, verificable y objetiva[cite: 37].
4.  [cite_start]Facilitar el onboarding de nuevos integrantes[cite: 38].
5.  [cite_start]Permitir auditoría interna y externa[cite: 39].

> [cite_start]**Nota:** Este documento es de cumplimiento obligatorio[cite: 40].

## 2. Alcance del Manual
Este manual aplica a:
* [cite_start]Todos los proyectos desarrollados por CSJ Software Develop (internos y para clientes externos)[cite: 42, 44].
* [cite_start]Todos los integrantes del equipo técnico[cite: 43].
* [cite_start]**Terceros proveedores:** Serán incluidos cuando aporten código fuente, infraestructura, componentes críticos o servicios integrados [cite: 45-49].

## 3. Principios Rectores
[cite_start]CSJ Software Develop opera bajo los siguientes principios[cite: 52]:
* [cite_start]Todo trabajo debe estar documentado[cite: 53].
* [cite_start]Todo requisito debe ser verificable[cite: 54].
* [cite_start]Todo cambio debe ser aprobado[cite: 55].
* [cite_start]Ningún código llega a producción sin pruebas[cite: 56].
* [cite_start]La calidad es responsabilidad de todo el equipo[cite: 57].
* [cite_start]La trazabilidad es obligatoria[cite: 58].

---

## 4. Modelo de Gobernanza Documental

### 4.1 Identificación Única
[cite_start]Todos los documentos deben seguir el formato obligatorio: `DOC-[ÁREA]-[NUMERO]`[cite: 62, 63].
* [cite_start]*Ejemplo:* `DOC-REQ-002`[cite: 64].

### 4.2 Control de Cambios
[cite_start]Cada documento debe contener una tabla de historial que incluya: Versión, Autor, Revisor, Fecha y Descripción del cambio [cite: 66-71].

### 4.3 Ciclo de Vida Documental
El flujo de estado de los documentos es:
[cite_start]`Borrador` → `Revisión` → `Aprobado` → `Vigente` → `Obsoleto`[cite: 72].

### 4.4 Almacenamiento
* [cite_start]Repositorio centralizado con control de acceso[cite: 74, 75].
* [cite_start]Historial de versiones y respaldo periódico[cite: 76, 77].
# 🐾 PetCare Architecture System

Repositorio oficial de documentación arquitectónica para la plataforma **PetCare**, desarrollado bajo el **Modelo 4+1 de Kruchten** y el patrón estructural **Boundary-Control-Entity (BCE)**.

---

## 📐 Vistas del Modelo 4+1

### 1. Vista de Casos de Uso (+1)
Define las interacciones principales entre los actores (Cliente, Recepcionista, Veterinario) y las funciones clave del sistema.
- **Archivo:** `docs/diagramas/casos_uso.puml`

### 2. Vista Lógica
Estructura de clases y modelo relacional normalizado en **Tercera Forma Normal (3FN)**.
- **Archivo:** `docs/diagramas/vista_logica.puml`

### 3. Vista de Procesos
Diagrama de secuencia con patrón **BCE** que detalla el flujo de datos desde la interfaz (`Boundary`) hasta la base de datos (`Database`).
- **Archivo:** `docs/diagramas/vista_procesos.puml`

### 4. Vista de Componentes
Organización modular del sistema desacoplando la capa de presentación (Frontend), lógica de negocio (Backend REST) y persistencia (DAO).
- **Archivo:** `docs/diagramas/vista_componentes.puml`

### 5. Vista de Despliegue
Topología física de red indicando los nodos cliente, servidor de aplicaciones y servidor de base de datos PostgreSQL.
- **Archivo:** `docs/diagramas/vista_despliegue.puml`

---

## 🛠️ Tecnologías y Estándares
- **Lenguaje de Modelado:** PlantUML / UML 2.5
- **Patrones:** BCE (Boundary-Control-Entity), 3FN Relacional
- **Control de Versiones:** Git / GitHub (Conventional Commits)
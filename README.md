# 🍞 Software Synthex by Daniela Roa — Panificadora Daniela SAS
> **Sistema ERP de Manufactura Industrial, Control Multibodega, Finanzas y Trazabilidad Invima.**

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-8.3-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Licencia](https://img.shields.io/badge/Proyecto-Caso_T%C3%A9cnico_Alegra-emerald)](#)

---

## 📌 ¿Qué es Software Synthex?

**Software Synthex** es una plataforma integral de gestión de operaciones de manufactura industrial de panadería diseñada para **Panificadora Daniela SAS**. 

Combina la supervisión estratégica de la gerencia C-Suite con la ejecución táctica del piso de planta. Permite controlar en tiempo real el ciclo completo de valor: **Abastecimiento de insumos &rarr; Entradas a Muelle &rarr; Control Multibodega &rarr; Formulación BOM & rutas &rarr; Simulación Financiera &rarr; Ejecución Kanban de Producción &rarr; Remisiones & Facturación &rarr; Auditoría de Trazabilidad y control de salidas**.

---

## 🌟 Características Principales y Estructura por Módulos

El sistema está organizado de forma intuitiva en 4 grandes ejes estratégicos y operativos con **10 Módulos Integrados**:

```
MÓDULO ESTRATÉGICO / C-SUITE
  ├── 0. Dashboard Gerencial — Visión 360°

MÓDULO DE INVENTARIOS & COMPRAS
  ├── 1. Maestros de Ítems & Compras
  ├── 2. Entradas de Inventario
  ├── 3. Inventario Actual & Bodegas
  └── 4. Facturación & Remisiones

MANUFACTURA & PRODUCCIÓN
  ├── 5. Ingeniería de Producto
  ├── 6. Simulador de Costos
  └── 7. Control de Piso de Producción

AUDITORÍA & CONTROL
  └── 8. Auditoría de Salidas y Trazabilidad

ADMINISTRACIÓN Y SEGURIDAD
  └── 9. Usuarios & Permisos
```

### 📋 Detalle de Funcionalidades por Módulo:

1. **0. Dashboard Gerencial — Visión 360°**: Tablero C-Suite con 6 KPIs top (*Facturación $284.5M*, *Margen Bruto 34.8%*, *OEE 89.2%*, *OTIF 96.4% esta informacion es de ejemplo como una prueba dinamica de la funcionalidad*), sugerencias predictivas del **Synthex AI Copilot** y desglose de 5 pilares operativos.
2. **1. Maestros de Ítems & Compras**: Catálogo técnico de SKUs, punto de reorden, requisiciones sugeridas por IA y emisión de Órdenes de Compra y solicitudes las cuales son clave en el modulo de inventarios.
3. **2. Entradas de Inventario**: Recepción muelle vinculada a O.C., captura de factura de proveedor, lote de insumo, temperatura y vencimiento FEFO.
4. **3. Inventario Actual & Bodegas**: Selector de 3 bodegas físicas (*B-01 Materia Prima*, *B-02 En Proceso WIP*, *B-03 Producto Terminado esta informacion es de ejemplo como una prueba dinamica de la funcionalidad*), toma física para conteo cíclico, cierre fiscal Dian y ajustes manuales por mermas/muestras.
5. **4. Facturación & Remisiones**: Flujo estricto de despacho **Primero Remisión, Luego Factura** para descontar stock de Producto Terminado y liquidar cartera.
6. **5. Ingeniería de Producto & Procesos**: Ficha técnica con Estructura BOM (listado de materiales de cada semiprocesado y producto terminado), definición de Centros de Trabajo (tarifas min. MOD/CIF) y Rutas Operativas.
7. **6. Simulador de Costos & Hoja de Costos por Producto**: Análisis financiero de sensibilidad *What-If* y desglose en Hoja de Costos por lote/unidad con punto de equilibrio.
8. **7. Control de Piso de Producción**: Lanzamiento de Órdenes de Producción, tablero Kanban en vivo, liquidación automática de insumos MP y entregas a bodega.
9. **8. Auditoría de Salidas y Trazabilidad**: Kardex inmutable, trazabilidad forense Invima en 1.4s (del Lote PT a la O.C.) y simulador de Recall sanitario.
10. **9. Usuarios & Permisos**: Administración de perfiles, código PIN de seguridad de 4 dígitos, matriz granular de accesos por módulo y registro de auditoría.

---

## 💻 Tecnologías Utilizadas (importante esta técnologia fue utilizada por la IA antigravity de google)

- **Frontend Core**: [React 18](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Estilos UI**: [Tailwind CSS v3](https://tailwindcss.com/) (Tema oscuro slate con estética industrial)
- **Iconografía**: [Lucide Icons](https://lucide.dev/)
- **Bundler & Dev Server**: [Vite 8](https://vitejs.dev/)
- **Diagramas de Flujo**: [Mermaid JS](https://mermaid.js.org/)

---

## 🚀 Instrucciones de Instalación y Puesta en Marcha (sugerencias de google antigravity para el funcionamiento de la app)

Sigue estos pasos sencillos para clonar y ejecutar el proyecto en tu máquina local:

### Prerrequisitos
Tener instalado [Node.js](https://nodejs.org/) (versión 18 o superior) y `npm`.

### 1. Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/software-synthex-panificadora.git
cd software-synthex-panificadora
```

### 2. Instalar Dependencias
```bash
npm install
```

### 3. Iniciar el Servidor de Desarrollo
```bash
npm run dev
```
La aplicación estará disponible en tu navegador en: **`http://localhost:5173/`**

### 4. Compilar para Producción
```bash
npm run build
```

---

## 📦 Ejecución Autónoma Sin Instalación (Demo Portátil)

Si deseas probar la aplicación de forma inmediata **sin instalar Node.js ni configurar un entorno web**, el proyecto incluye la versión **Demo Portátil Autónoma**:

- **Archivo**: `Software_Synthex_Demo_Portatil.html` *(Single-File Standalone)*
- **Instrucción**: Basta con dar **doble clic** sobre el archivo `Software_Synthex_Demo_Portatil.html` para ejecutar toda la aplicación interactiva con los 10 módulos offline en cualquier navegador (Chrome, Edge, Safari, Firefox).
- **Cumplimiento al ejercicio** en el se solicitaba Prototipo interactivo que corra y al que podamos acceder. 



## ✒️ Autor y Créditos

- **Desarrolladora y product owner**: Daniela Roa Garcia
- **Proyecto**: Caso Técnico Manufactura Industrial
- **Empresa Modelo**: Panificadora Daniela SAS
- **Software prototipo**: *Software Synthex by Daniela Roa*

---
*Synthex Software &copy; 2026. Todos los derechos reservados by Daniela Roa.*

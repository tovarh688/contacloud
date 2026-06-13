📊 ContaCloud
Sistema contable SaaS adaptado a la normativa colombiana — multiempresa, nómina legal, facturación DIAN
![Demo en vivo](https://img.shields.io/badge/🚀_Demo_en_vivo-Ver_aplicación-1A56A0?style=for-the-badge)
[![Stack](https://img.shields.io/badge/Stack-Google_Apps_Script_+_JavaScript-F4B400?style=for-the-badge)]()
[![Normativa](https://img.shields.io/badge/Normativa-Colombia_PUC_+_DIAN-FFCD00?style=for-the-badge)]()
[![Multiempresa](https://img.shields.io/badge/Arquitectura-Multiempresa-0F9D58?style=for-the-badge)]()
---
¿Qué es ContaCloud?
Sistema contable y administrativo completo construido desde cero, adaptado a la normativa colombiana. Cubre desde la contabilidad formal (libro diario, libro mayor, PUC) hasta la operación diaria del negocio (ventas, caja, inventario, nómina), todo en una sola plataforma multiempresa.
Diseñado para pequeñas y medianas empresas que necesitan cumplir con sus obligaciones contables sin pagar licencias costosas de software especializado.
---
🚀 Demo en vivo
👉 Abrir ContaCloud
No requiere instalación. Corre directo en el navegador.
---
🏗️ Arquitectura del sistema
```
ContaCloud
├── 📒 Contabilidad Formal
│   ├── Libro diario con asientos automáticos por módulo
│   ├── Libro mayor con saldos por cuenta PUC
│   ├── Cuentas PUC colombiano completo
│   └── Cierre de períodos contables
│
├── 🧾 Facturación & Ventas
│   ├── Facturación con consecutivo automático
│   ├── Campos DIAN: CUFE, resolución, estado de emisión
│   ├── Gestión de caja: apertura, cierre, cuadre
│   ├── Múltiples métodos de pago
│   └── Registro de cambio y recibido
│
├── 📦 Inventario
│   ├── Productos con código de barras, SKU, marca
│   ├── Control de stock con stock mínimo
│   ├── Movimientos de inventario trazables
│   ├── Categorías por empresa
│   └── Costos y precios con impuestos
│
├── 👷 Nómina Colombiana
│   ├── Salario base + auxilio de transporte
│   ├── Horas extras: diurnas, nocturnas, festivas
│   ├── Deducciones: salud (4%), pensión (4%)
│   ├── Bonos, anticipos y otras deducciones
│   └── Liquidación por quincena o mes
│
├── 👥 Clientes & Terceros
│   ├── Registro con documento, ciudad, tipo
│   └── Historial de transacciones
│
├── 💰 Caja & Tesorería
│   ├── Múltiples cajas por empresa
│   ├── Apertura con monto inicial
│   ├── Cierre con cuadre por método de pago
│   └── Movimientos con trazabilidad completa
│
└── 🔐 Seguridad & Administración
    ├── Multiempresa con módulos activables por empresa
    ├── Panel de administración global
    ├── 2FA (autenticación de dos factores)
    ├── Auditoría global: usuario, IP, dispositivo, acción
    ├── Roles y permisos por módulo
    ├── Control de intentos fallidos de login
    └── Límites configurables por empresa (usuarios, trabajadores)
```
---
🗄️ Modelo de datos — 28 módulos
Área	Hojas / Entidades
Contabilidad	LIBRO_DIARIO, LIBRO_MAYOR
Usuarios & Seguridad	USUARIOS, ROLES, PERMISOS, AUDITORIA_GLOBAL
Empresas	EMPRESAS, CONFIG_EMPRESA, EMPRESA_MODULOS, EMPRESA_LIMITES
Facturación	FACTURAS, FACTURA_DETALLE, CONSECUTIVOS
Inventario	INVENTARIO, CATEGORIAS_PRODUCTOS, MOVIMIENTOS_INVENTARIO
Nómina	TRABAJADORES, NOMINA
Caja	CAJAS, CAJAS_APERTURA, CAJAS_CIERRE, MOVIMIENTOS_CAJA
Clientes	CLIENTES
Administración	ADMIN_PANEL, CONFIG
---
🛠️ Stack tecnológico
Tecnología	Uso
Google Apps Script	Backend, lógica de negocio, APIs
JavaScript (ES6+)	Frontend, interactividad
HTML5 / CSS3	Interfaces de usuario
Google Sheets	Base de datos relacional
PUC Colombia	Plan Único de Cuentas oficial
---
✨ Características destacadas
Contabilidad automática — cada venta, gasto o nómina genera su asiento en el libro diario
Nómina legal colombiana — calcula automáticamente todas las deducciones y recargos según la ley
Facturación DIAN-ready — campos CUFE, resolución y estado de emisión listos para factura electrónica
2FA incluido — autenticación de dos factores para mayor seguridad
Auditoría completa — cada acción queda registrada con usuario, IP, dispositivo y timestamp
Multiempresa real — un solo sistema para gestionar múltiples negocios con datos aislados
Módulos activables — cada empresa activa solo los módulos que necesita
---
🇨🇴 Adaptación a normativa colombiana
Característica	Detalle
Plan de cuentas	PUC colombiano completo
Nómina	Salud 4%, Pensión 4%, HED, HEN, HEDF, HENF
Facturación	Campos DIAN: CUFE, resolución de facturación
Impuestos	IVA configurable por producto
Períodos	Cierre contable por mes/año
---
💼 ¿Tienes una pyme en Colombia?
ContaCloud está disponible como SaaS. Sin instalaciones, sin complicaciones.
📩 Contáctame: github.com/tovarh688
---
👨‍💻 Autor
Héctor Tovar — Desarrollador Full Stack
Bucaramanga, Colombia · Disponible para trabajo remoto
![GitHub](https://img.shields.io/badge/GitHub-tovarh688-181717?style=flat&logo=github)

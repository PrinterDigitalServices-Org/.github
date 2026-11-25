# 💻 Printer Digital Services — Ecosistema Digital & Software

> Ecosistema de plataformas web corporativas, herramientas de prospección y automatización comercial, plantillas frontend de alto rendimiento y soluciones digitales orientadas a conversión, SEO técnico y despliegue continuo.

## 🚀 Arquitectura Técnica del Ecosistema

Cada proyecto opera con enfoque de producción, alta velocidad de carga, cumplimiento de **Core Web Vitals** y despliegue automatizado:

- **Frontend:** [Next.js 15/16 (App Router)](https://nextjs.org/) + [React 19](https://react.dev/) + [Tailwind CSS v4](https://tailwindcss.com/) + componentes [Radix UI](https://www.radix-ui.com/) / shadcn.
- **Animaciones & UI:** Micro-interacciones a 60 fps con [GSAP](https://greensock.com/gsap/), Framer Motion y visualización de datos con Recharts.
- **Datos & ORM:** [PostgreSQL](https://www.postgresql.org/) (acceso directo `pg` y [Prisma ORM](https://www.prisma.io/)) con validación de esquemas mediante [Zod](https://zod.dev/).
- **Infraestructura & CI/CD:** Empaquetado Docker multi-stage con `pnpm` y despliegue automatizado mediante [Dokploy](https://dokploy.com/) y Traefik.
- **Pagos & Automatización:** Integración con [Stripe](https://stripe.com/), campañas SMTP con Nodemailer, scrapers B2B y publicación multicanal con IA.

## 📦 Directorio de Repositorios y Plataformas

| Repositorio | Propósito / Especialidad | Stack Principal |
| --- | --- | --- |
| **PrinterDigitalServices** | Web corporativa, calculadora de presupuestos, CRM de leads, clientes Stripe y radar B2B | Next.js 16, React 19, PostgreSQL (`pg`), Stripe |
| **web-templates** | Librería oficial de starters frontend (*ecommerce*, *blog*, *landing GSAP*, *enterprise*) | Next.js 15+, Tailwind CSS, Radix UI, GSAP |
| **Resource-eu** | Portal de recursos y directorio geolocalizado en Europa | Next.js, React 19, Tailwind CSS, Leaflet |
| **PublicadorRedesSociales** | Publicador automático multimarca en redes sociales con generación asistida por IA | Python, Buffer, Google GenAI, Pillow |

## 🎯 Pilares Técnicos y Estándares

- **Diseño Anti-IA Slop & Rendimiento:** Interfaces limpias, jerarquía visual cuidada, tipografía legible y auditorías automáticas de calidad y Core Web Vitals.
- **Automatización Comercial Responsable:** Flujos de prospección, seguimiento Kanban y campañas de correo con salvaguardas anti-spam integradas.
- **Modularidad & Reutilización:** Base de plantillas listas para producción (`web-templates`) que aceleran el lanzamiento de nuevos verticales y clientes.
- **Despliegue Reproducible:** Contenedores Docker estandarizados y pipelines conectados directamente a Dokploy.

## 📬 Contacto

- **Organización:** Printer Digital Services
- **GitHub:** [PrinterDigitalServices-Org](https://github.com/PrinterDigitalServices-Org)

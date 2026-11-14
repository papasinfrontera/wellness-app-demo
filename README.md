# WELLNESS APP — Fundación tecnológica (Sprint 6.1)

Este repositorio contiene el **nuevo código de arquitectura** para WELLNESS APP. El demo actual en Vercel permanece separado y no será reemplazado antes de validar la migración.

## Objetivo

Crear una plataforma longitudinal con Next.js, TypeScript y PostgreSQL/Supabase, preparada desde el inicio para documentos de laboratorio, exportaciones WHOOP, una base de conocimiento científico RAG y el motor independiente de Clinical Rules.

## Seguridad

**Repositorio público: NUNCA guardar datos reales de pacientes, informes clínicos, tokens, contraseñas, exportaciones WHOOP ni PDFs.** Solo código, ejemplos sintéticos y documentación técnica. Los archivos personales irán a almacenamiento privado con políticas de acceso por usuario.

## Estado

- Sprint 6.1: estructura y contratos iniciales.
- Supabase: pendiente de crear y conectar.
- Importación PDF y WHOOP: pendientes de implementar.
- IA + base científica: arquitectura definida; sin conexión aún.

## Gobernanza científica

El equipo técnico puede incorporar fuentes candidatas. Las fuentes no pasan a estado `approved` para interpretaciones clínicas sin revisión y aprobación del Consejo Médico-Científico.

## Entornos

- Demo estable existente: `https://wellness-app-demo-sprint1-papasinfronteras-projects.vercel.app`
- Nueva aplicación Next.js: desarrollo aislado hasta la aprobación de migración.

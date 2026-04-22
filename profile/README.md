# Aceti-Oxigeno, S.A. — Departamento de Cómputo

![Organización](https://img.shields.io/badge/Organizaci%C3%B3n-Aceti--Oxigeno%2C%20S.A.-0C447C?style=flat)
![Ubicación](https://img.shields.io/badge/Ubicaci%C3%B3n-Panam%C3%A1-3B6D11?style=flat)
![Migración](https://img.shields.io/badge/Migraci%C3%B3n-En%20progreso-BA7517?style=flat)
![Equipo](https://img.shields.io/badge/Equipo-4%20integrantes-534AB7?style=flat)

> Centro de código y documentación técnica del departamento. Aquí centralizamos todos los sistemas, estándares y responsables del área.

---

## Repositorios activos

| Repositorio | Tecnología | Estado | Descripción | Responsable |
| :--- | :--- | :--- | :--- | :--- |
| [informe-diario-caja](../../informe-diario-caja) | ![Java](https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white) | ![Migrado](https://img.shields.io/badge/Migrado-27500A?style=flat) | Reporte diario del cierre de caja | Christian Navarro |
| _Próximo sistema_ | — | ![Disponible](https://img.shields.io/badge/Disponible-888780?style=flat) | — | — |
| _Próximo sistema_ | — | ![Disponible](https://img.shields.io/badge/Disponible-888780?style=flat) | — | — |

---

## Sistemas pendientes de migrar a repositorio

Los siguientes sistemas están en uso pero aún no cuentan con repositorio ni documentación formal. La prioridad es ir incorporándolos uno a uno conforme se vayan documentando.

| Sistema | Área | Tecnología | Prioridad |
| :--- | :--- | :--- | :--- |
| Sistema 1 | Por identificar | Por identificar | ![Alta](https://img.shields.io/badge/Alta-A32D2D?style=flat) |
| Sistema 2 | Por identificar | Por identificar | ![Alta](https://img.shields.io/badge/Alta-A32D2D?style=flat) |
| Sistema 3 | Por identificar | Por identificar | ![Media](https://img.shields.io/badge/Media-BA7517?style=flat) |
| Sistema 4 | Por identificar | Por identificar | ![Media](https://img.shields.io/badge/Media-BA7517?style=flat) |
| Sistema 5 | Por identificar | Por identificar | ![Baja](https://img.shields.io/badge/Baja-3B6D11?style=flat) |
| _+ Agregar_ | — | — | — |

> **Proceso recomendado:** Al migrar cada sistema, completar su fila en la tabla de arriba con el enlace al repositorio y llenar su `README.md` usando el template de estándares de abajo.

---

## Equipo

| Rol | Nombre | Responsabilidades |
| :--- | :--- | :--- |
| ![Jefe](https://img.shields.io/badge/Jefe%20de%20C%C3%B3mputo-0C447C?style=flat) | Por definir | Coordinación general, decisiones técnicas, priorización de migraciones |
| ![Soporte](https://img.shields.io/badge/Soporte%20T%C3%A9cnico-085041?style=flat) | Por definir | Infraestructura, servidores, resolución de incidencias |
| ![Programador](https://img.shields.io/badge/Programador-3C3489?style=flat) | Por definir | Desarrollo, mantenimiento y documentación de sistemas |
| ![Digitalizador](https://img.shields.io/badge/Digitalizador-633806?style=flat) | Por definir | Gestión de datos, digitalización de procesos y documentos |

---

## Estándares mínimos por repositorio

Todo repositorio creado en esta organización **debe** incluir en su `README.md`:

1. **Descripción** — qué hace la aplicación y para qué área de la empresa.
2. **Servidor** — IP o nombre del servidor donde está desplegada, incluido el puerto.
3. **Base de datos** — motor utilizado (MySQL, PostgreSQL, etc.) y nombre del schema.
4. **Variables de entorno** — archivo `.env.example` en la raíz con todas las variables necesarias.
5. **Cómo levantar el ambiente local** — requisitos previos y comandos paso a paso.
6. **Responsable y fecha** — nombre del responsable técnico y fecha de última actualización del README.

### Template para nuevos repositorios

```markdown
# Nombre del Sistema

Descripción breve de qué hace y para qué área sirve.

## Requisitos
- Java 17 / Node 18 / PHP 8 (según aplique)
- Base de datos: MySQL 8 — schema: `nombre_schema`

## Configuración
Copiar `.env.example` a `.env` y completar los valores:

\`\`\`env
DB_HOST=
DB_PORT=
DB_NAME=
DB_USER=
DB_PASS=
\`\`\`

## Cómo ejecutar localmente

\`\`\`bash
# Instalar dependencias
...

# Iniciar la aplicación
...
\`\`\`

## Servidor de producción
- **IP / Host:** `000.000.0.0`
- **Puerto:** `8080`
- **Ruta de despliegue:** `/opt/app/nombre-sistema`

## Responsable
**Nombre:** Por asignar  
**Última actualización del README:** AAAA-MM-DD
```

---

## Convenciones de nombres de repositorios

Todos los repositorios deben seguir el formato en minúsculas con guiones:

```
nombre-descriptivo-del-sistema
```

| Correcto | Incorrecto |
| :--- | :--- |
| `informe-diario-caja` | `InformeDiarioCaja` |
| `control-inventario` | `sistema_inventario_v2` |
| `api-facturacion` | `APIFacturacion_FINAL` |

---

![Última actualización](https://img.shields.io/badge/Última%20actualización-Abril%202026-D3D1C7?style=flat)

*Departamento de Cómputo · Aceti-Oxigeno, S.A. · Panamá*

# Aceti-Oxigeno, S.A. — Departamento de Cómputo

> Centro de código y documentación técnica del departamento. Aquí centralizamos todos los sistemas, estándares y responsables del área.

---

## Repositorios activos

| Repositorio | Tecnología | Estado | Descripción | Responsable |
| :--- | :--- | :--- | :--- | :--- |
| [informe-diario-caja](../../informe-diario-caja) | Java · Spring Boot |  Migrado | Reporte diario del cierre de caja | Christian Navarro |
| _Próximo sistema_ | Por definir |  Disponible | — | — |
| _Próximo sistema_ | Por definir |  Disponible | — | — |

---

## Sistemas pendientes de migrar a repositorio

Los siguientes sistemas están en uso pero aún no cuentan con repositorio ni documentación formal. La prioridad es ir incorporándolos uno a uno.

| Sistema | Área | Tecnología | Prioridad |
| :--- | :--- | :--- | :--- |
| Sistema 1 | Por identificar | Por identificar | Alta |
| Sistema 2 | Por identificar | Por identificar | Alta |
| Sistema 3 | Por identificar | Por identificar | Media |
| Sistema 4 | Por identificar | Por identificar | Media |
| Sistema 5 | Por identificar | Por identificar | Baja |
| _+ Agregar_ | — | — | — |

> **Proceso recomendado:** Al migrar cada sistema, completar la tabla de arriba con su repositorio y llenar el `README.md` correspondiente usando el template de estándares.

---

## Equipo

| Rol | Nombre | Responsabilidades principales |
| :--- | :--- | :--- |
| Jefe de Cómputo | Por definir | Coordinación general, decisiones técnicas, priorización de migraciones |
| Soporte Técnico | Por definir | Infraestructura, servidores, resolución de incidencias |
| Programador | Por definir | Desarrollo, mantenimiento y documentación de sistemas |
| Digitalizador | Por definir | Gestión de datos, digitalización de procesos y documentos |

---

## Estándares mínimos por repositorio

Todo repositorio creado en esta organización **debe** incluir en su `README.md`:

1. **Descripción** — qué hace la aplicación y para qué área de la empresa.
2. **Servidor** — IP o nombre del servidor donde está desplegada, incluido el puerto.
3. **Base de datos** — motor utilizado (MySQL, PostgreSQL, etc.) y nombre del schema.
4. **Variables de entorno** — archivo `.env.example` en la raíz con todas las variables necesarias.
5. **Cómo levantar el ambiente local** — requisitos previos y comandos paso a paso.
6. **Responsable y fecha** — nombre del responsable técnico y fecha de última actualización del README.

### Template rápido para nuevos repositorios

```markdown
# Nombre del Sistema

Descripción breve de qué hace y para qué área sirve.

## Requisitos
- Java 17 / Node 18 / PHP 8 (según aplique)
- Base de datos: MySQL 8 — schema: `nombre_schema`

## Configuración
Copiar `.env.example` a `.env` y completar los valores:
```env
DB_HOST=
DB_PORT=
DB_NAME=
DB_USER=
DB_PASS=
```

## Cómo ejecutar localmente
```bash
# Instalar dependencias
...

# Iniciar la aplicación
...
```

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

Para mantener consistencia, todos los repositorios deben seguir el formato:

```
nombre-descriptivo-del-sistema
```

Ejemplos correctos: `informe-diario-caja`, `control-inventario`, `api-facturacion`  
Ejemplos incorrectos: `SistemaVentas`, `sistema_ventas_v2_FINAL`

---

*Departamento de Cómputo · Aceti-Oxigeno, S.A. · Actualizado: Abril 2026*

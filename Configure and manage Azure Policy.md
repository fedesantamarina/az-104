# Configure and Manage Azure Policy

## Introducción

Azure Policy es una característica de Azure que permite a los administradores definir requisitos y restricciones específicas para los recursos en un ambiente de Azure. Mediante la creación y aplicación de políticas, se garantiza que los recursos se mantengan en conformidad con las reglas corporativas y las directrices de cumplimiento.

```mermaid
graph TD;
  A(Introducción) --> B1(Definición de Azure Policy)
  A --> B2(Importancia)
  B1 --> C1(Requisitos)
  B1 --> C2(Restricciones)
  B2 --> C3(Reglas corporativas)
  B2 --> C4(Directrices de cumplimiento)
```

**Glosario**

| Término                  | Descripción                                                  |
|-------------------------|--------------------------------------------------------------|
| Azure Policy             | Herramienta para crear y aplicar políticas en Azure.         |
| Reglas corporativas     | Normas establecidas por una organización.                     |
| Directrices de cumplimiento | Regulaciones que deben seguirse en un entorno empresarial. |

## Creación de Políticas

Para crear una política en Azure, primero debes acceder al portal de Azure y navegar hasta el servicio "Azure Policy". Aquí, puedes optar por utilizar políticas predefinidas o crear políticas personalizadas mediante el uso de plantillas de Azure Resource Manager (ARM).

```mermaid
graph TD;
  A(Creación de Políticas) --> B1(Acceso al portal)
  A --> B2(Servicio Azure Policy)
  B1 --> C1(Autenticación)
  B2 --> C2(Políticas predefinidas)
  B2 --> C3(Políticas personalizadas)
  C3 --> D1(Plantillas ARM)
```

**Glosario**

| Término                  | Descripción                                                   |
|-------------------------|---------------------------------------------------------------|
| Azure Resource Manager  | Servicio que facilita la administración de recursos en Azure. |
| Plantillas ARM          | Plantillas para definir recursos y configuraciones en Azure.  |

### Ejemplo de Código

```json
{
  "policyRule": {
    "if": {
      "field": "type",
      "equals": "Microsoft.Storage/storageAccounts"
    },
    "then": {
      "effect": "deny"
    }
  }
}
```

## Aplicación de Políticas

Una vez creada una política, el siguiente paso es aplicarla a un grupo de recursos o a una suscripción de Azure. De esta manera, se puede asegurar que los recursos estén en conformidad con las directrices especificadas.

```mermaid
graph TD;
  A(Aplicación de Políticas) --> B1(Grupo de recursos)
  A --> B2(Suscripción de Azure)
  B1 --> C1(Asignar Política)
  B2 --> C2(Asignar Política)
```

**Glosario**

| Término             | Descripción                                      |
|--------------------|--------------------------------------------------|
| Grupo de recursos  | Conjunto de recursos relacionados en Azure.      |
| Suscripción de Azure| Acuerdo de licencia y facturación con Azure.     |

## Monitorización y Cumplimiento

Una vez aplicadas las políticas, Azure Policy proporciona herramientas para monitorizar el estado de cumplimiento de los recursos. Se pueden generar informes y alertas para mantenerse actualizado sobre cualquier desviación.

```mermaid
graph TD;
  A(Monitorización y Cumplimiento) --> B1(Herramientas de monitorización)
  A --> B2(Estado de cumplimiento)
  B1 --> C1(Informes)
  B1 --> C2(Alertas)
```

**Glosario**

| Término               | Descripción                                         |
|----------------------|-----------------------------------------------------|
| Estado de cumplimiento| Nivel de adherencia a las políticas establecidas.   |
| Informes              | Documentos que detallan el estado de los recursos.  |
| Alertas               | Notificaciones sobre desviaciones de la política.  |

## Cuadro Sinóptico

| Sección                      | Acciones Clave                                        | Herramientas y Términos Asociados   |
|------------------------------|--------------------------------------------------------|-------------------------------------|
| Introducción                 | Comprender qué es Azure Policy y su importancia.       | Azure Policy, Reglas Corporativas   |
| Creación de Políticas        | Acceder a Azure, usar el servicio Azure Policy.        | Azure Resource Manager, Plantillas ARM |
| Aplicación de Políticas      | Asignar políticas a grupos de recursos o suscripciones.| Grupo de recursos, Suscripción de Azure |
| Monitorización y Cumplimiento| Utilizar herramientas para verificar el cumplimiento.  | Estado de cumplimiento, Informes    |

Espero que esta información te ayude en tu preparación para el examen AZ-104.

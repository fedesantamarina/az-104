### Manage Subscriptions

Cuando trabajamos con Microsoft Azure, la gestión de suscripciones es un componente esencial para asegurar el correcto despliegue y mantenimiento de los recursos. Esta gestión nos ayuda a administrar costos, recursos y usuarios de manera eficiente.

```mermaid
graph TD;
    A[Manage Subscriptions] --> B[Cost Management];
    A --> C[Resource Allocation];
    A --> D[User Management];
    A --> E[Role-Based Access Control];
    A --> F[Policy Assignment];
```

**Sin título**

| Término | Descripción |
|---------|-------------|
| Manage Subscriptions | Proceso de administración y control de suscripciones en Azure. |
| Cost Management | Supervisión y administración de costos asociados. |
| Resource Allocation | Distribución y asignación de recursos dentro de la suscripción. |
| User Management | Administración de usuarios que tienen acceso a la suscripción. |
| Role-Based Access Control | Control de acceso basado en roles. |
| Policy Assignment | Asignación de políticas para recursos dentro de la suscripción. |

#### Control de Costos

En Azure, es posible mantener un control estricto sobre los costos a través de diversas herramientas como Azure Cost Management y Azure Advisor. Estas herramientas ofrecen insights en tiempo real sobre el gasto, y brindan recomendaciones para optimizar los recursos.

```mermaid
graph TD;
    A1[Cost Control] --> B1[Azure Cost Management];
    A1 --> C1[Azure Advisor];
    A1 --> D1[Budgets];
    A1 --> E1[Cost Analysis];
```

**Sin título**

| Término | Descripción |
|---------|-------------|
| Cost Control | Gestión y control del gasto en Azure. |
| Azure Cost Management | Herramienta para la administración de costos. |
| Azure Advisor | Ofrece recomendaciones para optimizar recursos. |
| Budgets | Presupuestos para controlar gastos. |
| Cost Analysis | Análisis detallado de los costos incurridos. |

#### Administración de Recursos

La administración de recursos en una suscripción de Azure puede hacerse a través de Azure Resource Manager, que permite agrupar, organizar y administrar recursos de manera efectiva. Puedes utilizar plantillas ARM para automatizar el despliegue de recursos.

```mermaid
graph TD;
    A2[Resource Management] --> B2[Azure Resource Manager];
    A2 --> C2[Resource Groups];
    A2 --> D2[ARM Templates];
    A2 --> E2[Resource Locks];
```

**Sin título**

| Término | Descripción |
|---------|-------------|
| Resource Management | Gestión de recursos en la suscripción. |
| Azure Resource Manager | Plataforma para la administración de recursos. |
| Resource Groups | Agrupaciones de recursos. |
| ARM Templates | Plantillas para el despliegue automático de recursos. |
| Resource Locks | Bloqueos para prevenir cambios accidentales. |

#### Control de Acceso Basado en Roles (Role-Based Access Control, RBAC)

Azure RBAC permite asignar permisos específicos a usuarios, grupos y aplicaciones, dependiendo de sus roles dentro de la organización. Este control de acceso es crucial para mantener la seguridad y la integridad de los recursos de Azure.

```mermaid
graph TD;
    A3[RBAC] --> B3[Users];
    A3 --> C3[Roles];
    A3 --> D3[Permissions];
    A3 --> E3[Resource Scope];
```

**Sin título**

| Término | Descripción |
|---------|-------------|
| RBAC | Control de acceso basado en roles. |
| Users | Usuarios que acceden a los recursos. |
| Roles | Roles asignados a los usuarios. |
| Permissions | Permisos otorgados o denegados. |
| Resource Scope | Ámbito del recurso al que se aplica el RBAC. |

#### Asignación de Políticas

Puedes asignar políticas a nivel de suscripción, grupo de recursos o recurso individual para garantizar que los recursos cumplan con ciertos requisitos y normativas.

```mermaid
graph TD;
    A4[Policy Assignment] --> B4[Subscription Level];
    A4 --> C4[Resource Group Level];
    A4 --> D4[Individual Resource Level];
```

**Sin título**

| Término | Descripción |
|---------|-------------|
| Policy Assignment | Asignación de políticas a recursos. |
| Subscription Level | Nivel de suscripción. |
| Resource Group Level | Nivel de grupo de recursos. |
| Individual Resource Level | Nivel de recurso individual. |

### Cuadro Sinóptico

```mermaid
graph TD;
    A[Manage Subscriptions] --> B1[Cost Control];
    A --> B2[Resource Management];
    A --> B3[RBAC];
    A --> B4[Policy Assignment];
    B1 --> C1[Azure Cost Management];
    B1 --> C2[Azure Advisor];
    B2 --> C3[Azure Resource Manager];
    B2 --> C4[Resource Groups];
    B3 --> C5[Users];
    B3 --> C6[Roles];
    B4 --> C7[Subscription Level];
    B4 --> C8[Resource Group Level];
```

Espero que esta información te sea útil para manejar eficientemente las suscripciones en Azure y que te ayude a prepararte para tu examen AZ-104.

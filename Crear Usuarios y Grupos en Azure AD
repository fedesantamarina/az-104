# Crear Usuarios y Grupos en Azure AD (Azure Active Directory)

## Introducción

Azure Active Directory (Azure AD) es un servicio de identidad en la nube que proporciona capacidades de gestión de identidad y acceso. Una de las tareas fundamentales en la administración de Azure AD es la creación y gestión de usuarios y grupos. Esto es crucial para garantizar que las personas adecuadas tengan el acceso adecuado a los recursos correctos.

```mermaid
graph TD;
    A[Azure AD] --> B[Usuarios];
    A --> C[Grupos];
    B --> D[Creación];
    B --> E[Gestión];
    C --> F[Creación];
    C --> G[Gestión];
```

**Mini Glosario**

```mermaid
graph TD;
  A1[Azure AD] -->|Servicio de identidad| A2[Identidad]
  B1[Usuarios] -->|Entidades en Azure AD| B2[Entidades]
  C1[Grupos] -->|Colección de Usuarios| C2[Colección]
```

## Creación de Usuarios

Para crear un nuevo usuario en Azure AD, existen diversas formas. Puede hacerlo a través del portal de Azure, mediante PowerShell o a través de la API Graph de Microsoft.

### Portal de Azure

1. Navegue al Portal de Azure.
2. Vaya a "Azure Active Directory".
3. Haga clic en "Usuarios" y luego en "Nuevo usuario".

### PowerShell

Utilice el comando `New-AzADUser` para crear un nuevo usuario.

```powershell
New-AzADUser -UserPrincipalName "user@domain.com" -DisplayName "User Name" -Password "UserPassword"
```

```mermaid
graph TD;
  A1[Creación de Usuarios] --> B1[Portal de Azure]
  A1 --> C1[PowerShell]
  B1 --> D1[Interfaz gráfica]
  C1 --> D2[Scripting]
```

**Mini Glosario**

```mermaid
graph TD;
  A1[Portal de Azure] -->|Interfaz Web| A2[Interfaz]
  B1[PowerShell] -->|Lenguaje de Scripting| B2[Scripting]
```

## Creación de Grupos

La creación de grupos facilita la administración al permitir asignar recursos y permisos a una colección de usuarios en lugar de a usuarios individuales.

### Portal de Azure

1. Navegue al Portal de Azure.
2. Vaya a "Azure Active Directory".
3. Haga clic en "Grupos" y luego en "Nuevo grupo".

### PowerShell

Utilice el comando `New-AzADGroup` para crear un nuevo grupo.

```powershell
New-AzADGroup -DisplayName "Group Name" -MailNickname "GroupMail"
```

```mermaid
graph TD;
  A2[Creación de Grupos] --> B2[Portal de Azure]
  A2 --> C2[PowerShell]
  B2 --> D3[Interfaz gráfica]
  C2 --> D4[Scripting]
```

**Mini Glosario**

```mermaid
graph TD;
  A3[Portal de Azure] -->|Interfaz Web| A4[Interfaz]
  B3[PowerShell] -->|Lenguaje de Scripting| B4[Scripting]
```

## Cuadro Sinóptico

```mermaid
graph LR;
  A[Azure AD] -->|Gestiona| B1[Usuarios]
  A -->|Gestiona| B2[Grupos]
  B1 -->|Creados por| C1[Portal de Azure]
  B1 -->|Creados por| C2[PowerShell]
  B2 -->|Creados por| C3[Portal de Azure]
  B2 -->|Creados por| C4[PowerShell]
```

Al comprender estos aspectos fundamentales de la creación y gestión de usuarios y grupos en Azure AD, estará mejor preparado para administrar efectivamente los recursos y permisos dentro de su entorno de Azure.

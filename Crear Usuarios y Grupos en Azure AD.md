# Crear Usuarios y Grupos en Azure AD

Azure Active Directory (Azure AD) es el servicio de directorio y gestión de identidad que ofrece Microsoft Azure. La gestión de objetos en Azure AD, como usuarios y grupos, es una tarea esencial para el administrador de Azure. Aquí te explicaré detalladamente cómo crear usuarios y grupos en Azure AD.

## Crear Usuarios en Azure AD

### Portal de Azure
1. Ve al portal de Azure y navega hasta Azure AD.
2. Selecciona la opción "Usuarios" y luego "Nuevo Usuario".
3. Completa la información requerida y presiona "Crear".

```azurecli
az ad user create --user-principal-name usuario@dominio.com --display-name "Usuario Ejemplo"
```

```mermaid
graph TD
  A[Azure AD] -->|Portal de Azure| B[Crear Usuario]
  B --> C[Información Requerida]
  B -.-> D[Azure CLI]
```

### Azure CLI
Otra forma de crear un usuario es utilizando la Azure Command-Line Interface (CLI).

```azurecli
az ad user create --user-principal-name usuario@dominio.com --display-name "Usuario Ejemplo"
```

```mermaid
graph TD
  A[Azure AD] -->|Azure CLI| B[Crear Usuario]
  B --> C[Información Requerida]
```

#### Alternativas
- Utilizar PowerShell para automatizar la creación de usuarios.
- Importar usuarios desde un archivo CSV.

## Crear Grupos en Azure AD

### Portal de Azure
1. Ve al portal de Azure y navega hasta Azure AD.
2. Selecciona la opción "Grupos" y luego "Nuevo Grupo".
3. Completa la información requerida y presiona "Crear".

```mermaid
graph TD
  A[Azure AD] -->|Portal de Azure| B[Crear Grupo]
  B --> C[Información Requerida]
```

### Azure CLI
Al igual que con los usuarios, también puedes utilizar la Azure CLI para crear grupos.

```azurecli
az ad group create --name "NombreDelGrupo" --mail-nickname "Alias"
```

```mermaid
graph TD
  A[Azure AD] -->|Azure CLI| B[Crear Grupo]
  B --> C[Información Requerida]
```

#### Alternativas
- Utilizar PowerShell para automatizar la creación de grupos.
- Importar grupos desde un archivo CSV.

```mermaid
graph TD
  A[Crear Usuarios y Grupos en Azure AD]
  A --> B1[Crear Usuarios en Azure AD]
  A --> B2[Crear Grupos en Azure AD]
  B1 --> C1[Portal de Azure]
  B1 --> C2[Azure CLI]
  B2 --> D1[Portal de Azure]
  B2 --> D2[Azure CLI]
```

## Glosario
```mermaid
classDiagram
  AzureAD --|> Usuario : Crea
  AzureAD --|> Grupo : Crea
  PortalAzure --|> AzureAD : Accede
  AzureCLI --|> AzureAD : Accede
  Usuario : +user-principal-name
  Usuario : +display-name
  Grupo : +name
  Grupo : +mail-nickname
```

## Cuadro Sinóptico

| Tema            | Portal de Azure | Azure CLI      | Alternativas      |
|-----------------|-----------------|----------------|-------------------|
| Crear Usuarios  | ✔️              | ✔️             | PowerShell, CSV   |
| Crear Grupos    | ✔️              | ✔️             | PowerShell, CSV   |
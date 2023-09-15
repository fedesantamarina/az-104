graph TD
    A[Crear Storage Account] --> B1[Subscription<br/>Suscripción de Azure]
    A --> B2[Resource Group<br/>Grupo de recursos]
    A --> B3[Nombre de Storage Account<br/>Nombre único]
    A --> B4[Location<br/>Ubicación geográfica]
    A --> B5[Performance<br/>Rendimiento]
    A --> B6[Account Kind<br/>Tipo de cuenta]
    A --> B7[Replication<br/>Replicación]
    A --> B8[Access Tier<br/>Nivel de acceso]
    A --> B9[Networking<br/>Configuración de red]
    A --> B10[Data Protection<br/>Protección de datos]
    A --> B11[Advanced<br/>Opciones avanzadas]
    A --> B12[Tags<br/>Etiquetas]
    
    B5 --> C1[Standard<br/>HDD]
    B5 --> C2[Premium<br/>SSD]
    
    B6 --> D1[BlobStorage]
    B6 --> D2[BlockBlobStorage]
    B6 --> D3[FileStorage]
    B6 --> D4[StorageV2]
    B6 --> D5[Storage]
    
    B7 --> E1[Locally-redundant storage LRS<br/>Local]
    B7 --> E2[Geo-redundant storage GRS<br/>Geo]
    B7 --> E3[Read-access geo-redundant storage RA-GRS<br/>Geo-lectura]
    B7 --> E4[Zone-redundant storage ZRS<br/>Zonas]
    
    B8 --> F1[Hot<br/>Frecuente]
    B8 --> F2[Cool<br/>Raro]
    
    B9 --> G1[Public endpoint<br/>Público]
    B9 --> G2[Private endpoint<br/>Privado]
    
    B10 --> H1[Soft delete<br/>Borrado suave]
    B10 --> H2[Point-in-time restore<br/>Restaurar punto]
    B10 --> H3[Versioning<br/>Versionado]
    
    B11 --> I1[Secure transfer<br/>Transfer. segura]
    B11 --> I2[Azure AD<br/>Azure AD]
    B11 --> I3[Large file shares<br/>Archivos grandes]

# Tutorial para control de versiones en FlyWay para SQLServer.

### Introducción:
La idea de este tutorial és tener un howto de como mantener un control de versiones de nuestra base de dato SQL mediante el uso de las migrations.

### Prerequisitos:
FlyWay usa el protocolo tcp/ip para poder conectar con la base de datos por lo que el primer requisito es Activar el protocolo de TCP/IP desde:
    SQL Server Configuration Manager > Configuración de red de SQL Server > Protocolos de MSSQLSERVER > TCP/IP
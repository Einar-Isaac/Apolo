## Para instalar la aplicación solo descarguen el .exe y ejecútenlo :v
* Es para Windows 10 / 11 x64, pesa 80.25 MB, autocontenido con su propio entorno de ejecución integrado (i.e. no ocupas instalar java).
* Del almacenamiento, con 250 MB de espacio libre en disco una vez instalada la aplicación no hay problema.
* En cuanto a la ram, tiene un límite asignado de 512 MB (`-Xms128m -Xmx512m`).
* Graficos acelerados por hardware mediante Direct3D con respaldo automático por software (`-Dprism.order=d3d,sw`), compatible tanto con una GPU dedicada como con los gráficos integrados.
* Se hizo en Java 21 y con JavaFX con gestión de memoria G1GC, empaquetada nativamente con `jpackage` y usando el WiX Toolset.
* Es 100% local, funciona offline, nada de cuentas ni servidores externos, todo se guarda de forma aislada en tu equipo en una base de datos SQLite.
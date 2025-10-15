# DSS-Project-SAST
Repositorio para el proyecto de SAST del curso Desarrollo Seguro de Software.

# Pasos para levantar Sonarqube
**Disclaimer**: Funcionó para Windows, no sé si funcionará para Linux.

En la raiz del repositorio, ejecutar:
```bash
docker-compose up -d
```

Esperar 2-3 minutos a que el servicio se levante, luego ingresar a:
```bash
http://localhost:9001
```

Ingresar las credenciales:
* Usuario: `admin`
* Contraseña: `admin`
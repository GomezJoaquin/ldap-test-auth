# README

Este es un script de Python para establecer una conexión y autenticarse en un servidor de directorio de Active Directory (AD) utilizando el módulo ldap3.

## Requisitos

- Python 3.x
- Módulo ldap3 instalado (puede instalarlo ejecutando `pip install ldap3`)

## Configuración

Antes de ejecutar el script, asegúrese de configurar los siguientes parámetros:

```python
server_address = 'address:389'
domain_name = 'gxctest.local'
username = 'user@' + domain_name
password = 'pass'
```

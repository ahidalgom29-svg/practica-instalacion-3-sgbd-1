# Práctica 3 SGBD
| SGBD | IP Base/servicio | Puerto | Usuario | Contraseña |
| :--- | :--- | :--- | :--- | :---- |
| **Oracle 23ai Free** | localhost / FREEPDB1 | 1521 | orauser | 8888 |
| **PostgreSQL 16** | localhost / dbpg | 5432 | pguser | 8888 |
| **MariaDB 11** | localhost / dbm | 3306 | muser | 8888 |

## Ejercicio 5: Conexiones desde otra máquina

Se han configurado las reglas en el cortafuegos UFW para permitir el acceso TCP a los puertos de PostgreSQL (5432) y MariaDB (3306) utilizando la IP de la Máquina Virtual (10.0.2.15).

* **PostgreSQL 16**: Permite conexiones en el puerto 5432 para el usuario `pguser` sobre la base `dbpg`
* **MariaDB 11**; Se autorizó la cuenta `'muser'@`%'` con clave 8888 sobre la base `dbm` en el puerto 3306.

 

import data base from back file, this may take a minute or 2 from schema backup, this is empty schema and you need to create admin user:
keycloak.sql

Place Mariadb Driver and in below path:
keycloak-12.0.4/modules/system/layers/keycloak/org/mariadb/

use modified config from standalone.xml to use external mariadb:
keycloak-12.0.4/standalone/configuration/standalone.xml



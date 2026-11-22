# Leonida GPS

Escribe una dirección real de Florida y te digo su equivalente aproximado en Leonida, el estado de GTA VI. También funciona al revés: escribes un lugar de GTA VI (Little Cuba, Port Gellhorn, Ambrosia…) o das clic en el mapa de Leonida, y te dice qué parte de Florida lo inspiró.

**Abrir:** https://leonida-gps.github.io

El sitio tiene contraseña. Lo que hay en este repo es la app ya cifrada (AES-256-GCM, con llave derivada por PBKDF2-SHA256), no el código fuente.

## Cómo calcula la ubicación

- Primero busca "gemelos": lugares del juego que la comunidad ya ligó con su versión real (por ejemplo, Ocean Drive con Ocean Beach).
- Con los gemelos más cercanos a tu dirección ajusta una transformación local de kilómetros reales a coordenadas del juego.
- Cada resultado trae su nivel de confianza: gemelo exacto, alta, media, inspiración regional, edificios reciclados (el juego solo tomó algunos edificios de esa zona y los puso en otro lado) o sin equivalente.

Es una aproximación de fans: Leonida comprime y reacomoda Florida, así que no hay una equivalencia 1 a 1.

## Créditos de datos

| Fuente | Uso | Licencia |
|---|---|---|
| [GTADB](https://map.gtadb.org/) y colaboradores ([repo](https://github.com/rolux/gtadb.org)) | Lugares del juego ligados a su contraparte real | CC BY 4.0 |
| [Leonida Atlas](https://github.com/navanem/gta6-leonida-atlas), mapa base comunitario Yanis v16 | Mapa de Leonida | CC BY 4.0 |
| © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright) (vía geo-maps) | Contorno de tierra de Florida | ODbL |
| [U.S. Census Bureau](https://www.census.gov/) (vía us-atlas y us-zip-centroids) | Condados, códigos postales y límites | Dominio público |
| [GeoNames](https://www.geonames.org/) (vía cities.json) | Ciudades de Florida | CC BY 4.0 |
| Overpass y Neonderthaw | Tipografías | SIL OFL 1.1 |

Proyecto de fans, no oficial. Sin relación con Rockstar Games ni Take-Two Interactive. Grand Theft Auto, GTA VI y Leonida son marcas de sus respectivos dueños.

Design by RXCHA

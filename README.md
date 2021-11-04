Download pbf here:
https://download.geofabrik.de/north-america/us.html

Convert pbf to postgis
https://osm2pgsql.org/examples/vector-tiles/

start Martin server
```
docker run -p 3000:3000 -e DATABASE_URL=postgresql://postgres@host.docker.internal/penntrails urbica/martin
```
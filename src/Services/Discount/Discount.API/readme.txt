--Setup PostgreSQL Docker database
docker pull postgres


-- Setup pgAdmin
pgadmin.org
docker pull dpage/pgadmin4

--Nuget Packages
Npgsql
Dapper

docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
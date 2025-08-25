# Neo4j_DB

# creacion imagen segun el Dockerfile
docker build -t dbneo4j:v1 .
# creacion del contenedor 
docker run -d --name dbneo4j -p 7474:7474 -p 7687:7687 dbneo4j:v1

<img width="1215" height="109" alt="Captura de pantalla 2025-08-24 221458" src="https://github.com/user-attachments/assets/e1012ed8-b0e9-4640-9cb5-f500d97f4afa" />
<img width="1204" height="199" alt="Captura de pantalla 2025-08-24 221534" src="https://github.com/user-attachments/assets/3723aea8-da73-4f96-8f7c-ee453e71aa06" />

# VisTrails and Docker
Dockerhub Repository
+ https://hub.docker.com/r/mrtiramisu/tb-wf/

# Instructions 
+ Finding average of e_inc_100k column

### Nigeria's averages 
    docker pull mrtiramisu/tb-wf:nigeria
    docker run mrtiramisu/tb-wf:nigeria

### Parameterized 
    docker pull mrtiramisu/tb-wf:parameterized
    docker run mrtiramisu/tb-wf:parameterized country=COUNTRY_NAME
    
Replace COUNTRY_NAME with the name of the country.

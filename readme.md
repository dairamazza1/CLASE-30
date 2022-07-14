-------- Comandos Usados -------- 1° Parte node server.js CLUSTER

forever start server.js 
forever list

pm2 start server.js
pm2 start server.js --name="serverCLUSTER" --watch -i max -- CLUSTER
pm2 start server.js --name="serverFORK" --watch -- FORK

pm2 list

2° Parte 

pm2 start server.js --name="serverCLUSTER" --watch -i max -- CLUSTER pm2 list

Configurar archivo nginx.conf
    start nginx
    tasklist /fi "imagename eq nginx.exe"
    ./nginx.exe -s reload

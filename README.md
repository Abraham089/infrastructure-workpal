<h1>Repositorio para la infraestructura de workpal</h1>

<h2>Crear el namespace antes de levantar los recursos del backend</h2>
<p>kubectl create namespace workpak</p>

<h2>Comando para iniciar el manifest del backend:</h2>
<p>kubectl apply -f /kubernetes/backend_manifest.yaml</p>

<b>Se utilizan las imagenes del backend y del frontend para los deployments, ambas imagenes ya estan automatizadas</b>

<p>Para ver la documentacion del backend, se expone un puerto en el service y se entra al puerto</p>

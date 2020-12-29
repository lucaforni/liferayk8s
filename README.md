# liferayk8s
Desplegando Liferay en Kubernetes

Repositorio de código con el fin de servir los ficheros necesarios para realizar el how-to explicado en el blog: https://liferay.dev/blogs/-/blogs/desplegando-liferay-7-3-en-kubernetes

kubectl apply -f database-deployment.yaml -n=liferay-demo

kubectl apply -f search-deployment.yaml -n=liferay-demo

kubectl apply -f liferay-deployment.yaml -n=liferay-demo
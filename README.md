# docker-ubuntu-apache2
Dockerfile com ubuntu e apache2

1. Clone projeto e entre na pasta
2. Executar `docker build -t ubuntu-apache2 .`
3. Executar `docker run -d --name container-ubuntu-apache2 -p 3000:80 ubuntu-apache2`
4. Abrir `http://localhost:3000` no seu navegador.

* docker exec -it `container-ubuntu-apache2 bash` para entrar no container.
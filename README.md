1 - git clone https://github.com/rogeriofonseca/springmvc-stand-alone.git && cd springmvc-stand-alone

2 - Construir e iniciar o container através do comando abaixo:
    $ docker build -t rogeriofonseca/tomcat-server:1.0 . && docker run -p 8383:8080 --rm -it rogeriofonseca/tomcat-server:1.0

3 - Acessar através do browser http://localhost:8383/springmvc-stand-alone/

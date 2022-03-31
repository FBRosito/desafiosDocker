# Desafios Docker - FullCycle 

### Desafio Go
Arquivos utilizados para fazer e publicar a imagem com menos de 2MB no Docker Hub estão na pasta **desafioGo**.

Ao digitar
```
docker run fernandorosito/codeeducation
```
O terminal retornará

```
Code.education Rocks!
```
Como na captura de tela a seguir:

![image](https://user-images.githubusercontent.com/80263741/161098646-cf7e5bba-4169-40e8-8073-b03c42066f93.png)

### Desafio Nginx com Node.js

O retorno da aplicação node.js para o nginx irá ser:
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```
Arquivos utilizados para fazer o *docker-compose* estão na pasta **desafioNginxNodeJs**

Para utilizar, basta digitar no seu terminal

```
git clone https://github.com/Noruegues/desafiosDocker.git

```

```
cd desafiosDocker/desafioNginxNodeJs

```

```
docker-compose up -d

```
Para confirmar que a aplicação NodeJs, o Nginx e o banco MySQL estão funcionando, podemos acessar a url **localhost:8080** na web ou utilizar o código **curl -i localhost:8080** que irá retornar o texto **Full Cycle Rocks!** pedido e um **nome aleatório**.

```
HTTP/1.1 200 OK
Server: nginx
Date: Thu, 31 Mar 2022 15:53:20 GMT
Content-Type: text/html; charset=utf-8
Content-Length: 94
Connection: keep-alive
X-Powered-By: Express
ETag: W/"5e-McpANGkdQe+dIxYpvz42tkRXKgM"


      <h1>Full Cycle Rocks!</h1>
      <ol>
        <li>Lori Ernser DVM</li>
      </ol>   
```
Como na captura de tela a seguir:

![image](https://user-images.githubusercontent.com/80263741/161101675-f29417f2-e091-4cd5-b72d-bbb51a6c8a3f.png)


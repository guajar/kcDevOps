#Enlace Nodepop -> http://ec2-34-231-196-177.compute-1.amazonaws.com/

#Enlace Django -> http://34.231.196.177

----------------------------------------------------------------------------------

# Nodepop - Documentación de uso:

*Para peticiones POST utilizar x-www-form-urlencoded*
*Para utilizar lenguaje deseado --> Accept-Language [en - es]


#Ejemplo de request para listar todos los anuncios:

*http://localhost:3000/apiv1/anuncios?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiNThlN2U1MmJmNzI5NGEyNjgwMzliYTQxIiwiaWF0IjoxNDkxNzczMzM3LCJleHAiOjE0OTIyMDUzMzd9.dahlYK8tqvxKJyOcpoy7rcY7X96Uo4E5QyIYXoNkQuM


***

###Login de usuario (conseguir autenticación)
* URL


*Para peticiones POST utilizar x-www-form-urlencoded*
*Para utilizar lenguaje deseado --> Accept-Language [en - es]

```
POST /apiv1/users/login
```

* PARÁMETROS (*OBLIGATORIOS)

```
	username: email del usuario
	password: contraseña del usuario

```

###Añadir usuarios:
* URL


*Para peticiones POST utilizar x-www-form-urlencoded*
*Para utilizar lenguaje deseado --> Accept-Language [en - es]

```
POST /apiv1/users/signup
```

* PARÁMETROS (* OBLIGATORIOS)

```
	*name: nombre
	*email: email del usuario
	*pass: contraseña

```



	- *José Antonio Maldonado*
# Api-Web-Inventarios
 Api de Inventarios para Web

# Probar en POSTMAN:

# Get Inventarios:
Obtiene todos los productos del inventario

localhost:8082/api/categoria

# Post Nueva Categoria:
Crea una nueva categoria 

localhost:8082/api/categoriaNew

Poner en post, luego en el body incluir un JSON con los siguientes datos:

{
"nombreCategoria":"Nombre Cat",
"descripcionCategoria":"Descripcion Categoria"
}

# Eliminar Categoria:
Eliminar categoria

localhost:8082/api/categoria/delete/{id a eliminar}


# Get Item:
Llamar a un solo item del inventario

localhost:8082/api/categoria/{id a buscar}

# Actualizar Item:
Actualizar item del inventario

localhost:8082/api/categoria/update/{Id a actualizar

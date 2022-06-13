# Uso de tests #

En una terminal hay que correr el programa con npm run dev, y en otra terminal ejecutar las pruebas de funcionamiento tanto con Axios como en 

### Con Axios

#### Obtener todos los productos de la base de datos

    Comando --> node ./tests/axios/axios.getProducts.js

#### Agregar un producto a la base de datos

    Comando --> node ./tests/axios/axios.addProduct.js

#### Modificar un producto en la base de datos a partir del campo _id proporcionado por mongoose

    Comando --> node ./tests/axios/axios.updateProduct.js

#### Eliminar un producto en la base de datos a partir del campo _id proporcionado por mongoose

    Comando --> node ./tests/axios/axios.deleteProducts.js
    
    

### Con Supertest - Chai - Mocha

    Comando---> npm run mocha-test


/- Errores:

    {1- Sigo teniendo problemas con los errores. Modifique todo e intente hacerlos andar pero no hay caso. El problema es con el errorHandler, en la carpeta middleweare. No me toma el error y pasa al default.
    
    2- No se me registran los error en la carpeta logs, los muestra por consola pero no los escribe.
    }


------------------------------------------------------------------------------------------------------------


/- Agregado:

{
    1- .env: se agrego NODE_ENV = "development"
    
    2- /config/options.js = se agrego al final nodeEnv
    
    3- /helpers/logger.js = se creo el archivo logger.js
    
    4- /routes/loger.router.js = se creo la ruta loggerRoute
    
    5- app.js = se agrego app.use(addLogger);
}















































matiSolis
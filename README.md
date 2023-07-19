/- Errores:

    {1- Sigo teniendo problemas con los errores. Modifique todo e intente hacerlos andar pero no hay caso. El problema es con el errorHandler, en la carpeta middleweare. No me toma el error y pasa al default.
    
    2- No se me registran los error en la carpeta logs, los muestra por consola pero no los escribe.
    }


------------------------------------------------------------------------------------------------------------


/- Agregado:

{
    .env: se agrego NODE_ENV = "development"
    /config/options.js = se agrego al final nodeEnv
    /helpers/logger.js = se creo el archivo logger.js
    /routes/loger.router.js = se creo la ruta loggerRoute
    app.js = se agrego app.use(addLogger);
}















































matiSolis
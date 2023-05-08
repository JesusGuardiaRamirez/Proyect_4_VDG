
![Ironhack logo](https://i.imgur.com/1QgrNNw.png)
# Proyecto - ETL . 


## La violencia de Genero en España, y otros paises. 





![Captura de pantalla 2023-05-05 a las 11 54 21](https://user-images.githubusercontent.com/125477881/236429147-df33e2d7-86eb-4888-ab9f-eb7b0495f936.png)




Este proyecto va enfocado a la violencia de genero, y abriendo paso a mi proyecto final con Ironhack.





### Los requisitos de este proyecto son:



        1. Extraer datos.
        2. Limpieza y análisis de los datos.
        3. Crear base de datos SQL.
        

* Obtener la información de 3 fuentes diferentes.



        1. URL
        2. PDF
        3. CSV



* Usar dos de los siguientes métodos para esa obteneción de datos:
 
 
 
        1. Archivos.
        2. DB.
        3. Apis.   
        4. Rss
        5. Scraping
     
  
    
    
*******************************



### Proyect Braking Down:





* He utilizado el scraping para coger la informacion de wikipedia con referencia a las comunidades autonomas y asi obtener los datos mas actuliazados de la poblacion.





  url = 'https://es.wikipedia.org/wiki/Anexo:Comunidades_y_ciudades_aut%C3%B3nomas_de_Espa%C3%B1a'
  
 
  

   ![Captura de pantalla 2023-05-08 a las 21 40 32](https://user-images.githubusercontent.com/125477881/236917925-b279d4b4-dbe6-4f86-a719-4940a8e26275.png)

 
 * Donde la informacion transformada se queda tal y aparece en la siguiente imagen:
  
  
   ![Captura de pantalla 2023-05-08 a las 22 55 27](https://user-images.githubusercontent.com/125477881/236933049-3f6bb134-e3e8-4ec3-bc52-6b4aafd56480.png)

  

* Del cual guardo los datos en un CSV para su uso.




***********************************************





* Tambien he utilizado la pagina web del gobierno de españa para sacar los datos reales de las victimas de vilencia de genero, el registro eseñaba desde el 
2013. 

url  =  'http://estadisticasviolenciagenero.igualdad.mpr.gob.es/'


![Captura de pantalla 2023-05-08 a las 21 50 36](https://user-images.githubusercontent.com/125477881/236919977-f6100342-17ab-41c3-92f9-10009042366c.png)


************************************************



Y por ultimo, un PDF de los datos reales de Francia del cual he tenido que pasar por la libreria pandas y poder pasar los datos y trabajar con ellos.


![Captura de pantalla 2023-05-08 a las 22 01 20](https://user-images.githubusercontent.com/125477881/236922063-aec442e7-b174-4fb4-876c-a8452c05ad93.png)





************************************************





Finalizando el proyecto, una vez obtengo todos los datos, ahora lo que toca es cargar los datos a SQL. (solo he enseñado algunos de los datos ya que este proyecto
sigue en las proximas semanas, de cara a la galeria del proyecto final de IRONHACK !



![Captura de pantalla 2023-05-08 a las 22 05 15](https://user-images.githubusercontent.com/125477881/236922835-fb82d29f-4c22-4f44-81b3-81892904d7fb.png)



*******************************************************



## Con esto dariamos por finalizado este prouyecto ya que se trataba solmanete de:





        1. OBTENER / SUSTRAER LOS DATOS DE 3 TIPOS DE FUENTES 
        2. UTILIZAR DOS METODOS, los cuales yo he utilizado el Scrapeo, Trasnferir los datos desde PDF y archivos CSVs. 



*******************************************************
![Ironhack logo](https://i.imgur.com/1QgrNNw.png)


# IRWA-2022-part-1

Para empezar ejecutar nuestro código se debe ejecutar la serie de imports que podemos
encontrar en el inicio de nuestro fichero python.
Seguidamente, tenemos que ejecutar la segunda casilla de código para importar el fichero
de nuestro interés. Podemos observar que al final de la casilla hemos incluido un print para
poder ver toda la información del primer tweet.
Después de esta casilla, podemos ver una tercera con un output. Este output nos imprime,
en nuestro caso, el username de un usuario, y lo hemos puesto para conocer cómo
podemos acceder a los campos del tweeter que nos interesan.
Después podemos encontrar las funciones que hemos creado para llevar a cabo la práctica.
La primera función, llamada build_terms(line), le pasamos por parámetro el texto de los
diferentes tweets, y nos devuelve el mismo texto sin mayúsculas, sin signos de puntuación,
sin stopwords, sin stemming y separando cada palabra con un espacio.
La segunda función, llamada create_index(lines), le pasamos todos los tweets con su
respectiva información, y nos devuelve un diccionario con sus respectivos keywords y
informacion (llamado index), y un diccionario que contiene todos los ids de los tweets
(llamado title_index).
Finalmente, ejecutamos la tercera función, llamada search(query, index), que le pasamos
por parámetro la palabra o el conjunto de palabras que queremos buscar dentro de los
tweets (representa la variable query en nuestro código) y por otro lado, le pasamos el índice
de los tweets (representa la variable index en el código). Esta función, nos devuelve una
lista con todos los documentos que tienen la query que le hemos pasado como input.
Después de definir la función create_index, la llamamos para crear el índice de los términos
de los tweets pasando los parámetros correspondientes (datos_diccionario es la variable
que le pasamos por parámetro de tipo diccionario). Destacar que en la última casilla, el
código nos pedirá que introduzcamos la palabra que deseamos (query) para poder ver la
cantidad de veces que aparece en nuestro fichero y cuáles son los resultados de la
búsqueda.

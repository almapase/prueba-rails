# Primera prueba rails
1. Crear un proyecto llamado Superheroes
2. Inicializar git y crear el primer commit
3. Crear y moverse a el branch development
4. Dentro del proyecto crear un controller llamados pages con la página batman
5. La página batman debe contener una foto de batman de fondo puesta con backstretch y con un texto encima que diga "I am Batman"
- Hacer el commit

6. Crear un página dentro del mismo controller llamada superman
7. La página superman debe contener una foto de superman de fondo puesta con backstretch y con un texto encima que diga "This looks like a job for Superman"
- Hacer el commit

8. Crear una página llamada batman-vs-superman
9. Dentro de la página deben aparecer dos fotos, una de batman y la otra de superman, cada una ocupa el 50% de la pantalla
10. Esta nueva página debe ser la página principal
11. Sobre cada foto debe ir un link a la página de cada superheroe
- Hacer el commit

12. Crear el modelo de votos, el voto debe guardar el superheroe escogido y el mail de quien lo escogió
- (hint) heroe:string email:string
- recordar que hay que migrar

13. Debajo de cada link crear un formulario de inscripción, los datos deben ser guardados en el modelo de votos guardando al héroe escogido
14. Realizar el commit
### EXTRA la 15
15. Contar y mostrar la cantidad de votos que hay en cada uno Esta pregunta es de bonus, dejarla para el final
- tip1: ocupando group_by (o sea se traen los datos de SQL y se agrupan en ruby)
- tip2: ocupando group (se agrupan los datos de SQL y luego se traen)

16. Crear un nuevo controller llamado experiments con las páginas page1, page2, page3
- Hacer el commit

17. Copiar textos lorem ipsum en las 3 páginas
18. Cargar un layouts llamado bootstrap
19. Crear el layout con bootstrap ocupando el CDN de boostrap
- Hacer un commit

20. Crear un menú de bootstrap en una vista parcial
21. Cargar este menú de vista parcial en el layout
- Hacer un commit

22. Agregar como clase el nombre del controller y el nombre de la página en el layout nuevo (ocupando los params)
- ej: en page3 debería decir:

23. Crear un CSS que ponga el color de fondo negro de la página page3
- Hacer el commit

24. Crear con javascript una cuenta regresiva (solo en segundos) para page1
- Tip: setInterval()

25. El número de segundos en que inicia debe fijarse en el controller, partir por defecto en 300 segundos
26. En el navbar poner los links a page1, page2 y page3
27. page3 debe ser cargado sin turbolinks
- Hacer el commit

28. Hacer el merge con master
29. Subir a heroku (recordar la migración )
- Este punto sólo sera otorgado si dentro del archivo README.md se incluye la dirección de heroku donde se puede ver la página

30. Subir a github

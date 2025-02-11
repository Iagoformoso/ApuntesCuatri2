
### Secuencias
>[!Crear una secuencia] 
>   **Create sequence** seq_libro_id_libro;
>   
>   

Los **disparadores** tienen un comportamiento de modo que cuando ocurre una instrucción específica, como si de una señal se tratara, se "dispare" una funcionalidad antes que la instrucción ocurrida.
	Por ejemplo, si introducimos en la tabla Empresa una empresa, puede haber un disparador que antes de introducirla compruebe si ya existe (Caso hipotético).

>[!Crea un disparador para ejecutar la funcion antes de un insert]
>**create trigger** beforeInsertEjemplares **before insert on** ejemplar
>for each row execute procedure introduce_num_ejemplar(); 

### Parte de Java

En cada parte definiremos una **fachada** que sirve para definir los métodos públicos

>[!DAO]
>Data access object


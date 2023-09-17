# ColombiaHydroponic
## Version beta
### Estudio de .Net Blazor Framewroks etc

__TODO ESTO LO APRENDI EN EL CURSO DE Codigo Estudiante:__ https://www.youtube.com/@codigoestudiante
- Mi primer proyecto .Net con APIS y Frameworks
- HTML
- Blazor
- C#<br>

### Contenido de ColombiaHydroponic

![Logotipo viejo](https://res.cloudinary.com/dlwr6vxib/image/upload/v1694984160/o05ptvbifgacmjdwz2ha.png)<br>

### Problemas que ocurrieron

Principalmente por lo que hice este curso fue para entender la asincronía o SYNC para los que hablan ingles:

1. Tener muy encuenta como llamar las variables, ocurrieron muchos problemas relacionados con esto devido a que llamba una variable como una que ya existia probocando errores que solo se ven al inciar el proyecto, dandome horas de busqueda por solo una minuscula.
2. Nega la posibilidad de nulos, este fue uno de mis mayores enemigos al momento, me demoro 3 dias buscar ese problema, y era en el DTO de un servicio el cual no podia resivir nulos y como no me entere que no lo habia colocado, salia error al momento de ejecutar el servicio.
3. Mi mayor error fue hacer todo acarreriado, lo cual me proboco un problema en el Nuget de Toast al momento de colocarl la etiqueta en HTML, en la etiqueta para llamar al servicio era "\<BlazoredToasts/>" no "\<BlazoredToast/>" lo cual probocaba que no funcionara tambien pase 2 dias buscando ese problema :c.

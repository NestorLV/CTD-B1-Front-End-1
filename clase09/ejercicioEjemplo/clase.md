# Variables en CSS o Propiedades Personalizadas
## Declaración
   Las variables deben declararse dentro de un selector
   Se acostumbra usar :root para que la variable sea global 
   Se declaran con dos guiones y el nombre

## Aplicación
   Para utilizarlas se usa la funcion var() y entre
   los paréntesis se escribe el nombre de la variable
   
## Comportamiento
El valor es heredado a los hijos
El valor puede redefinirse por cascada

# La regla @import
La regla @import permite cargar uno o varios archivos CSS dentro de otro. Estamos llamando archivos css desde otro css para utilizar sus estilos. La ventaja es que puedes dividir el CSS en diferentes partes siguiendo la lógica que prefieras para tener el trabajo más organizado, más fácil de manejar y más fácil de aislar errores.

## Implementación
@import + la ruta del archivo que queremos llamar entre comillas:
Ejemplo:
@import "header.css"


 
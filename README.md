# Actividad Formativa N° 2: Diseñando un e-Commerce con Inteligencia Artificial.

## Nombre 
  The Pole Arts

## Descripción
  Un e-commerce dedicado al alquiler y venta de equipamiento de Pole Dance y Danza mezclado con el universo de Harry Potter.

## Diseño del registro principal
  Para la gestión de inventario y servicios, se definió la siguiente estructura de datos:

```pascal
Pole_Art = Registro
  id_producto: N(2)          {Clave Primaria}
  Producto: AN(30)           {Nombre del producto}
  Tipo: ("Alquiler", "Venta") 
  Descripcion: AN(150)       {Descripción del producto}
  Precio: Real              
  Stock: N(3)                
  Disponible: Booleano       {Estado de disponibilidad}
Fin_Registro
```
## Identificación y explicación de la clave
Campo clave: id_producto

Se seleccionó este campo como clave primaria simple debido a la propiedad de unicidad. Es fundamental contar con un selector de campo que sea único e irrepetible. Dos productos pueden tener el mismo precio o nombre, pero el ID garantiza que la base de datos identifique cada ítem, evitando errores.

## Proceso de Interacción con la IA
Utilicé Google Gemini. [Link del chat completo](https://gemini.google.com/share/9594899ae1dc)

## Video Demo
[Link al drive](https://drive.google.com/file/d/1d1_nBfUOF8JAdtH9ww0NOBBt6wVoqciz/view?usp=sharing)

## App Publicada
[Link de la página](https://china4k.github.io/e-Commerce-con-Inteligencia-Artificial/)

## Reflexión sobre el uso de IA en el diseño
La utilización de la IA no solo me ayudó con los nombres, descripción y precio de los productos adaptandolos al universo que tenía pensado, sino que también me sorprendrió lo fácil que fue hacer la página porque pensé que no iba a entender tan bien o iba a quedar algo demasiado simple, obviamente hay muchos detalles visuales y funcionales para mejorar pero el resultado me gustó mucho. El tiempo para hacer el trabajo se redujo demasiado con la IA, por no decir que fue solamente describirle lo que quería, copiar y pegar, es una herramienta muy útil.

# Clase-23Julio
//Ejercicios de operadores lógicos
//Operadores lógicos: AND (&&), OR (||)

let edad = 20;
let tieneDui = false;

let puedeVotar = edad >= 18 && tieneDui ? "puede votar" : "no puede votar";
console.log(puedeVotar);

let edad2 = 45; 
let tieneMembresia = true;

let tieneDescuento = edad2 >= 30 || tieneMembresia ? "tiene descuento" : "no tiene descuento";
console.log(tieneDescuento);

let edad3 = 12;
let estatura = 1.65; 

let puedeSubirMontañaRusa = edad3 >= 12 && estatura >= 1.60 ? "puede subir a la montaña rusa" : "no puede subir a la montaña rusa";
console.log(puedeSubirMontañaRusa);

//Guia de ejercicios

//1. Una persona puede entrar al cine si tiene una entrada válida y es mayor de 13 años, Crea las variables Entrada y edad, utiliza el operador lógico que creas que se aplica e imprime el mensaje de si puede entrar o no puede entrar.

let edad4 = 13;
let entrada = false;

let puedeEntrar = edad4 >= 13 && entrada ? "Puede entrar al cine" : "No puede entrar al cine";
console.log(puedeEntrar);

//2. Un cliente recibe un descuento especial si es mayor de 60 años o si es persona con discapacidad, usa las variables edad y discapacitado, emplea el operador que crees que se aplica, imprime el resultado.

let edad5 = 80;
let discapacidad = false;

let descuentoEspecial = edad5 >= 60 || discapacidad ? "Tiene descuento especial" : "No tiene descuento especial"; 
console.log (descuentoEspecial);

//3. Un estudiante aprueba si su nota es mayor o igual a 7 o si pasó la recuperación, crea las variables nota y recuperación. Utiliza el operador lógico que creas conveniente e imprime el mensaje.

let nota = 5; 
let pasoRepo = false;

let aprueba = nota >= 7 || pasoRepo ? "Aprueba el curso" : "No aprueba el curso";
console.log(aprueba);

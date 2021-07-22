# Prueba-t-cnica-para-developer-SUPER
function costo_anillos(){

let nro_anillos_abierto = prompt("ingrese anillos abiertos");
let nro_anillos_cerrados = prompt("ingrese anillos cerrados");

let costo_abrir = 20;
let costo_cerrar = 35;

let abrir = nro_anillos_abierto*costo_abrir;
let cerrar = nro_anillos_cerrados * costo_cerrar;
alert(abrir+cerrar);

}

costo_anillos();

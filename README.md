# React-para-Humanos-Aprende-a-Crear-Apps-sin-ser-Programador
En este repositorio se van a mostrar los ejemplos y codigos aplicados en la creacion del libro React para Humanos: Aprende a Crear Apps sin ser Programador.
Ejemplos sencillos: desde el botón hasta el contador.

Botón básico en React
El primer paso es crear un botón simple que muestre texto en la pantalla.
Usando como base el siguiente ejemplo:

function SimpleButton()
{
	return <button>Click Me</button>;
}

Lo modificamos y tenemos: 

function SimpleButton()
{
	return (
 		<div>
   			<h1>Miprimer boton en React</h1>
	  		<button>Haz clic aqui</button>
	 	</div>
   );
}

Visualizando lo siguiente:
	Este componente muestra un botón con el texto “Haz clic aquí”.

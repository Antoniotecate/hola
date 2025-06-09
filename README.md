hoka
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pagina principal practica 3</title>
  <style>
    .container {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .box {
      width: 500px;
      height: 200px;
      background-color: red;
      text-align: center;
      line-height: 200px;
      color: white;
      font-weight: bold;
    }
    .photo {
      width: 400px;
      height: 200px;
    }

.cuadro {
  width: 200px; /* Ancho del cuadro */
  height: 150px; /* Altura del cuadro */
  padding: 10px; /* Espacio interno para el texto */
  border: 1px solid #ccc; /* Borde del cuadro */
  margin: 10px; /* Espacio entre cuadros */
  display: inline-block; /* Permite que los cuadros se dispongan en fila */
  text-align: center; /* Centra el texto horizontalmente */
  vertical-align: top; /* Alinea los elementos verticalmente */
  justify-content: space-between;
   align-items: center;
}

/* Estilos para cada cuadro */
.cuadro-rojo {
  background-color: #ff0000; /* Rojo */
  color: white; /* Texto blanco */
   justify-content: space-between;
      align-items: center;
}

.cuadro-verde {
  background-color: #00ff00; /* Verde */
  color: black; /* Texto negro */
   
}

.cuadro-azul {
  background-color: #0000ff; /* Azul */
  color: white; /* Texto blanco */
   
}

.cuadro-amarillo {
  background-color: #ffff00; /* Amarillo */
  color: black; /* Texto negro */
  
}


.cuadro-salmon {
  background-color:#FA8072; /* Olivo */
  color: white; /* Texto blanco */
  float: right;
}

.cuadro-olivo {
  background-color:#808000; /* Olivo */
  color: black; /* Texto negro */
  float: right;
}
.cuadro a {
  color: inherit; /* El color del texto será el color de fondo del cuadro */
  text-decoration: none; /* Eliminar el subrayado del enlace */
}

.cuadro a:hover {
  text-decoration: underline; /* Subrayar al pasar el ratón */
}
        .centrado {
            text-align: center;
            font-weight: bold;
            font-size: 40px; /* Puedes ajustar el tamaño según tus necesidades */
        }
    </style>
</head>
<body>
  <div class="container">
    <div class="box">Juegos de mesa</div>
    <img class="photo" src="C:\Users\antonio\OneDrive\Pictures\Documents\Pactica tix\Imagenes\juegos de mesa.jpg" alt="Foto de ejemplo">
  </div>


	</head>
<BODY BGCOLOR="SILVER" TEXT="BLACK">

          <H1 class="centrado")>INTRODUCCION </H1> <BR>QUE SON? <BR>

<TT> Un juego de mesa es una actividad de entretenimiento que se juega sobre una superficie plana, generalmente una mesa, utilizando piezas, fichas, cartas o tableros, y siguiendo reglas específicas. Estos juegos pueden ser de estrategia, azar, habilidad o cooperación, y han sido una forma popular de socialización a lo largo de la historia </TT>

body>
    <div class="search-container">
        <h1>Buscar juegos</h1>
        <input type="text" id="searchQuery" placeholder="Escribe tu búsqueda...">
        <button onclick="search()">Buscar</button>
    </div>

    <script>
        function search() {
            const query = document.getElementById('searchQuery').value;
            if (query) {
                const url = `https://www.google.com/search?q=${encodeURIComponent(query)}`;
                window.open(url, '_blank');
            } else {
                alert('Por favor, escribe algo para buscar.');
            }
        }
    </script>
</body>

  <style>
    .container {
      display: flex;
      justify-content: space-between; /* Espaciado uniforme entre cuadros */
      align-items: center; /* Alineación vertical */
      margin: 20px;
    }
    .box {
      width: 500px;
      height: 200px;
      background-color: #4CAF50; /* Color verde */
      margin: 10px;
      text-align: center;
      line-height: 100px; /* Centrar texto verticalmente */
      color: white;
      font-weight: bold;
      border-radius: 8px; /* Bordes redondeados */
      font-size: 35px;
    }
        .encabezado-rojo {
            color: red;
        }
  </style>
</head>

<body>


</head>
<body>
  </div>
  <div class="container">
  <div class="cuadro cuadro-rojo">
    <h2>Monopoly</h2>
    <a href="file:///C:/Users/antonio/OneDrive/Pictures/Documents/Pactica%20tix/Practica%203%20%20juego%201.HTML">Enlace</a>
  </div>

  <div class="cuadro cuadro-verde">
    <h2>Calabozos y Dragones</h2>
    <a href="file:///C:/Users/antonio/OneDrive/Pictures/Documents/Pactica%20tix/Practica%203%20%20juego%202.HTML">Enlace </a>
  </div>

  <div class="cuadro cuadro-azul">
    <h2>Serpientes y escaleras</h2>
    <a href="file:///C:/Users/antonio/OneDrive/Pictures/Documents/Pactica%20tix/Practica%203%20%20juego%203.HTML">Enlace</a>
  </div>

  <div class="cuadro cuadro-amarillo">
    <h2>Ajedrez</h2>
    <a href="file:///C:/Users/antonio/OneDrive/Pictures/Documents/Pactica%20tix/Practica%203%20%20juego%204.HTML">Enlace </a>
  </div>

  </div>

    <div class="anuncio">
        <img src="C:\Users\antonio\OneDrive\Pictures\Documents\Pactica tix\Imagenes\Uno no mercy.jpg" alt="Producto">
        <h1>¡Oferta Especial!</h1>
        <p>Compra ahora y obtén un 20% de descuento en todos nuestros productos. ¡No te lo pierdas!</p>
        <a href="#">Comprar Ahora</a>


  <div class="cuadro cuadro-salmon">
    <h2>Juejos modernos</h2>
    <a href="https://ludomaniacos.com/los-10-juegos-de-mesa-modernos-mas-populares/">Enlace</a>
  </div>

  <div class="cuadro cuadro-olivo">
    <h2>Juegos clasicos</h2>
    <a href="https://padresfrikis.com/juegos-de-mesa-clasicos/">Enlace </a>
  </div>

<h1 class="encabezado-rojo">Elaboro: Antonio Camacho Gonzalez</h1>
 
  </div>

</body>
</html>

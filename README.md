

<!DOCTYPE html>
<html>
<head>
     <meta charset="UTF-8" />
     <title>title</title>
</head>
<body>
 <h1  id="titulo">
  titulo
  </h1>
  <im src="https://upload.wikipedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/768px-Google_%22G%22_logo.svg.png">
  </body>
    

  <script>

function agregarElemento(texto,color,fondo){
 let crearElemento = document.createElement("h1")  
 crearElemento.innerHTML = texto
 crearElemento.style.color = color
 crearElemento.style.backgroundColor = fondo
 document.body.appendChild(crearElemento)
}

function convertir_CMYK_a_RGB(c,m,y,k){
let r,g,b
r=255*(1-c)*(1-k)
}

function holasoyAmelie() {
  agregarElemento("Hola soy Amelie","red","black")
}


agregarElemento("argumentos","blue","lightblue")
agregarElemento("segundo elemento","red","pink")
agregarElemento("argumentos")





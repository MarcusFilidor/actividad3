actividad3
<html lang="es">
<head>
    
<title>Cuatro Cajas dentro de un Contenedor</title>
<style>
       
{
box-sizing: border-box;
margin: 0;
padding: 0;
}

.contenedor {
width: 80%;                      
padding: 20px;                   
border: 2px solid gray;          
box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); 
margin: 0 auto;                  
display: grid;                   
grid-template-columns: repeat(2, 1fr); 
gap: 10px;                       
}

        
.caja {
width: 100%;                    
height: 150px;                   
padding: 10px;                   
margin: 10px 0;                  
border: 1px solid #ccc;          
text-align: center;              
line-height: 150px;              
font-weight: bold;               
color: white;                    
}

        
.caja1 {
background-color: #f44336;       
}

.caja2 {
background-color: #4caf50;       
}

.caja3 {
background-color: #2196f3;      
}

.caja4 {
background-color: #ffeb3b;       
}

</style>
</head>
<body>

<div class="contenedor">
<div class="caja caja1">CAJA 1</div>
<div class="caja caja2">CAJA 2</div>
<div class="caja caja3">CAJA 3</div>
<div class="caja caja4">CAJA 4</div>

</div>

</body>
</html>

<html>
	<head>
		<title>inputs</title>
	</head>
	<body>
		<h1>Formularios y sus tipos de inputs</h1>

		<!-- Si no se especifica el metodo por el cual se ejecutará la petitión,
			por default lo hace por el método GET -->

		<form action="" method="GET">
			<label>Buscador</label>
			<input type="search" id=buscador name="buscador"/>
			<br><br>
			
			<label>Fecha Local</label>
			<input type="number" id="numero" name="numero" min="1" max="5"/>
			<br><br>

			<label> Fecha local</label>
			<input type="datetime-local" id="FechaLocal" name="fechaLocal"/>
			<br><br>
			
			<label> Mes</label>
			<input type="month" id="mes" name="mes"/>
			<br><br>

			<label> Hora:</label>
			<input type="time" id="hora" name="hora"/>
			<br><br>

			<label> Semana:</label>
			<input type="week" id="semana" name="semana"/>
			<br><br>

			<label> Color</label>
			<input type="color" id="color" name="color value="#FFFFFF"/>
			<br><br>

			<label> Fecha</label>
			<input type="date" id="fecha" name="fecha" min="2021-06-14" max="2021-06-16"/>
			<br><br>
			
			<input type="radio" id="masculino" name="sexo" value="1"/>
			<label for="masculino">Masculino</label>
			<br>
			<input type="radio" id="femenino" name="sexo" value="2"/>
			<label for="femenino">Femenino</label>
			<br>
			<input type="radio" id="otro" name="sexo" value="3"/>
			<label for="otro">Otro</label>
			<br><br>

			<h5>Alergias</h5>
			<input type="checkbox" id="polen" name="alergia" value="polen"/>
			<label for="polen">Polen</label>
			<br>
			<input type="checkbox" id="chocolate" name="alergia" value="chocolote"/>
			<label for="chocolate">Chocolate</label>
			<br>
			<input type="checkbox" id="penicilina" name="alergia" value="penicilina"/>
			<label for="penicilina">Penicilina</label>
			<br><br>
			
			<label>Archivo</label>
			<input type="file" id="archivo" name="archivo"/>
			<br><br>
			
			<label>Archivos</label>
			<input type="file" id="archivo2" name="archivo2" multiple/>
			<br><br>

			<label>Telefono:</label>
    			<input type="tel" id="telefono" name="telefono"
			pattern="[0-9]{3}-[0-9]{3}-[0-9]{2}-[0-9]{2}" 
			placeholder="Ej. 777-455-35-42"/>
    			<br><br>  

    			<label>Matrícula:</label>
			<input type="text" id="matricula" name="matricula"  minlength="10" maxlength="11"/>
    			<br><br> 

    			<label>Municipio:</label>
    			<input list="municipios" name="municipio"/>
    		<datalist id="municipios">
			<option value="Cuernavaca">
			<option value="Emiliano Zapata">
			<option value="Temixco">
			<option value="Jiutepec">
			<option value="Zacatepec">
			<option value="Cuautla">
     		</datalist>
     		<br><br> 
    			<label>Estado:</label>
      				<select id="estado" name="estado">
					<option value="0" >seleccione...</option>
					<option value="1" >Morelos...</option>
					<option value="3" >Guerrero..</option>
					<option value="0" >Oaxaca...</option>
					<option value="0" >Jalisco...</option>
					<option value="0" >Puebla...</option>
					<option value="0" >Edo Méx...</option>
      				</select>
    				<br><br> 
			
			<input type="submit" value="Aceptar"/>
			<input type="reset" value="Limpiar"/>

		</form>
		
		<!--
		<form action="" method="">
			<label> Usuario</label>
			<input type="text" id="usuario" name="usuario" placeholder="Usuario"/>
			<br>
			<label> Usuario</label>
			<input type="password" id="contrasena" name="contrasena"/>
			<br>
		-->	
		</form>	
	</body>
</html>

# formularios-html
Aula dia 29/08/23 sobre formularios basicos em html.
<!DOCTYPE html>
<html lang="pt-br">
<head>
              <meta charset="UTF-8" />
			  <title> Formúlario </title>

</head>

   <body style="background-color: gray;">
     <form>
	 <label style="background-color: PapayaWhip;"> Nome: </label>
	 <input type="text" name ="txtnome" required placeholder="Digite o seu nome" />
	     <br> <br>
	 
	 <label style="background-color: PapayaWhip;"> Idade: </label>
	 <input type="number" min="10" max="60" required placeholder="valores maiores que 10"/> 
	     <br> </br>
	 <label style="background-color: PapayaWhip;"> Data de Nascimento </label> 
	 <input required type="date" />
	     <br> </br>
	 <label style="background-color: PapayaWhip;"> Data Atual </label>
	 <input type="datetime-local"/>
	     <br> </br>
	 <label style="background-color: PapayaWhip;"> Mes </label>
	 <input type="month" placeholder="MÊS" />
	 <br> </br>
	 <label style="background-color: PapayaWhip;"> Qual linguagem de programação voce conhece? </label> <br> </br>
	 <input type="checkbox" name="asp" value="asp"/> ASP Net <br>
	 <input type="checkbox" name="php" value="php"/> PHP <br>
	 <input type="checkbox" name="Java" checked value="Java"/> Java <br>
	      <br> <br>
	 <label> Estado Civil </label> <br> <br>
	 <input type="radio" name="estadocivil" value="casado"> Casado <br>
	 <input type="radio" name="estadocivil" checked value="solteiro"> Solteiro <br>
	    <br> <br>
	 <label> Estado </label>
	 <select required name="estado">
	 <option value="SP"> São Paulo </option>
	 <option value="SC"> Santa Catarina </option>
	 <option value="RJ"> Rio de Janeiro </option>
	 <option value="MG"> Minas Gerais </option>
	 <option value="MS"> Mato Grosso do Sul </option>
	 </select>
	 
	 
	 <br> <br>
	 <input style="background-color: Purple;" type="submit" value="Enviar" />
	 
	 
	 
	 </form>
	 
	  
	 
   </body>
   
</html>

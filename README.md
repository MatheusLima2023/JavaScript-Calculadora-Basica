# JavaScript-Calculadora-Basica
Codigo facil e simple, formato Html com JavaScript
<!DOCTYPE html>
<html lang="pt-BR">
	<head>
		<meta charset="utf-8">
		<title> Praticando Javascript Exercicio 1</title>
	</head>
	<body>
  </body>
	<script type="text/javascript">
		var numero1 = prompt("Insira o primeiro número: ");
		var numero2 = prompt("Insira o segundo número: ");
		var operacao = prompt ("Qual operação deseja realizar? (Digite + ou - ou * ou /)");
		
		var resultadoOperacao = realizaOperacao(numero1, numero2, operacao);
		
		
		alert('O resultado da operação é igual a: ' + resultadoOperacao);
		
		function realizaOperacao (numero1, numero2, op) {
			var resultado = 0;
			//resultado = numero1 + eval(op) + numero2;
			resultado = eval (numero1 + op + numero2);
			return resultado;
		}
		
		
	</script>
</html>

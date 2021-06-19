# repositoria5HSMu
var valorCompra =prompt("Entre com o valor da sua compra nas lojas 'LuDas' para receber seu desconto!");
descontoLuDas(valorCompra);

function descontoLuDas(valorCompra){
	if(valorCompra <= 499.99){
		var percentual = 10;
		var desconto = (valorCompra*10)/100;
		var pagarComDesconto = (valorCompra - desconto).toFixed(2);
	}else{
		var percentual = 15;
		var desconto = (valorCompra*15)/100;
		var pagarComDesconto = (valorCompra - desconto).toFixed(2);
	}
return document.write("O percentual de desconto é: "+percentual+"%.<br> O valor do desconto é: R$ "+desconto+".00.<br> O valor final a ser pago é: R$ "+pagarComDesconto+".");
}

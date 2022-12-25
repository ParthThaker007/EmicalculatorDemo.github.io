function solution()
{
	var p = parseFloat(document.getElementById("amount").value);
	var r = parseFloat(document.getElementById("rate").value);
	var n = parseFloat(document.getElementById("time").value);
	
	var a = r/100;
	var m =((1 + a)**n);
	var o = (((1 + a)**n)- 1);
	emi = p*a*(m/o);
    ans=  emi.toFixed(1);
	tot  =  (ans*n);
	man = tot.toFixed(3);
	document.getElementById("final").innerHTML="Your per Month EMI =  "+ans;
	document.getElementById("total").innerHTML="Your TOTAL AMOUNT THAT YOU PAY =  "+man;
	
} 
var num1,num2;
var mywindow;


function add(){
num1=parseInt(document.arithmaticfrm.num1.value);
num2=parseInt(document.arithmaticfrm.num2.value);
 var num3=num1+num2;
  mywindow=open('','mywin','height=300,width=300,scrollbars=yes');
mywindow.document.writeln("<html><body>");
mywindow.document.writeln("<script>num3</script>");
mywindow.document.writeln("</html></body>");

document.arithmaticfrm.num3.value=num3 ;



}

function sub(){
num1=parseInt(document.arithmaticfrm.num1.value);
num2=parseInt(document.arithmaticfrm.num2.value);
var num3=num1-num2;
mywindow=open('','mywin','height=300,width=300,scrollbars=yes');
mywindow.document.writeln("<html><body>");
var data =
mywindow.document.writeln("Ans i = "+num3 + ";");
mywindow.document.writeln("</html></body>");



document.arithmaticfrm.num3.value=num3;
}

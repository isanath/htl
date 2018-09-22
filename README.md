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

















<?xml version="1.0" encoding="UTF-8"?>
<schema xmlns="http://www.w3.org/2001/XMLSchema" targetNamespace="http://www.example.org/associatedata" xmlns:tns="http://www.example.org/associatedata"  elementFormDefault="qualified">
<element name="AssociateData"   >
<complexType>
<sequence>
<element name="Associate"   minOccurs=" 1"    maxOccurs=" unbounded"  >
<complexType>
<sequence>
<element name="yearlyInvestmentUnder80c"    type="  integer"></element>
<element name=" firstName"    type="  string"></element>
<element name=" lastName"    type="  string"></element>
<element name="department"    >
<simpleType>
<restriction base="string">
<enumeration value="Sr.con"></enumeration>
<enumeration value="con"></enumeration>

</restriction>

</simpleType>

</element>
<element name=" designation"    type="  string"></element>
<element name="emailId"    type="  string"></element>
<element name="BankDetails">
<complexType>
<sequence>
<element name="accountNumber"   type="integer"></element>
<element name="bankName"   type="string"></element>
<element name="IFSCcode"   type="string"></element>
</sequence>
</complexType>
</element>
</sequence>
<attribute  name="Associateid"  type="integer"  use="required"></attribute>
</complexType>
</element>
</sequence>
</complexType>
</element>
</schema>



var mywindow;
function showalertbox()
{
alert("alert message");
}

function showconifrmationbox()
{
var status=window.confirm();
}

function showinputbox()
{
var name=window.prompt("Enter name ");
window.alert("Entered name "+name);
}

function openit()
{
mywindow=open('','mywin','height=300,width=300,scrollbars=yes');
mywindow.document.writeln("<html><head><title>fun</title></head><body>");
mywindow.document.writeln("<h1>New Window</h1>");
mywindow.document.close();
mywindow.focus();
mywindow.alert("Hey guys");
}


















# REPOAPEXEXERCISE12.12.2022

String name1='kerime ';
name1+='alici ';
name1+='beyaz';
System.debug('benim adim : ' +name1);
Integer age= 26;
System.debug(age);
Decimal height=1.50;
System.debug(height);
String sentence='i love my husband, i love my cat';
System.debug(sentence);
System.debug(sentence.toUpperCase());
System.debug(sentence.isAllUpperCase());
System.debug(sentence.toLowerCase());
System.debug(sentence.isAllLowerCase());
System.debug(sentence.capitalize());
System.debug(sentence.replace('love','like'));
System.debug(sentence.reverse());
System.debug(sentence.center(2));
System.debug(sentence.contains('husband'));
System.debug(sentence.hashCode());
System.debug(sentence.isAlpha());
System.debug(sentence.length());
System.debug(sentence.split('love'));
Boolean mycountrynetherland= false;
Boolean mycityamsterdam= false;
if(mycountrynetherland&&mycityamsterdam) 
{System.debug('my city is amsterdam ');} 
else if ( mycountrynetherland||mycityamsterdam) 
{System.debug('my country is netherland');}
else{System.debug('i live in turkey');}
Integer leadnum=78;
Integer accountnum=89;
Integer opportunity=100000;
if(opportunity<90000){
    System.debug('please visit our campaign page');
} 
else if (accountnum>90) {System.debug('please enter your related contact name');}
else{System.debug('please contact with salesforce');}
List <String> accname= new List <String>();

<div align="center">

## friendly interface \(color change dinamically  where the cursor is\)


</div>

### Description

help user type on screen. it is good specially if you have many controls (textboxes etc) on a page.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marcio Coelho](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marcio-coelho.md)
**Level**          |Intermediate
**User Rating**    |4.2 (25 globes from 6 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marcio-coelho-friendly-interface-color-change-dinamically-where-the-cursor-is__2-2853/archive/master.zip)





### Source Code

```
user friendly interface plus very simple code in javascript.
It uses eval to dinamically understand the id of the control being passed and Change color of the control where the cursor is.
<HTML>
<body>
 <BR>
 <INPUT type="text" id=text1 name=text1 onfocus="focusobj(this.id)" onblur="blurobj(this.id)"><BR>
 <INPUT type="text" id=text2 name=text2 onfocus="focusobj(this.id)" onblur="blurobj(this.id)"><BR>
 <INPUT type="text" id=text3 name=text3 onfocus="focusobj(this.id)" onblur="blurobj(this.id)"><BR>
 <SELECT id=select1 name=select1 onfocus="focusobj(this.id)" onblur="blurobj(this.id)">
	<OPTION>aaaa</OPTION>
	<OPTION>bbbb</OPTION>
	</SELECT>
 </BODY>
 </HTML>
 <SCRIPT LANGUAGE=javascript>
<!--
function focusobj(value){
eval(value+'.style.backgroundColor = "bisque"')
	}
function blurobj(value){
eval(value+'.style.backgroundColor = "white"')
		}
/*
 If by any means you have a form and your form name is myform. then the code would be something
like this:
eval('document.myform.'+value+'.style.backgroundColor = "bisque"')
*/
//-->
</SCRIPT>
```


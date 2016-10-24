	//The container div provides padding around itself. 
	//container fluid isnt going to put any padding around itself.
	//Bootstrap grids require a container inside of them 
	//Page header provides any space around the text as well as enlarge any of the text insdie of them. it will also providde an /underline after the text is displayed
	//jumbotron will enlarge your fonts and put everything inside a gray box with rounded corners. you can change colors from this gray box. if you use jumbotron outside of a container it is going to copmletley make the whole screen gray. you can change the background color of jumbotoron and style it. 
	//there are differnet types of button from xs (Extra small) to small to large 
	//A disabled link doesnt allow you to click on it or when you move your mouse over the link it shows a cross sign
	//The div btn-group btn-group-lg with the role as group, provides you with as many buttons as possible lined up side by side. One button of the buttons provied may be clicked, two buttons may not be clicked at once. 

	Bootstrap uses what is caleld a 12 column system. Meaning if we want all of our elements to section off evenly we need to section themo ff into versions of 12

	"col-lg-3 col-md-3 col-sm-6 col-xs-12"

	There are 3 large columns for wide screens 1200 px or more
	 3 medium columns for medium screens 992 px
	  6 small columns for small screens, 6 of the 12 columsn are going to be used
	   and 6 extra small screens  

	In Columns.html you can see that if the texts are not the same and we try and each column have a different size when the browser is resized there is an issue with formating. In order to fix this issue, put a div with a class named clearfix and write where the issue is occuring either when youre large, medium, small, extra small 	   

	<div class="clearfix visible-sm">


	Collapsed columns will allow you to click on a word and a list of material will flow down. By using the collapse in class for the div for the col1Content div the information will be shown by default. In collapse the information is not shown until clicked 

	The well hidden divs will dissapear if the width of the div goes below a certain value. 

	<div class="col-md-6 col-md-offset-6">
	will leave an offset or leave black 6 columns on the left value of the screen 

	table stribe allows you to put in the row lines. table hover will allow you to change color.

	If you are using bootstrap and you use the data target field you can tell bootstrap that you want to use their javascript libraries without actually having to write any of the code. Just by providing a data target you are allowing bootstrap to take over the control of your html page and use its jquery. 
The Carousel:
	If you want ot create a carousel you can use the id thecarousel 

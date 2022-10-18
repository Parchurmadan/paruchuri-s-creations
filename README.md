<!DOCTYPE html>
<html>
    <head>
      <title>hai learner</title>
      <link rel="stylesheet" href="D:\html,css,js\css.css"> 
<!-- CSS only -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">
<script src="D:\html,css,js\learning.js"></script> 
<!---JAVASCRIPT-->
 
 <script>
    function madan(){
        document.getElementById("display").innerHTML="you are having very good techinquies to display"
        document.getElementById("display").style.display="hide";
        document.getElementById("display").style.display="block";
    }
  </script>
</head>
    <body alink="green" link="blue" vlink="red" >
       
       <!---- <div>
        Table of contents i
        1 HTML 1
        1.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1<br>
        1.2 First code . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1<br>
        1.3 Basic tags . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2<br>
        1.4 Attributes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4<br>
        1.4.1 Attribute ‘name’ and ‘value’ . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4<br>
        1.4.2 Core attributes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4<br>
        1.5 Tables . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5<br>
        1.6 Text formatting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6<br>
        1.7 Images . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6<br>
        1.8 Lists . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8<br>
        1.9 Links . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8<br>
        1.10 Forms . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10<br>
        2 Cascading Style Sheets (CSS) 15<br>
        2.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15<br>
        2.1.1 Inline CSS . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15<br>
        2.1.2 Embedded CSS . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15<br>
        2.1.3 External CSS . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16<br>
        2.2 Basic CSS Selectors . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17<br>
        2.3 Hierarchy . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18<br>
        2.4 More selectors . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20<br>
        2.4.1 Attribute selector . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20<br>
        2.5 More properties . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21<br>
        3 Bootstrap 22<br>
        3.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22<br>
        3.2 Setup . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22<br>
        3.2.1 Download and include files . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22<br>
        3.2.2 Add CDN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23<br>
        3.2.3 Check setup . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23<br>
        3.3 Grid system . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 24<br>
        3.3.1 Example . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 25<br>
        3.3.2 Nested columns . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26<br>
        3.3.3 Offset . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26<br>
        3.4 Components . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 27<br>
        3.4.1 Labels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28<br>
        3.4.2 Buttons . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29<br>
        3.4.3 Forms . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29<br>
        3.4.4 Horizontal form . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30<br>
        3.4.5 Form eleme<br>
        3.4.6 Control size . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35<br>
        3.4.7 More buttons . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37<br>
        3.4.8 Input group . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39<br>
        3.4.9 Navigation bar (navbar) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42<br>
        4 JavaScript 45<br>
        4.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45<br>
        4.2 First code . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45<br>
        4.2.1 JavaScript in HTML file . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45<br>
        4.3 Keywords, Datatypes, Variables and Operators . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46<br>
        4.3.1 Keywords . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46<br>
        4.3.2 Datatypes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47<br>
        4.3.3 Variables . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 47<br>
        4.3.4 Operators . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48<br>
        4.3.5 String to number conversion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 49<br>
        4.3.6 Convert to integer . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 49<br>
        4.3.7 Convert to float . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50<br>
        4.3.8 Math . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50<br>
        4.3.9 String . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50<br>
        4.3.10 Arrays . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50<br>
        4.4 Control structure, loops and functions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51<br>
        4.4.1 If-else . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51<br>
        4.4.2 Switch-case-default . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52<br>
        4.4.3 For loop . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52<br>
        4.4.4 While loop . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52<br>
        4.4.5 do-while . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 53<br>
        4.4.6 for-in loop . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 53<br>
        4.4.7 Continue and break . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 53<br>
        4.4.8 Functions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 54<br>
        4.5 Event handling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 54<br>
        4.6 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 55<br>
        5 jQuery 56<br>
        5.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56<br>
        5.1.1 Requirements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56<br>
        5.1.2 Add contents . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 57<br>
        5.2 jQuery examples . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58<br>
        5.2.1 Add jQuery code . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58<br>
        5.2.2 jQuery in separate file . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 60<br>
        5.2.3 Get input from user . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 61<br>
        5.3 Selectors . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64<br>
        5.3.1 Select elements . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64<br>
        5.3.2 Filters . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67<br>
        5.4 Operations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69<br>
        5.5 Event handling . . . . . . . . . .<br>
         </div> -->
        
        <h1>1.2 First code</h1 > 
<h1>Hello-World</h1> h1 is called header tag <br>
<p>this is the first HTML code </p> p is called pargraph<br>   

<h1> 1.3 Basic Tags </h1>
<br>
Tag                        Description                             Example
h1, . . . , h6           Header tag h1 to h6                     <h2> Hi </h2>
p                     paragraphs (Line changes at the end)       <p> Hi </p>
span                   No line change after span                   <span>Hi</span> Bye.
div                   make division between contents            <div> . . . </div>
a                         hyperlink                           see Section 1.9
center                  Move content to center                <center> Hi </center>
br                     Line break (no closing tag)            <br /> or <br>
hr                    horizontal line (no closing tag)        <hr /> or <hr>
pre                     preserve formatting                   <pre> . . . . </pre>
table                       insert table                        see Section 1.5




<h1>Headings 2 </h1>  to
<h6>Heading 6</h6><br>
<p>This is Paragraph</p><br>
<span>The <strong> "br"</strong> tag is used after span to break the line </span><br>

<div style="color:blue">
The'div' tag can be used for formatting the tags inside it at once using 'style' and 'classes' ..etc<br>
<p>This paragraph is inside the 'div' tag </p>
<span>This span is indside the paragraph</span><br/>
<a href="https://www.google.com" >click here</a> anchor tag<br/>

</div> 

<center>
    <h3>Heading 3 is centered</h3><br/>
    <p><span>Centered span is indside the paragraph</span></p>
</center><br/>

Two horizontal line is drawn using two 'hr' tag.
<hr/>
<hr>

<pre>'pre' tag preserve the formatting (good for writing codes)

#python code

x=32;
y=23;
print(x+y)

</pre>

<h1>1.4 Attributes</h1>
• An attribute has two parts i.e. ‘name’ and ‘value’. For example, in the below code, name and value of
the attribute are ‘style’ and ‘blue’ respectively.<br>
<div style="color:red;">
<h1>hai</h1>
</div> 

<h1>1.4.2 Core attributes</h1>
• id: The 'id' is the unique name which can be given to any tag. This is very useful in distinguishing the elements with the other elements.
<p id='para1' >This is paragraph with id 'para1' </p><br>
<p id='para2'>This is paragraph with id 'para2'</p><br>

• Class: The attribute 'class' can be used with multiple tags. This is very useful in making groups in HTML design.<br>
<p class="c_blue" >This is paragraph with class 'blue'</p><br>
<span class="c_blue" >This is  span with class 'blue'</span><br/><br>

•Style: We already see the example of style attribute, which can be used to change the formatting of the text in HTML design. We can specify various  styles which are discussed in chapater 2.<br>
<p style="color:whitesmoke; font-weight:bold; ">style attribute is used for color and bold </p><br>

<span><strong>Note:</strong> Above three attributes are used with ‘CSS (cascading style sheet)’ and JavaScript/jQuery, which are the
    very handy tools to enhance the look and functionalities of the web-page respectively. The CSS is discussed in
    Chapter 2, whereas JavaScript and jQuery are discussed in Chapter 4 and Chapter 5 respectively.</span><br><br>

• Also we can define <strong>multiple attributes </strong> for one tag as shown below,<br><br>

<p class="c_blue" id="para1" style="font-weight:bold; color:red;">Multiple attrobutes</p><br>
•The other useful attributes are listed in <strong>Table 1.2</strong> <br><br>

<center><strong>1.2: List of attributes</strong></center>


Name                        Values                                Description
id                      user defined names                      <p id=’p_1’> Hi </p><br>
class                   user defined names                       <p class=’p_class’> Hi  </p><br>
style                  CSS styles                              <p style='color:red; font-weight:bold;'> Hi </p><br>
align                 left, right, center                        horizontal alignment<br>
width                numeric value or % value                  width of images and tables etc.<br>
height               numeric value                           height of images and tables etc.<br>

<strong>1.5 Tables</strong> 
<h5>In this section, we will learn to draw tables along with some attributes which are discussed in Table 1.2. Rable 1.3 shows
    the list of tahs available to create the table, which are used in Listing 1.1.
</h5>
<center>Table 1.3. Tags and attribute for creating tables</center><br>
<center> <table bgcolor="red"  style="text-align:center; font-weight: bolder;" border="1" bordercolor="black" width="490" >  
    <tr > <td>Tag </td>           <td>  Description</td><br></tr>
    <tr> <td>  table </td>     <td>beginning and end of table</td></tr> <br>
    <tr><td>tr</td><td> row of table</td></tr><br>
    <tr><td> th </td><td>header cell</td></tr> <br>
    <tr><td>td </td><td>data cell</td></tr><br>                       
    <tr><td><strong> Attributes:=</strong></td><td></td></tr><br>                      
    <tr><td>  rowspan </td><td>number of rows to merge</td></tr><br>
    <tr><td>colspan</td><td>number of columns to merge</td></tr><br>                
    <tr><td> border </td><td> width of border</td></tr> <br>                    
    <tr><td>cellpadding</td><td> width of whitespace between two border</td></tr><br>  
    <tr><td> cellspacing </td><td> width of whitespace within a border</td></tr><br>
    <tr><td>bgcolor</td><td>background color</td></tr><br>
    <tr><td> bordercolor  </td><td>color of border</td></tr> <br>
    <tr><td>width   </td><td> width of table (numeric or %)</td></tr><br>                 
    <tr><td> height   </td><td> height of table (numeric)</td></tr><br>              
    <tr><td> caption</td><td> caption for table</td></tr> </table> </center><br>

    • Some of the attributes of Table 1.3 are used in below example,<br> <br>
<center>Listening 1.1: Table with border and color</center> <br> 



<!-- border-color, width and height --><br>
<table border="1" bordercolor="black" width="450" height="100" >
   <caption>Table 1 : Various tags of table</caption>
    <tr bgcolor="red" ><!-- row-->
        <th>column 1</th><!-- header -->
        <th>column 2</th>
        <th>column 3</th>
    </tr>
    <tr bgcolor="cyan">
        <td>Data 1 </td><!-- backgrpund color -->
        <td>Data 2</td><!-- data -->
        <td>Data 3</td>
    </tr>
    <tr bgcolor="yellow">
        <td colspan="2" >New Data 1</td><!-- column span -->
        <td>New Data 2</td><!--- data -->
    </tr>
</table>
<!-- width in % --><br>
<table border="1" bordercolor="red" width="75%" margin="15px" heigth="15"><br>
 <caption>Table 2: width is 80%</caption>
 <tr bgcolor="yellow" ><br>
    <th>Column 1</th>
    <th>column 2</th>
    <th>column 3</th>
 </tr> 
 <tr style="text-align:center;" bgcolor="green">
    <td>data 1</td>
    <td>Data 2</td>
    <td>Data 3</td>
 </tr>  

</table><br>

<center><strong  >1.6 Text formatting</strong></center>

<h4>In this section, we willl see some of the text formatting options (see table 1.4)e.g. bold, italic , subscript and strike </h4><br>

<center><p1>Table 1.4 : Text formatting</p1></center>
<center>
<table border="1" bordercolor="red" width="75%" height="50"  >
        <tr bgcolor="yellow"><th>Tag</th><th>Description</th></tr>
        <tr bgcolor="yellow"><th>b</th><th>hold</th></tr>      
        <tr bgcolor="yellow"> <th>i</th><th>italic</th></tr>  
        <tr bgcolor="yellow"><th>u, ins</th><th>underline</th></tr>  
        <tr bgcolor="yellow"> <th>strike, del</th><th>strike</th></tr>  
        <tr bgcolor="yellow"><th>sup</th><th>superscript</th></tr>  
        <tr bgcolor="yellow"><th>sub</th><th>subscript</th></tr>  
        <tr bgcolor="yellow"><th>big</th><th>big size text</th></tr>  
        <tr bgcolor="yellow">  <th>small</th><th>small size text</th></tr>  
</table>
</center><br>
• Below are the some of the examples of text formatting, whose results are shown in fig. 1.4,<br>
<!-- Text formatting -->
<p>This is <b>bold</b>text</p>
<p>This is <strike>striked</strike>text</p>
<p>this water in chemical term as H<sup>2</sup>O</p><br>
<p>This water chemical term is H<sub>2</sub>O</p><br>
 <center><strong>1.7 Images</strong></center></body><br>
 Images tag  has two important attributes i.e, 'src' and 'alt' as described below.<br>
    • src: tells the location of 'images' file e.g, in Line 2 the image 'logo.jpg' will be searched inside the folder 'img'. <br>
    • alt: is the 'alternatee text' which is displayed if image is not found. For example.  in Line 6, the name of the
     image is incorrectly written i.e, 'logoa'(instead of 'logo'), therfore the value of 'alt' i.e, 'Missing Logo.jpg'
     will be displayed as shown in Fig 1.5.<br><br>
<!--Images-->
<img src="C:\Users\kumar\OneDrive\Pictures\Camera Roll\WIN_20220712_13_49_02_Pro.jpg" width="20%" />
<br/><br/>
<center><img src="D:\old data\madan\DCIM\Camera\20220225_140308.jpg"width="35%" height="250"/></center><br>

<p1><strong>Note:</strong>We can use other attributes as well e.g. 'height', 'align'and'border' etc.</p1><br><hr>

<center><strong>1.8 Lists</strong></center><br>
There are three of lists in HTML.<br>
•  Unordered list: bullet are used in it (see Lines 2 and 9)<br>
•  Ordered list: numbers are used in it (see Lines 15,22 and 28)<br> 
•  Definition list: This can be used for writing definations in HTML (see Line 35)<br><br>


<!--Lists-->
<!-- unordered list -->
<ul>Unordered list
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ul>

<ul type="square" ><-- Change bullets: 'square', 'circle' or 'disc' -->
    
<li>pen</li>
<li>pencil</li>
<li>Eraser</li>

</ul>
<ul type="circle" >
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ul>

<-- orderd list --
<ol>Ordered list
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ol>

<ol type="i"><!-- change style: 'i','I','a' or 'A' -->
<li>Pen</li>
<li>Pencil</li>
<li>Eraser</li>      

</ol>

<ol type="i" start="5" > **It stars from 'v'**
    <li>pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ol>

<ol type="I" >
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ol>

<ol type="a" >
    <li>pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ol>

<ol type="A" >
    <li>pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
</ol>

<-- Defination list --
<dl>
    <dt><h4>HTMML Defination List</h4></dt>
    <dd>HTML is easy</dd>
    <dd>HTML is good</dd>
</dl>
<hr/><br><hr>
<center><strong>1.9 Links</strong></center><br> 


<!--  links--> 
<p1>Go to paragraph with <a href="#para1"> id='para1' </a></p1><br>

<p1> Go to Paragraph 2 with<a href=#para2>id='para2</a></p1><br>
<a href="http://www.google.com">Go to google</a><br>
<p1><a href="js.html" target="_self" >Javascript Totorial</a>in same window.</p1><br>
<p1><a href="js.html" target="_blank" >Javascript Tutorial</a>in new window</p1><br>
<p1><a herf="http://pythonsp.readthedocs.io/pdf">Download PDF, DOC or ZIP Files</a> </p1><br>
<p1><a href="mailto:madankumargowd@gmail.com" >Email me</a></p1><br>
<p1><a href="href=mailto:madankumargowd@gmial.com?subject-Feedbac&body=Your feedback here" >Feedback email</a></p1><br> 


<strong>Note:</strong>We can change the color of the links using 'alink (active links)', 'link' and 'vlink (visited link', by defining these attributes in the 'body tag as show below')<br>
<-- <body alink="green" link="blue" vlink="red"> --  <hr/><br><hr>
  <center><strong>1.10 Forms</strong></center><br>
  Forms can have different types of controls to collect the input-data from users, which are listed below and shown in Table 1.5,<br>
<ul>
    <li>Text type</li>
    <li>Text area </li>
    <li>Radio button</li>
    <li>Checkbox</li>
    <li>Select box</li>
    <li>File select</li>
    <li>Buttons</li>
    <li>Submit and reset buttons</li>
    <li>Hidden input</li>
</ul><br>  



<center>Table 1.5: List of control inputs and their attributes</center><br>
<center><table bgcolor="lightblue" border="2" bordercolor="green" >
    <tr><th>control</th><th>Attributes</th><th>Values</th> <th>Description</th> </tr>
<tr > <th bgcolor="red">Input:text</th><th>type</th><th>text,password</th><th></th> </tr>
 <tr><th></th><th>value</th><th>user-defined</th><th>initial value in the area</th></tr>
 <tr><th></th><th>name</th><th>user-defined</th><th>name send to server</th></tr>     
 <tr><th></th><th>size</th><th>numeric value</th><th>width of the text area</th></tr>
 <tr><th></th><th>maxlength</th><th>numeric value</th><th>maximum number of characters</th></tr>  
 <tr><th bgcolor="red" >Input:ratio</th><th>type</th><th>radio</th><th></th></tr> 
 <tr><th></th><th>name</th><th>user-defined</th><th>name send to server</th></tr> 
 <tr><th></th><th>value</th><th>user-defined</th><th>value of the box if selected</th></tr>   
 <tr><th></th><th>checked</th><th></th><th>check the button by default</th></tr>  
 <tr><th bgcolor="red" >Input:check box</th><th>type</th><th>checkbox</th><th></th></tr>
 <tr><th></th><th>name</th><th>user-defined</th><th>name send to server</th></tr>
 <tr><th></th><th>value</th><th>user-defined value</th><th>value of the box if selected</th></tr>   
 <tr><th></th><th>checked</th><th></th><th>check the box by default</th></tr>     
 <tr><th bgcolor="red" >Input:button</th><th>type</th><th>button</th><th>trigger client side script</th></tr>
 <tr><th></th><th></th><th>submit</th><th>submit the form and run 'action'</th></tr>
 <tr><th></th><th></th><th>reset</th><th>reset form</th></tr>  
 <tr><th></th><th></th><th>image</th><th>create image button</th></tr>
 <tr><th></th><th>method</th><th> get, post</th><th>get or post method</th></tr>        
 <tr><th></th><th>action</th><th>user-defined</th><th>action to perform on <strong>Submit</strong></th></tr>  

 <tr><th bgcolor="red" >Input:hidden</th><th>type</th><th>hidden</th><th>will not display on html, but can be used</th></tr>
 <tr><th></th><th></th><th></th><th>for sending information to server</th></tr>    

 <tr><th bgcolor="red" >Selection  box</th><th>name</th><th>user-defined</th><th>name send to server</th></tr>
 <tr><th></th><th>size</th><th>numeric-value</th><th>enables scroll (default dropdown)</th></tr>    
 <tr><th></th><th>multiple</th><th>numeric-value</th><th>select multiple items</th></tr> 
 <tr><th></th><th>value</th><th>user-defined value</th><th>value of the item if selected</th></tr> 
 <tr><th></th><th>selected</th><th></th><th>select item by default</th></tr>    

 <tr><th bgcolor="red" >Text area</th><th>rows,cols</th><th>numeric value</th><th>number of rows and cols</th></tr>  
 <tr><th></th><th>name</th><th>user-defined</th><th>name send to server</th></tr>  

</table></center><br> 


• Below are the example of the control inputs described in <strong>Table 1.5</strong> <br>  

<-- Forms --
<form>
<h4>Text input</h4><br>
Name: <input type="text" name="user_name" size="4" value="" maxlength="10"><br>
Password: <input type="password" name="user_password"><br>

<h4>Radio button name should be same</h4>
<input bgcolor="red" type="radio" name="r_gender">male<br>
<input type="radio" name="r_gender">Female<br>
<input type="radio" name="r_gender">Infant

<h4>check box : name should be  different</h4>
<input type="checkbox" name="c_male" checked> male<br>
<input type="checkbox" name="c_female">Female<br>
<input type="checkbox" name="c_infant" >Infant

<h4>Select Box: drop-down</h4>
<select name="s_box" >
    <option value="s_male" >Male</option>
    <option value="s_female" selected >Female</option>
    <option value="s_infant" >Infant</option>
</select>

<h4>Select box: scroll</h4>
<select name="s_box" size="4" multiple >
    <option value="s_male" selected >Male</option>
    <option value="s_female" selected >Female</option>
    <option value="s_infant" > Infant 1</option>
    <option value="s_infant" selected >Infant 2</option>
    <option value="s_infant"  >Infant 3</option>
    <option value="s_infant" > infant 4</option>
</select> 

<h4>Text area</h4>
<textarea rows="10" cols="80" name="txt_area" >Initial Text
  x=2
  y=3
</textarea><!--- formatting work as pre --> 
<!--</form><br> -->

• Below is the code which shows the working of various buttons. Note that <strong>method</strong>and <strong> action</strong> are defined
in this form, which will be triggered on 'submit' button. Lastly, 'hidden' option is used in this example.<br>
<form method="get|post" action="jquery.html" >
<h4>Button and Hidden</h4>
New<input type="text" name="user_name" size="4" value="Meher" maxlength="16"/><br>
Password<input type="password" name="user_pass"><br>
<input type="button" onclick="alert('Hello')" name="b_alert" value="Say Hello"/><br>
<input type="submit" name="b_submit" value="Go To jQuery"/><br>
<input type="reset" name="h_reset" value="Reset"/><br>
<input type="hidden" name="h_data" value="html_tutorial"/>
</form><br><br><hr>
<center  ><h1>
<strong >Chapter 2</strong><br>
<strong>Cascading Style Sheets (CSS)</strong></h1></center><br>
<p1><strong>2.1 Introduction</strong></p1><br><br>
CSS is used to enhance the look of thw eb page. In Section 1.4.2, we saw the attribute 'style', which is used for
changing the color of the text. Let's rewrite the example of 'style' as show in next section.<br><br>
<p1><strong>2.1.1 Inline CSS</strong></p1><br><br>
• Below code is an example of 'inline CSS', where the styles are defined inside the individual tags.<br>
<-- css.html --><br>  



<form>
    <h2 style="color:blue" >Heading 1</h2>
    <h2 style="color:lightblue" >Heading 2</h2>
    <h3 style="color:skyblue" >Heading 3</h3>
</form><br>
In the above code, we have three ‘headings’ with font-color as ‘blue’. Suppose, we want to change the color to red,
then we must go to to individual ‘h3’ tag and then change the color. This is easy in this case, but if we have 100
headings in 5 different ‘html’ files, then this process is not very handy. In such cases, CSS can be quite useful as
shown in next section.<br><br>


<p1><strong>2.1.1 Embedded CSS</strong></p1><br><br>
In the below code, the style is embedded inside the ‘style’ tag as shown in Lines 8-17. Here, we have defined two
classes i.e. ‘h3_blue (Lines 21-23)’ and ‘h3_red (Lines 26-28)’. Then, the selectors at Lines 9 and 13 targets the
class ‘h3_blue’ & ‘h3_red’, and change the color to blue and red respectively. In this chapter, we will discuss the
selectors (e.g. h3.h3_blue) in more details.<br><br>
<strong>Note:-</strong><br>
• In CSS, the comments are written between /* and */.<br>
• CSS has three parts,<br>
    -<strong>Selectors</strong>   e.g. h3.h3_blue<br>
    -<strong>Properties</strong> e.g. color<br>
    -<strong>Values</strong> of properties e.g. red<br> 




<form>
    <h3 class="h3_blue" >Heading 1</h3>
    <h3 class="h3_red" >Heading 2</h3>
    <h3 class="h3_green" >Heading 3</h3>
    <br><br>
    <h3 class="h3_yellow" >Heading 4</h3>
    <h3 class="h3_pink" >Heading 5</h3>
    <h3 class="h3_gray" >Heading 6</h3>
</form><br><br>
<strong>2.1.3 Externals CSS</strong><br>
We can write the ‘CSS’ code in different file and then import the file into ‘html’ document as shown in this section.
In this way, we can manage the files easily.<br><br>
• The ‘CSS’ code is saved in the file ‘my_css.css’ which is saved inside the folder ‘asset/css’<br><br>
<form><<p1>in CSS.css we are writting like this<br>
h3.h3_blue{
    color:blue;
}
h3.h3_red{
    color:red;
}
</form><br><br> 

• Next, we need to import the CSS file into the ‘html’ file as shown in Line 7.
<---   <link rel="stylesheet"  type"text/css"  href=" write here where css i  path is loacted"  --  <br><br>
<strong>2.2 Basic CSS Selectors</strong><br><br>
There are three of selectors in CSS<br>
•<strong>Element</strong> : can be selected using it's name e.g. 'p', 'div' and 'h1'etc.<br>
•<strong>Class</strong> : can be selected using 'className' operator e.g. 'h3_blue',<br>
•<strong>ID</strong> : can be selected using '#idName' e.g. '#my_para.<br><br>
We will us following HTML for understanding the selectors,<br>
<form>
    <h4>CSS Selectors</h4>
    <p1 class="c_head" >Paragraph with class 'c_head'</p1><br><br>
    <p1 id="i_head" >Paragraph with id 'i_head</p1>
</form><br><br>
• Below code shows the example of different selectors, and the output<br><br>
<strong>2.3 Hierarchy</strong><br>
In previous section, we saw the example of selectors. In this section, we will understand the hierarchy of the styling-operations.<br>
<hr><strong>Important:</strong><p1> Below is the priority level for the CSS,</p1><hr/>
<br><br>
• Priority level:<br>
  --ID (higher priority)<br>
  --Class<br>
  --Element<br>
  • if two CSS has same priority, then CSS rule at the last will be applicable.<hr><br>
  •Below is teh html code with following tags,<br>
  --'p'tag<br>
  --'p'tag with class 'c_head'<br>
  --'p'tag with class 'c_head' and id 'i_head'<br>
  <form>
    1<p>Heading</p>
    2<p  class="c_head">hai this is heading</p><br>
    3<p class="c_head" id="i_head">hai this is heading</p>  In this **Id** id="i_head"  is is important priority compare to class class="c_head" 
  </form><br>

  Below is the CSS code. Let's understand the formatting of all three 'p' tags individually. The results ares shown below<br>
  • <strong>'p'tag at number 3 of of HTML :  </strong> Since, 'id' has highest priority, therfore CSS rules for #'i_head' (number 2) will<br>
  not be overridden by number 1; hence the color is <strong>red</strong>. Line 3 has 'p'tag, therfore 'font-variant' rule will be <br><br>
  <strong>2.4 More selectors :-</strong><br><br>
  Below table shows the combination of selectors to target the various elements of the HTML. Also, some of the <br>example of 'Attribute selector' is shown in this section.<br><br>
  <center>Table 2.1: List of selectors</center>



 
<center><table border="2" bordercolor="red" >
       <tr>
        <th>Selectors</th><th>Description</th>
       </tr>
       <tr><td>h1, p, span etc.</td><td>element selector</td></tr>
       <tr><td>className</td><td>class selectors</td></tr>
       <tr><td>#idName</td><td>id selector</td></tr>
       <tr><td>*</td><td>Universal selector (selects everything)</td></tr>
       <tr><td>h1.className</td><td>select h1 with class 'className'</td></tr>
       <tr><td>h1#idName</td><td>select h1 with id 'idName'</td></tr>
       <tr><td>p span</td><td>descendant selector (select span which is inside p)</td></tr>
        <tr><td>p > span</td><td>child selector ('span' which is direct descendant pf  'p') </td></tr>
        <tr><td>h1, h2,p</td><td>group selection (selct h1, h2 and p)</td></tr>
        <tr><td> [my_id]</td><td>select 'span' with attribute 'my_id'</td></tr>
        <tr><td>span[my_id=m_span]</td><td>select 'span' with attribute 'my_id=m_span'  </td></tr>        
    </table></center><br><br>
    <strong>2.4.1 Attribute selector </strong><br>
    • Add below code at the end of the html file. In these lines 'custom attributes ' are added (i.e. my_id)<br>
    <span my_id="my_span" >Span with attribute 'my_id' with value 'm_span'</span>
    <br>
    <span my_id="my_span2" >Span with attribute 'my_id' with value 'm_span2' </span><br><br>
    <strong>2.5 More properties</strong><br><br>
    Table 2.2 shows the some more important properties which can be used in CSS<br><br>
    <center>Table 2.2 More CSS properties</center><br> 
    
  <center>  <table border="2" bordercolor="yellow" >
        <tr><th>Property</th><th>Syntax</th><th>Description/possible values</th></tr>
        <tr><td>size</td><td>20%</td><td>size=20%</td></tr>
        <tr><td></td><td>20px</td><td>20 pixel</td></tr>
        <tr><td></td><td>2em</td><td>2*font-size</td></tr>
        <tr><td></td><td>2mm, 2cm, 2in</td><td>2 mm, cm and inch</td></tr>
        <tr><td>color</td><td>names</td><td>e.g. red, blue, green</td></tr>
        <tr><td></td><td>hex code (#RRGGBB OR #RGB)</td><td>#FFF000 OR #FFF</td></tr>
        <tr><td></td><td>rgb(num, num, num)</td><td>rgb(0, 0, 255) or rgb (20%, 10%, 70%)</td></tr>
        <tr><td>link</td><td>a:link</td><td>a:link {color:red} </td></tr>
        <tr><td></td><td>a:hover</td><td></td></tr>
        <tr><td></td><td>a:visited</td><td></td></tr>
        <tr><td></td><td>a:active</td><td></td></tr>
        <tr><td>Font</td><td>font-family</td><td>serif,cursive</td></tr>
        <tr><td></td><td>font-style</td><td>normal, italic, oblique</td></tr>
        <tr><td> </td><td>font-variant</td><td>normal, small-caps</td></tr>
        <tr><td></td><td>font-weight</td><td>normal, bold, bolder, lighter, 100-900</td></tr>
        <tr><td></td><td>font-size</td><td>10px, small, medium, large etc..,</td></tr>
        <tr><td>Text </td><td>color</td><td>red, #FFF</td></tr>
        <tr><td></td><td>letter-spacing</td><td>10px</td></tr>
        <tr><td></td><td>word-spacing</td><td>10 px</td></tr>
        <tr><td></td><td>tetx-align</td><td>right, left , center</td></tr>
        <tr><td></td><td>text-decoration</td><td>underline, overline, lowercase, none</td></tr>
        <tr><td></td><td>text-transform</td><td>capitalize, uppercase, lowercase, none</td></tr>
        <tr><td></td><td>white-space</td><td>pre, normal, nowrap</td></tr>
        <tr><td>text-shadow</td><td>text-shadow:5px 5px 8px red;</td><td></td></tr>
        <tr><td>Image</td><td>border</td><td>'1px', or '1px solid blue'</td></tr>
        <tr><td></td><td>height, width</td><td>100px, 20%</td></tr>
        <tr><td>Border</td><td>border-style</td><td>solid, dashed, dotted, double, none etc,</td></tr>
        <tr><td></td><td>border-top-style</td><td></td></tr>
        <tr><td></td><td>border-bottom-style</td><td></td></tr>
        <tr><td></td><td>border-left-style</td><td></td></tr>
        <tr><td></td><td>border-right-style</td><td></td></tr>
        <tr><td></td><td>border-width</td><td>4px, 4pt</td></tr>
        <tr><td></td><td>border-bottom-width</td><td>similarly use 'top', 'left', 'right' </td></tr>
        <tr><td></td><td>border (shortcut)</td><td>'1px solid blue'</td></tr>
        <tr><td>Margin</td><td>margin, margin-left etc,</td><td></td></tr>
        <tr><td>Padding</td><td>padding (top, bottom, left, right)</td><td>'10px 10px 2px 2px' or '10px 2px</td></tr>
        <tr><td></td><td>padding-right, padding-left etc.</td><td></td></tr>
    

    </table></center><br><br> 

    
    <center><strong>Chapter 3</strong><br><strong><h3>Bootstrap</h3></strong></center>
    <h3>3.1 Introduction :-</h3>
    one of the problem with basic. HTML design is that the webpage may look different browser or device
    (e.g. mobile, tablet and laptop). Therefore, we may need to modify the code according to browser or device. The
    problem can be easily resolved by using Bootstrap.<br><br>
    
    Bootstrap is a frame work which uses HTML, CSS and JavaScript for the web design. it is supported by all the major browsers e.g. Firefox, Opera and chrome etc. Further, Bootstrap includes serveral predefined classes for easy layouts e.g. Firefox, Opera and Chrome etc.
    Further, Bootstrap includes serveral predefined classes fot easy layouts e.g. dropdown buttons, navigation bar and alerts etc. Lastly, it is responsive in nature i.e. the layout changes automatically according to the device e.g. mobile or laptop etc.<br><br>
    <h3>3.2 Setup</h3>
    Bootstrap needs atleast 3 files for its opertaion which can be download from thw Bootstrap website.<br><br>
    <strong>• bootstrap.csss :</strong>This file contains various CSS for bootstrap.<br>
    <strong>• bootstrap.js : </strong>This file contains various JavaScript functionalities e.g. dropdown and alerts etc.<br>
    <strong>• jQuer.js : </strong>This file is the jQuery library which can be downloaded from the 'jQuery' website.<br>
    It is required for proper workin of 'bootstrap.js'.<br><br>
    <h3>3.2.1 Download and include files</h3>
    These files are downloaded and saved inside the 'asses' the folder. Next, we need to include these files in the HTML documents= as below.<br>
    <strong >Note  -- </strong> <h3>Bootsrap is will link in head Tag as  <link href="assest/css/bootstrap.min.css" rel="stylesheet"  ></h3>
   
    <strong>3.2.2 Add CDN</strong><br>
    Another way to include the files is CDN. In this method. we need not to download the files, but provide the links to these files. Note that, in this case the code will not work in offline mode.<br><hr><strong>Note: </strong>In this tutorial, we have used the first method i.e,. download the files and include in the html document.<hr/> <br>
    <h3>3.2.3 Check setup</h3>
    Let's write our first code to check the correct setup of the Bootstrap.<br>
    <hr><strong>Note : </strong>We need to memorize the code for creating the 'dropdown' button. All the templates are available on the <mark style="background-color:blue;" >Bootstrap website</mark>. Copy and paste the code from there and the modify the code according to need as shown in this tutorial  <hr/><br>
   <center>
    <div class="dropdown show" >
        <button class="btn btn-primary dropdown-toggle " href="#" role="button" data-toggle="dropdown" id="dropdownMenuItem" aria-haspopup="true" aria-expanded="false" >Click to view drop down</button>
        <div class="dropdown-menu" >
            <a class="dropdown-item" href="#" style="background-color:red;" >Action</a>
            <a class="dropdown-item" href="#" style="background-color:green;">Another action</a>
            <a class="dropdown-item" href="#" style="background-color:yellow;" >second action</a>
        </div>
    </div>
   </center><br>


   <center>
    <div class="dropdown " > 
    <button class="btn btn-success dropdown-toggle" href="#" id="dropdownMenu" role="button" data-toggle="dropdown"  aria-haspopup="true" aria-expanded="false" >Click to open</button>
    <div class="dropdown-menu" >
        <a class="dropdown-item" href="#" style="background-color:aqua;" >Action</a>
        <a class="dropdown-item" href="#" style="background-color:aquamarine;" >At Action</a>
        <a class="dropdown-item" href="#" style="background-color:cadetblue;" >Second action</a>
    </div>
    </div>
   </center><br>
 
   
   <center>
    <-- Example single danger button -->

<div class="btn-group">
    <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
      Action
    </button>
    <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
      <div class="dropdown-divider"></div>
      <a class="dropdown-item" href="#">Separated link</a>
    </div>
  </div>
   </center>

   

   <h3>Learning about Bootstrap </h3>
   <table>
    <tr>   
        <th>Layout:=
        Methods :=</th> </tr>
 <tr> <th>   Flexbox :=
    Flexbox properties :=
    Flex-container (d-flex) :=
    flex-direction (   row/column) := 
    justify-content (start/center/end) :=</th></tr>
    <tr>
  <th>  Bootstrap :=
    Flexbox class Names</th>
    
    
    </tr>
   </table>
   <center>
    <div class="container"   > 
        <div class="favoutite-background-card-container "  >
            <h1>Tourism</h1>
            <p>plan your trip</p>
            <div class="button" >
            <button class="btn btn-success " style="width:125px;   "  ">Get Started</button>
        </div>
    </div>
    </div>
   </center>

    <div class="favoutite-background-container2" >
        <h3 class="favoutite-heading" >Favourite places</h3>
<div class="favoutite-background-card-container1 d-flex flex-row justify-content-end" >
  <div>
    <h1 class="favoutite-heading2" >Taj Mahal</h1>
    <p class="favoutite-paragraph" >Construction of the mausoleum was essentially completed in 1643, but work continued on other phases of the project for another 10 years. The Taj Mahal complex is believed to have been completed in its entirety in 1653 at a cost estimated at the time to be around ₹32 million, which in 2020 would be approximately ₹70 billion (about US $1 billion). The construction project employed some 20,000 artisans under the guidance of a board of architects led by the court architect to the emperor, Ustad Ahmad Lahauri. Various types of symbolism have been employed in the Taj to reflect natural beauty and divinity.</p>
</div>
    <img src="https://akm-img-a-in.tosshub.com/indiatoday/images/story/202001/taj-mahal-3212516_1280.jpeg?eYW.7ThdbzabwLFW1ymfEYtcoJ8wS6Bm&size=770:433" class="favoutite-place-card-image"/>
    
</div>
<div class="favoutite-background-card-container2 d-flex flex-row justify-content-end " >
   <div>
    <h1 class="favoutite-heading2" >Golden temple</h1>
    <p class="favoutite-paragrapg2" >The man-made pool on the site of the temple was completed by the fourth Sikh Guru, Guru Ram Das, in 1577.[6][7] In 1604, Guru Arjan placed a copy of the Adi Granth in Harmandir Sahib.[3][8] The Gurdwara was repeatedly rebuilt by the Sikhs after it became a target of persecution and was destroyed several times by the Mughal and invading Afghan armies.[3][5][9] Maharaja Ranjit Singh, after founding the Sikh Empire, rebuilt it in marble and copper in 1809, and overlaid the sanctum with gold leaf in 1830. This has led to the name the Golden Temple</p>
</div>
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Golden_Temple%2C_Amritsar_03.jpg" class="favoutite-place-card-image2" />

</div> 
<div class="favoutite-background-card-container3 d-flex flex-row justify-content-end " >
<div>
    <h1 class="favoutite-heading3" >Mysore Palace</h1>
<p class="favoutite-paragraph3" >The Mysore Palace, also known as Amba Vilas Palace, is a historical palace and a royal residence (house). It is located in Mysore, Karnataka. It used to be the official residence of the Wadiyar dynasty and the seat of the Kingdom of Mysore. The palace is in the centre of Mysore, and faces the Chamundi Hills eastward. Mysore is commonly described as the 'City of Palaces', and there are seven palaces including this one. However, the Mysore Palace refers specifically to the one within the new fort</p>
</div>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Mysore_Palace_%288113480008%29.jpg/1280px-Mysore_Palace_%288113480008%29.jpg" class="favoutite-place-card-image3" />
</div>
<div class="favoutite-background-card-container4 d-flex flex-row justify-content-end " >
 
<img src="https://images.newindianexpress.com/uploads/user/imagelibrary/2021/4/10/w900X450/fsfsfs.jpg?w=720&dpr=1.3" class="favoutite-place-card-image4" />
<div>

    <h1 class="favoutite-heading3" >Varanasi Temple</h1>
    <p class=".favoutite-paragraph3">LUCKNOW: Get ready for a gala inauguration of the Kashi Vishwanath Corridor on  December 13 when Prime Minister Narendra Modi will launch his dream project. The ceremony will be aired live in 20,000 temples across the country. ADVERTISEMENTAds by 
        The PM will reach the venue on a boat via the holy Ganga to inaugurate the project worth over Rs 700-crore. The three-day extravaganza that will follow on December 12, 13 and 14 will be celebrated like Diwali and Dev Deepawali with huge participation by people of Varanasi.        Direct access to the Kashi Vishwanath Dham temple from the side of river Ganga has become possible with the completion of the project that had started in March 2019.</p>
</div>
</div>
<div class="favoutite-background-card-container2 d-flex flex-row  " >

  <h1>Tenplaes</h1>
    <img src="https://images.newindianexpress.com/uploads/user/imagelibrary/2021/4/10/w900X450/fsfsfs.jpg?w=720&dpr=1.3" class="favoutite-place-card-image5" />


</div>
</div>

<div class="favourite-background-container" >
<img src="https://media.istockphoto.com/photos/diwali-oil-lamp-picture-id803533956"  class="favourite-image" />

    <div class="d-flex flex-row justify-content-center">
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div>
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div>
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
  
</div>

<div class="d-flex flex-row justify-content-center">
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div>
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div>
    <div class="favourite-card-item" >
        <h1>
            jhvbhh
        </h1><p>cfrefccxcb</p>
    </div> 
  
</div>
<button class="btn btn-info" >View More</button>
</div>
  


<h3>3.3 Grid System </h3><br>
Bootstrap divides the<strong>each row</strong>  into <strong>12 columns.</strong>  Then following commands can be used to specify the width
the columns<br>
• <strong>col-lg-4 :</strong> It will select 4 columns. Choose any number between 1-12. The ‘lg’ stand for large screen (e.g.
large computer screen).<br>
• <strong>col-md-5 :</strong> : ‘md’ = medium screen<br>
• <strong>col-sm-3 :</strong>  ‘sm’ = small screen<br>
• <strong>col-xs-3 :</strong>  ‘xs’ = extra small screen<br>
• <strong>col-lg-offset :</strong>  skip first 4 columns. Simimlary use ‘md’, ‘sm’ and ‘xs’ with offset<br>
<h3>3.3.1 Example</h3>
Below is an eample of grid system. Read the content to understand it. The resultant webpage is shown below.<hr/>
<mark>Note:</mark><br>
• For easy visualization, in the below code the CSS code  is used to fill the columns with colors and border.<br>
• The columns  should be defined inside the class ‘row’ .<br>
• Also, sum of the widths of individual columns should not be greater than 12.<br>
• Lastly, if we use ‘col-md-4’ without defining the ‘lg’, ‘sm’ and ‘xs’, then ‘md’ rule will be applicable to higher
size screen ‘lg’, but not on the lower size screen ‘sm’ and ‘xs’. Similary, if we use ‘sm’ without defining the
‘lg’, ‘md’ and ‘xs’, then rule will be applicable to higher size screen i.e. ‘lg’ and ‘md’ but not on ‘xs’<br><hr>
<div class="row">
    <div class="col-xs-4 col-md-2 ">col-xs-4 ,col-md-2</div>
    <div class="col-xs-4  col-md-6 " >col-xs-4, col-md-6</div>
    <div class="col-xs-4 col-md-4 ">col-xs-4, col-md-4</div>
</div><br>
<h3>3.2.3 Nested columns</h3>
We can further divide a column into small columns by defining a class ‘row' inside the ‘column’.<br>
<div class="row" >
    <div class="col-xs-4 col-md-2 " >col-xs-4, col-md-2</div>
    <div class="col-xs-4 col-md-6 " >
        <div class="row">
         <div class="col-xs-6">col-xs-6</div>
         <div class="col-xs-6">col-xs-6</div> 
    </div>
</div>
<div class="col-md-4 col-xs-4">col-xs-4, col-md-4</div>
</div> <br>
<h3>3.3.3 Offset</h3>
We can skip the example using 'offset'., and the corresponding html page.<br>
<div class="row" >
<div class="col-md-offset-2 col-md-2 " >col-md-2</div>
<div class="col-md-8" >col-md-8</div>
</div><br>
<h3>3.4 Components</h3>
Once we understand the ‘html’, ‘css’ and ‘Bootstrap-grid’ understood, then the use of Bootstrap-components
are straightforward. Just copy and paste the code from the <mark>Bootstrap website</mark> and modify it according to the
requirement.<br>
In this section, we will use following template.<br>

<h3>3.4.1 Labels</h3>
The class ‘label’ is used to create the label .<br>
• The class ‘label-info’ sets the color of the label to ‘blue’ .<br>
• The size of the ‘labels’ can be changes using ‘element’ tags (e.g. ‘h3’ ) outside the ‘span’ tag .<br><hr>
<h3>Example heading <span class="label label-info " >Now</span></h3>
<strong>Note: </strong> Bootstrap provides 6 color option,<br>
• danger<br>
• default<br>
• info<br>
• primary<br>
• success<br>
• warning<br><hr >
<h2>Exanple of bootstrap colors <span class="label label-success" >Now</span></h2>
<h3>Example heading <span class="btn btn-info">New</span></h3>
<a href="#">Example heading <span class="badge" >10</span> </a>
<h3>Label Example<span class="label label-success" >New</span></h3>
<hr>
<strong>Note: </strong> All the codes will be added in the ‘body’ tag, and the new code will be inserted below the previous codes.
Therefore full HTML code is not added in the tutorial.
<hr><br>

<h3>3.4.2 Buttons</h3>
The element ‘button’ can be used to create the button in Bootstrap as shown below,<br><br><hr>
Note:
• We can use ‘lg’, ‘md’ and ‘xs’ etc. to set the size of the button.<br>
• In Line 3, a glyphicon is added (i.e. trash sign). More glyphicon can be found on the<mark>Boostrap-webpage.</mark> <br><hr>
<h3>Buttons</h3>
<button type="button" class="btn btn-primary" >Sign In</button>
<button type="button" class="btn btn-danger" >Delete <span class="glyphicon glyphicon-trash  bi bi-trash" ></span> </button>
<button type="submit" class="btn btn-lg btn-success  bi bi-check-all " >Submit</button>
<button type="submit" class="btn btn-md btn-success" >Submit</button>
<button type="submit" class="btn btn-sm btn-success">Submit</button><hr><br>
<h3>3.4.3 Forms</h3>
in this section,  4 types of forms are added.<br><br>
<h3>3.4.3.1 Basic form</h3>
Output of below code is:=
<br>


<center>

    <h3>Basic form</h3>
    <div class="row">
        <div class="col-md-6 col-lg-12  body-form "  >
<div class="panel-body"  >
<form role="form"  >
    <div class="form-group"  >
<label for="exampleInputEmail" >Email Address</label>
<input class="form-control"  id="exampleInputEmail" type="email" placeholder="Enter email" >
    </div>
<div class="form-group" >
    <label for="exampleInputPassword" >Password</label>
    <input class="form-control" id="exampleInputPassword" type="password" placeholder="Enter password" >
</div>
<div class="form-group" >
    <label for="exampleInputFile" >File</label>
    <input id="exampleInputFile" type="file" >
<p class="help-block" >Example block-level help text here.</p>
</div>
<div class="checkbox" >
    <label>
        <input type="checkbox" >Check me out
    </label>
</div>
<button type="submit" class="btn btn-info" >Submit</button>
</form>
</div>
        </div>
    </div><br><br> 



    <div class="row" >
        <div class="col-md-6 col-lg-12" style="background:rgb(242, 246, 21);  height:auto;">
        <div class="panel-body" >
            <form role="form" >
                <div class="form-group">
                    <label for="exampleInputEmail" >Enter email</label>
                    <input class="form-control" id="exampleInpuEmail"  type="email"  placeholder="Enter mail" >
                </div>
                <div class="form-group" >
                    <label for="exampleInputPassword" >Enter Password</label>
                    <input class="form-control" id="exampleInputPassword" type="password" placeholder="Password here">  
                </div>
                <div class="form-group" >
                    <label for="exanpleInputFile" > </label>
                    <input class="form-control" id="exampleInputFile" type="file" >
                    <p class="file-block" >Eaxmple block-level help text here</p>
                </div>
                <div class="checkbox" >
                    <label>
                        <input type="checkbox" >check me out
                    </label>
                </div>
                <button class="btn btn-success" >Submit</button>
            </form>
        </div>
        </div> 
    </div> <br><br>

    <div class="row" >
        <div class="col-md-6 col-lg-12" style="background-color:rgba(0, 255, 13, 0.499); height:auto;">
           <div class="panel-body" >
            <form role="form" >
                <div class="form-group" >
                    <label for="exampleInputEmail" >Enter Here</label>
                    <input class="form-control" id="exampleInputEmail" type="email" placeholder="enter mail here" >
                </div>
                <div class="form-group" >
                    <label for="exampleInputPassword" > Enter password</label>
                    <input class="form-control" id="exampleInputPassword " type="password" placeholder="enter password here" >
                </div>
                <div class="form-group" >
                    <label for="exampleInputFile" >upload File</label>
                    <input id="exampleInputFile"  type="file" >
                    <p class="file-body" >Please select proper doc's</p>
                </div> 
                <div class="form-group" >
                 <label  >
                    <input type="checkbox" >Check Here
                 </label>
                </div>
                <button class="btn btn-success  bi bi-check-all" >Submit</button>

            </form>
           </div>
        </div>
    </div>
</center> 

<div class="row" >
<div class="  col-md-6 col-lg-12" style="background-color:cadetblue; height:auto;" >
<div class="form-panel" >
    <form role="form" >
        <div class="form-group" >
            <label for="exampleInputEmail" >Enter Email</label>
            <input class="form-control" id="exampleInputEmail" type="email" placeholder="enter mail here" >
        </div>
        <div class="form-group" >
            <label for="exampleInputPassword" >Password here</label>
            <input class="form-control" id="exampleInputPassword" type="password" placeholder="enter password here" >
        </div>
        <div class="form-group" >
            <label for="exampleInputfile" > upload  File </label>
            <input type="file" >
            <p class="file-body" >please upload doc's here</p>
        </div>
        <div class="checkbox" >
            <label for="exampleInputCheckbox" >
                <input type="checkbox" id="exampleInputCheckbox" >Check here</label>
           
        </div>
        <buuton class="btn btn-danger bi bi-check-all " >Submit</buuton>
    </form>
</div>
</div>
 </div><br><br> 


 <h3>3.4.4 Horizontal form</h3>
 Output of below code below form <br>
<h3>Horizontal form</h3>
<div class="row" >
    <div class="col-md-6 col-lg-12" style="background-color:thistle; height:auto;" > 
    <div class="form-body">
        <form class="form-horizontal" role="form" >
<div class="form-group" >
<label for="inputEmail" class="col-lg-2 col-sm-2 control-label " >Email here</label>
<div class="col-lg-10" >
    <input class="form-control" id="inputEmail" type="email" placeholder="enter email here" >
    <p class="email-form" >Eample block-level help text here</p>
</div>
</div>
<div class="form-group" >
    <label for="inputPassword" class="col-lg-6  control-label "  >Enter password</label>
    <div class="col-lg-10" >
    <input class="form-control" id="inputPassword" type="password" placeholder="enter password here" >
</div>
</div>
<div class="form-group" >
    <label for="inputFile " class="col-lg-6 col-md-6 control-label " >Upload file</label>
    <div class="col-lg-10"> 
    <input  id="inputFile" type="file"  >
    <p>Please upload file here</p>
</div>
</div>   
<div class="form-group" >
    <label for="inputCheckbox" class="col-lg-12 col-md-6 control-label" >Check</label>
    <div class="col-lg-10" > 
        <input id="inputCheckbox" type="checkbox" >
    </div>
</div>  
<button class="btn btn-success bi bi-check-all" >Submit</button>   
</form>
    </div>
    </div>
</div> 






<








<CSS>:=

/*p{
    color: aqua;
    background-color: blue;
}
h1{
    color: blue;
    background-color:aqua;
}
h3.h3_blue{
    color:blue;
}
h3.h3_red{
    color:red;
}
h3.h3_green{
    color:green;
}
h3.h3_yellow{
    color:yellow;
}
h3.h3_pink{
    color:pink;
}
h3.h3_gray{
    color:gray; 
} */
/*element selection  */
/*
h4{
    color:blueviolet;
}
/* css selection */
/*
.c_head{
    color:aquamarine;
}
*/
/* id selections */
/*
#i_head{
color:beige;
background-color: aqua;
}
span[my_id]{
    background-color: royalblue;
    color: turquoise;
}
span[my_id="my_span2"]{
    background-color: burlywood;
    color: slateblue;
}
*/
.container{
    background-image: url("https://cdn.pixabay.com/photo/2013/02/21/19/06/drink-84533_960_720.jpg");
    height: 100vh;
    
    background-size: cover;
flex-direction: column-reverse;
display: flex;
justify-content: end;
margin-bottom: 25px;


}
.favoutite-background-card-container{
    padding:25px;
    border-radius: 10px;
    background-color: white;
}
.button{
    align-items: center;
}
.favoutite-background-container2{
    background-image: url("https://gotirupati.com/wp-content/uploads/2017/07/Virupaksha-Temple-Hampi5-copy.jpg");
    background-size: cover;
    height: auto;
    padding:25px;
    margin: 16px;
    
    

}
.favoutite-heading{
    color:red;
    font-family: 'Courier New', Courier, monospace;
    font-style: oblique;
}
.favoutite-background-card-container1{
background-color: white;
border-radius: 8px;
padding: 16px;
margin:10px;
}
.favoutite-heading2{
color:green;
}
.favoutite-paragraph{
    color:cadetblue;
}
.favoutite-place-card-image{
    width: 150px;
    height: 210px;
}
.favoutite-background-card-container2{
    background-color:tomato;
    border-radius: 8px;
    padding: 16px;
    margin: 10px;

}
.favoutite-place-card-image2{
height: 210px;
width: 150px;
}
.favoutite-background-card-container3{
    background-color: wheat;
    border-radius: 8px;
    padding: 16px;
    margin: 10px;
}
.favoutite-heading3{
color: black;

}
.favoutite-paragraph{
color:cornflowerblue
}
.favoutite-place-card-image3{
    height: 210px;
    width:150px;
}
.favoutite-background-card-container4{
background-color: turquoise;
padding: 16px;
margin: 10px;
border-radius: 8px;
}
.favoutite-place-card-image4{
    height: 210px;
    width: 130px;
    margin: 16px;
}
.favoutite-place-card-image5{
    height: 50px;
    width: 30px;
    margin: 16px;
}
.favourite-background-container{
    background-color: lightskyblue;
    height:auto;
    width: auto;
    padding: 9px;
    text-align: center;
}
.favourite-image{
    width: 877px;
    height: 15%;
    padding: 5px;
}
.favourite-card-item{
    background-color: aliceblue;
    height: auto;
    width: 125px;
    border-radius: 15px;
    padding: 15px;
    margin: 15px;
}
.favourite-card1{
    padding-right: 5px;
}


/*  grid system in bootstrap and difference in displays   */
/*
.col-xs-1,.col-xs-2,.col-xs-3,.col-xs-4,.col-xs-5,.col-xs-6,.col-xs-7,.col-xs-8,
.col-sm-1,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,
.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,
.col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,
.col-xl-1,.col-xl-2,.col-xl-3,.col-xl-4,.col-xl-5,.col-xl-6,.col-xl-7,.col-xl-8{
    background-color: greenyellow;
    color: green;
    font-weight: bold;
    border: 2px solid red;
    height: 3em; /* height of the box */
   /* text-align: center; }/* vertical center the text */ 
*/

.body-form{
    background-color: antiquewhite;
    height: auto;
    border-color: black;
}

/* javascript */
#text{
    color:yellow;
    background-color: aqua;
}
#display{
    color:aquamarine;
background-color: blanchedalmond;    
}
#view{
    color: azure;
    background-color: cadetblue;
}
#parchuri{
    color: tomato;
    background-color: steelblue;
}
#id1{
    background-color: aqua;
    color: black;
    font-weight: bolder;
    font-style: italic;
}























<---JAVASCRIPT-->

<h3>JavaScript</h3>
<form role="form">
    <div class="col-md-6 col-lg-6 form-group" >
        <label for="exampeInputEmail" id="emailChange" >write Email</label>
        <input class="form-control" id="exampleInputEmail"  type="email" placeholder="enter mail here" >
    </div>
<button class="btn btn-success " type="button" onclick='getElementById("emailChange").innerHTML="writing Email"' >click</button>
<button class="btn btn-success " type="button" onclick='getElementById("emailChange").innerHTML="write proper email"' >click</button>

</form>

<center>
    <img src="https://burst.shopifycdn.com/photos/beauty-of-the-lush-green-valley.jpg?width=925&format=pjpg&exif=1&iptc=1" id="image1"  height="100" width="100" ><br><br>
    <button class="btn btn-primary" type="button"  onclick='document.getElementById("image1").src="https://burst.shopifycdn.com/photos/person-walks-in-a-open-air-courtyard.jpg?width=925&format=pjpg&exif=1&iptc=1" ' >click change</button>
    <button class="btn btn-primary" type="button"  onclick='document.getElementById("image1").src="https://burst.shopifycdn.com/photos/water-texture-of-waves.jpg?width=925&format=pjpg&exif=1&iptc=1" ' >click change</button>
    <button class="btn btn-primary" type="button"  onclick='document.getElementById("image1").src="https://burst.shopifycdn.com/photos/beauty-of-the-lush-green-valley.jpg?width=925&format=pjpg&exif=1&iptc=1"' >click default</button><br><br>


<h1 id="text" >changing of color</h1>
<button class="btn btn-success" onclick='document.getElementById("text").style.color="green"' >Change to green</button>
<button class="btn btn-success" onclick='document.getElementById("text").style.color="red"' >Change to red</button>
<button class="btn btn-success" onclick='document.getElementById("text").style.color="yellow"' >default</button><br><br>

<h1 id="hiddenDisplay" > show the detailed display on screen</h1>
<button class="btn btn-success" type="buton" onclick='document.getElementById("hiddenDisplay").style.display="none"' >Hide</button>
<button class="btn btn-success" type="buton" onclick='document.getElementById("hiddenDisplay").style.display="block"' >Display</button>


<h1 id="display" >welocome to my world </h1>
<button class="btn btn-primary" type="button" onclick="madan()"  >SHOW</button>
</center><br><br>
<center>
    <h1 id="view" >Welocme to open documents</h1>
    <button class="btn btn-danger" onclick="kumar()" >open now</button>
<script>

    function kumar(){
        document.getElementById("view").innerHTML="content to be shwon"
    }
</script><br><br>
<h1 id="parchuri">create new things</h1>
<button class="btn btn-info" onclick="parchuri()" >open</button>
<script src="D:\html,css,js\javascript.js"
></script>
</center><br><br>

<center>
    <h1>Output display in JavaScript</h1>
    <h1 id="heading" >hai this </h1>
    <button class="btn btn-primary" onclick="madann()" >open it</button>
    <script>
        function madann(){
            document.getElementById("heading").innerHTML="hello world!"
        }
    </script>
</center><br><br>
<center>
    <h1 id="mad" >hai this is madan</h1>
    <button class="btn btn-success" onclick="mada()" >opening</button>
    <script>
        function mada(){
            document.getElementById("mad").innerHTML="welcome to madan"
        }
    </script>
</center><br><br>
<center>
    <h1 id="madankumar" >hai this madan kumar</h1>
    <button class="btn btn-secondary" onclick="functionn()" >close</button>
<script>
    function functionn(){
   document.write("hai this madan kumar")
    }
</script>    
</center><br><br>
<center>
    <h1 id="alert" >alert message</h1>
    <button class="btn btn-danger" onclick="alerts()" >pop up</button>
    <script>
        function alerts(){
            window.alert("alerst")
        }
        console.log("dbugging purpose","buggin the correct one","hai:this is madan kumar:11345")
    </script><br><br> 
   
    <button class="btn btn-success" onclick="print()" >print</button>
</center><br><br>  

 <script>

function add(){

var a,b,c;
    a=10;
    b=25;
    c=35;
    res=a+b+c;
    document.write("<h1>some of three numbers</h1>",res)
    window.alert("hai this is madan adding numbers"+"<strong></strong>"+res)
}
 </script>
<button type="button" onclick="add()" >adding</button>
<br><br>



<h1>Data types</h1>
<script>
    function add(){
    
    var a,b,c;
    a=10;
    b=3.45
    c="hello";
     document.write("data type of",typeof a)
     document.write("data type of",typeof b)
     document.write("data type of",typeof c)
    }
    </script>

<button class="btn" type="button" onclick="add()" >click Data</button>
<script>
    function adding(){
    var a,b,c;
    a=35;
    b="45";
    c=true; 
    /* object */
  var marks=[90,55,25,63]  
  var students={name:"madan kumar", secondnamne:"parchuri", rno:35, present:true,}
                

    document.write("type of variables", typeof a)
    document.write("<br>type of  variables", typeof b)
    document.write("<br>type of variables", typeof c)
    /* obhect => array,  name:"madan"; null are consider as null */
    document.write("<br>type of variables",typeof marks)
    document.write("<br>type of variables",typeof students)
    document.write("<br>finding index", marks[0], marks[3] )
    document.write("<br>your name", students.name)

   }
</script>
<button class="btn btn-success" type="button" onclick="adding()"  >click data</button>

<--  user defined function-->



<script>
    function sub(x,y){
    document.write("sum of two numbers is",  x+y)
    }
var a,b ,c;
a=25;
b=25;
sub(a,b)
</script>
<script>
    function subb(x,y){
        return x+y;
    }
var a,b,sum;
a=25;
b=35;
sum=subb(a,b)
document.write("adding values",sum)
document.write("add values",subb(a,b))
</script>

<script>
    function add(){
        var a,b;
        a=25;
        b=35;
        return a+b;

    }
    document.write("adding values",add())
</script>

<- conditions -->
<-- 1:- simple if condition --
<script>
function age(){
    if (document.getElementById("t1").value>=16 ) {
         window.alert("Elegiable for vote");
    }

}
</script>

<h1>Enter age here<input type=text id="t1" ></h1>
<button class="btn btn-primary bi bi-check-all" type="button" onclick="age()" >Verify age</button>


<script>
    function aaa(){
        if (document.getElementById("t2").value>=18)
    {
        window.alert("HAVING Perfect details")
    }
    }
</script>
<h1>Enter age here<input type="text" id="t2" > </h1>
<button class="btn btn-success bi bi-check"   type="button" onclick="aaa()" >Verify here</button>

<-- if-else condition  -->




<script>
    function bbb(){
     if (document.getElementById("t3").value<=78)
     {
        document.getElementById("res").innerHTML="Eligible for voting"
     }
     else{
        document.getElementById("res").innerHTML="Not eligible for voting"
     }
     if (document.getElementById("t3").value>=80)
    {
        document.getElementById("res").innerHTML="Old age"
    }
    else {
        document.getElementById("res").innerHTML="perfect age"
    }
    }
</script>
<h1>Enter age here<input type="text" id="t3"</h1>
<button class="btn btn-primary bi bi-check-all" type="button" onclick="bbb()" >Verify age</button>
<div id="res"></div> 



<script>
    function aging(){
    if (document.getElementById("id1").value==document.getElementById("id2").value)
    {
        document.getElementById("id3").innerHTML="Both are equal"
    }
    else if (document.getElementById("id1").value>document.getElementById("id2").value)
     {
        document.getElementById("id3").innerHTML="First number is greater than second number";
    }
    else {
        document.getElementById("id3").innerHTML="Smaller than second number"
    }
    }
 
</script>
<h1>Enter first line<input type="text" id="id1" placeholder="tecxt here" ></h1>
<h1>Enter second line<input type="text" id="id2" placeholder="tecxt here" ></h1>
<button class="btn btn-success" type="button" onclick="aging()" >verify</button>
<div id="id3" ></div>
<center>
<--- SWITCH CASE  -->


 <h1>Multi-Selection</h1>
</center>

<script>
function total(){
    document.getElementById("perc").value=(document.getElementById("om").value/document.getElementById("mm").value)*100
    var percentage=document.getElementById("perc").value;
    var g;
    switch (Math.floor(percentage/10))
    { 
        default : g="ranker";
        break;
        case 9:
        case 8: g="wonderful";
        break;
        case 7: g="verygood";
        break;
        case 6: g="good";
        break;
        case 5: g="average";
        break;
        case 4: g="below average";    
    }
    document.getElementById("grade").value=g;
}
</script>
Maximum marks: <input type="text" id="mm"><br><br>
Obtained marks: <input type="text" id="om"><br><br>
<button class="btn btn-info" type="button" onclick="total()" >Submit</button><br><br>
Percentage: <input type="text" id="perc"><br><br>
Grade: <input type="text" id="grade"><br><br>



<script>
    function mathss(){
    document.getElementById("per").value=(document.getElementById("on").value/document.getElementById("mn").value)*100
    var percentage=document.getElementById("per").value;
   
    var g;
    switch(Math.floor(percentage/10)){
        default: g="common";
        case 9: g="outstanding";
        break;
        case 8: g="very good";
        break;
        case 7: g="good";
        break;
        case 6: g="not bad";
         break;
        case 5: g="poor";
    }
    document.getElementById("gradee").value=g;
    }
</script>

Maximum numbers: <input type="text" id="mn"/><br>
Obtained number: <input type="text" id="on" /><br>
<button type="button" class="btn btn-success " onclick="mathss()" >Submit</button><br>
Percentage: <input type="text" id="per" /><br>
Grade:      <input type="text" id="gradee" /><br>



<center>
maximum number:  <input type="text" id="mad"><br><br>
Obtained number: <input type="text" id="an"><br><br>
<button class="btn btn-success" type="button" onclick="maths()" >Submit</button><br><br>
Percentage:   <input type="text" id="kum"><br><br>
Grade: <input type="text" id="ar"><br><br>

</center>
<script>
    function maths(){
        document.getElementById("kum").value=(document.getElementById("an").value/document.getElementById("mad").value)*100
        var percentage=document.getElementById("kum").value;
        var g;
        switch(Math.floor(percentage/10)){
            case 10 : g="wow";
            break;
            case 9: g="outstanding";
            break;
            case 8: g="very good";
            break;
            case 7: g="good";
            break;
            case 6: g="not bad";
            break;
            case 5: g="bad";

        }
        document.getElementById("ar").value=g;
    }
</script>

<h1>Iterative statements</h1>
1. for loop<br>
2. while loop<br><br>
there are three main things  which are used  in this two  loops:<br><br>

1.initialization<br>
2.Condition<br>
3.updation<br>
<h1>For loop</h1>
<h1 id="ress"></h1>
<script>
    var i; ress="";
    for(i=5;i<=100;i++){
        ress+=i+"";
        if(i%10==0)
        ress+="<br>"
    }
    document.getElementById("ress").innerHTML=ress;
</script>

<h1>for loop</h1>
<h1 id="ree" ></h1>
<script>
 var i=1; ree="";
 for(;i<=100;){
    ree+=i+"";
    if(i%10==0)
    ree+="<br>"
    i++;
 }
 document.getElementById("ree").innerHTML=ree;

</script>

<h1>while loop</h1>
<h1 id="re" ></h1>
<script>
 var i=1; re="";
 while(i<=100){
    re+=i+"";
    if(i%10==0)
    re+="<br>"
    i++;
 }
 document.getElementById("re").innerHTML=re;

</script>
<center>

<h1>numbers conversion in javascript</h1>
<h1 id="mes" ></h1>
<script>
var x=3.14;
var y=20;
var z=5e+3;
var  n=01234567;
var a=10/3;

/*toString(base)*/
var q=15;
 var cv= q.toString(8)
var w="25";
var e="35";
var r=w-e;

var t=25;
var y=25;
var u="25";
var i=y+t+u


var ab=20;
var bc="abc";
var d=ab/bc;
document.getElementById("mes").innerHTML=cv;     
</script>
<br><br> 
<h1>Number object</h1>
<script>
    
var x=15
var y=new Number(15)/* object */
var z=new Number(15)/* object */
    
document.write("Type of x :"+typeof x+"<br>")
document.write("Type of y :"+typeof y+"<br>")
document.write((x==y)+"<br>")/* it gives true*/
document.write((x===y)+"<br>")/* it compares type of data  it gives false */
document.write((y===z)+"<br>")/*we can't compare objects  it gives false   */
    
</script>
<br><br>
<h1>Number Methods</h1>
<script>
var x=15;
var s=x.toString();/* toString */

var x=15;
var E=x.toExponential(2)/* toExponential is secentific number  */

var c=5.45678
var R=c.toFixed(3) /* toFixed three decimals will shown after dot(.) */

var x=2.52564;
var T=x.toPrecision(3)/* toPrecision */

var x=5.45687
Number(x);
var U=x.toPrecision(3)

document.write("Type of x :"+typeof s+"<br>" )
document.write("Exponential Form"+E+"<br>")
document.write("toFixed:"+R+"<br>")
document.write("toPrecision:"+T+"<br>")
document.write("toPrecision:"+U+"<br>")
</script><br><br>


<h1>Number Conersion</h1>
<ol>
    <li>Number()<br>   </li>
    <li>parseInt()<br></li>
    <li>parseFloat()<br></li>
    
</ol>
<script>
    var e=25;
    var s=e.toString();/* toString */
    var a=Number(s);/* Number -- number*/

    var i=25;
    var l=i.toString();/* toString */
    var g=parseInt(l);/* parseInt --- number*/

    var o=3567;
    var k=o.toString();/* toString */
    var j=parseFloat(k);/* parseFloat  -- number */

    document.write("Type of A:"+typeof a+"<br>"+"Value of A:"+a+"<br>" )
    document.write("Type of G:"+typeof g+"<br>"+"Value of G:"+g+"<br>"  )
    document.write("Type of J:"+typeof j+"<br>"+"Value of J:"+j+"<br>" )
</script><br><br>
<h1>Number properties</h1>
<script>
    document.write("MIN_VALUE:"+Number.MIN_VALUE+"<br>")
    document.write("MAX_VALUE:"+Number.MAX_VALUE+"<br>")
    document.write("POSITIVE_INFINITY:"+Number.POSITIVE_INFINITY+"<br>")
    document.write("NEGATIVE INFINITY:"+Number.NEGATIVE_INFINITY+"<br>")
    document.write("NaN Not a NUmber :"+Number.NaN)
</script>
</center><br><br>
<center>
    
    <h1>Strings</h1>
    <ol> <li>string objrct</li>
    <li>String Methods</li></ol><br>
   <script>
    var  s1="Welcome to strings in javascript"+"<br>";
    document.write(s1+"<br>"); /* double quotation string */
    s2='String with single Quote"hai this'
    document.write(s2+"<br>"); /* single quatation string  */
    document.write(typeof s2+"<br>"); /*  string */
    s3 =new String("welcome");
    document.write(s3+"<br>");
    document.write(typeof s3+"<br>")/* it is a string object */
    document.write("<h1>String Methods  </h1>"+"<br>");
    document.write("s1 =",s1,"s2 =",s2 ,"<br>")/* indexOf() */
    document.write("indexOf() s1 = ",s1.indexOf("o")+"<br>");
    document.write("indeOf() s2 =", s2.indexOf("Q"),"<br>");
    document.write("lastIndexOf() s1 =",s1.lastIndexOf("o"),"<br>"); /* lastIndexOf() */
    documnet.write("indexOf() s1 = " ,s1.indexOf())
    document.write("indexOf() s1 = ", s1.indexOf("e",6),"<br>"); /*6 is start index where to find "o" */
 </script>
 <script>
    var s4="hai this madan kumar parchuri";
    document.write("search() s4 =",s4.search("u"),"<br>"); /* search */
    document.write("slice() s4 =",s4.slice(0,9),"<br>") /* slice */
    document.write("slice() with negative index s4=", s4.slice(0,-5),"<br>" ) /* negative slice */
    document.write("substring s4 =", s4.substring(0,17),"<br>")/*substring it not accept negitive index*/
    document.write("substr() s4 =", s4.substr(0,5),"<br>") /* substr  */
    document.write("replace s4 = ", s4.replace("madan kumar parchuri","sohail"),"<br>")/* replace old string and place new string */
    
    var s5="welcome to javascript";
    var s6="WELCOME TO JAVASCRIPT";
    document.write("upperCase() s5 = ", s5.toUpperCase(),"<br>")
    document.write("lowerCase() s6 =",s6.toLowerCase(),"<br>")
    document.write("concat() s5 ==> s6 =  ",s5.concat(s6),"<br>")
    document.write(" ==> length of  s5 = " ,s5.length,"<br>");
    var s7="madan kumar"
    var s8 =s7.trim(); 
    document.write("trim() s8 = ",  s8.length,"<br>"); /* trim */
    document.write("charAt s7 =",s7.charAt("3"),"<br>"); /* charAt to define exact letter */
    document.write("charCodeAt s7 =",s7.charCodeAt("0"),"<br>");
    var s9="25";
    document.write(s8[0]+"<br>");
</script>
</center>
<center>
    <h1>ARRAYS</h1>
    <script>
        document.write("<h1>CREATING</h1>")
        document.write("<h2>")
      var a=[10,20,30,40];
      document.write(a+"<br>");
      document.write(typeof a,"<br>");
      var b=new Array(50,60,70,80);
      document.write(b,"<br>");
      var c=[100];
      document.write(c+"<br>");
      d=new Array(100);
      document.write(d+"<br>");
      document.write("Length of array a is = "+a.length+"<br>");/* array length */ 
      document.write("First element ="+a[0]+"<br>")/* index values */
      document.write("Second Element ="+a[2]+"<br>")/* index value */
      var e={"name":"madan","reg":123, "perc":80};/* named index */
      document.write("named index ="+e.name+"<br>",e.reg+"<br>",e.perc+"<br>");
      var f=[10,20,30,40,50];
      f[2]=250; 
      for(i=0; i<f.length; i++);/*forloop */
      document.write("forloop ="+f+"<br>")
      document.write("f["+i+"]="+f+"<br>")
      var z=[10,20,30,40,50];  /* adding values using arrays */
      z[7]=100;
      document.write("z ="+z+"<br>")
      var x=[10,30,50,70,90,100,] /* deletion  */
      x[1]=''
      document.write("deletion = "+x+"<br>") /* delete and replacing newe number */
      document.write(x.length);
      document.write(Array.isArray(x)); 
        
    </script>
</center>
<br>
<center>
    <h1>Array Methods</h1>
    <script>
   document.write("<h1>")   
    /* join() */  
   var a=[10,20,30,40,50]
   var b=[60,70,80,90,100]
   var c=["madan","kumar","parchuri"]
   document.write(a.join(" ")+"<br>") /* join() */
   document.write(c.join("123")+"<br>")/* join() */
   /* sort() */
   var d=["a","q","w","e","r","t","y","u","i","o","p","a","s","d","f","g","h","j","k","l","z","x","c","v","b","n","m"];
   document.write(d.sort()+"<br>")/* sort() */
   
   /* reverse() */
   var e=["kumar","madan","parchuri"]
   document.write(e.reverse()+"<br>")/*reverse() */
   
   /* pop() */
   var f=[10,20,30,40,50,60,70,80,90,100];
   document.write("f ="+f.pop()+"<br>") /* pop() */
   document.write("f ="+f+"<br>") /* after deleting 100 remainung will shown there */

   /* push() */
   var g=[10,20,30,40,50];
   document.write("g ="+g.push("60")+"<br>")/* push()  insert value in last element */
   document.write("g ="+g+"<br>") /* shown result that is implemented */

   /* unshift */
   var h=[10,15,20,25,30,35]
   document.write("h ="+h.unshift("5")+"<br>");/* unshift() insert value or element in first element */
   document.write("h ="+h+"<br>") /* shown result here that is is implmented */

   /* shift() */
   var i=[10,20,30,40,50];
   document.write("i ="+i.shift()+"<br>"); /* shift() delete first element */
   document.write("i ="+i+"<br>") /* result shown here */

   /* concat()  */
   var j=[10,20,30,40,50,60,70];
   var j2=[80,90,100];
   var j3=[,110,120,130];
   document.write("j = "+j.concat(j2+j3)+",140"+"<br>") /* concat()  merging of two arrays or elements to one array or element  j => j2+j3   140 is element */

   /* splice() */
   var k=[5,20,30,40,50,60];
   document.write("k ="+k.splice(1,3)+"<br>")
   document.write("k ="+k.splice(1,2,"10,25,35")+"<br>")/* splice()  it is used for  deleting and replacing value where the the indexes are deleted  1=index; 2=two index are deleted; "10,15,25,35"= this value is replaced in two indexes as one index   */
   
   document.write("k ="+k+"<br>")/* output here */

  /* slice() */
  var l=[10,20,30,40,50,60,70];
  document.write(" l ="+l+"<br>")
  document.write("l ="+l.slice(1)+"<br>")
  document.write("l ="+l.slice(0,3)+"<br>") /* slice() it starts from where you mentioned  index as start index and also stop index in this it includes start index but it doesn't include stop index */
   </script>
</center>
<br>
<center>
    <h1>Date Object Creation</h1>
    <script>
     document.write("<h1>");
     var d1 = new Date()
     document.write("d1 ="+d1+"<br>")/* first method in date */   
     
     var d2 = new Date(2021,10,13,14,02,05,1000);
     document.write("d2 ="+d2+"<br>")/* Date is constant without chnaging anything */

     var d3 = new Date(2022);
     document.write("d3 ="+d3+"<br>") /* 2022 is millliseconds so it goes to default date  */

     var d4 = new Date(2021 ,0,22,19,45,36,200);
     document.write("d4 ="+d4+"<br>")

     var d5 = new Date("2021 June 22,10:35:25:200");
     document.write("d5 ="+d5+"<br>")
    </script>
</center>
<br>
<center>
    <h1>Get Methods Of Date Object</h1>
    <script>
        document.write("<h1>")
        var d1 = new Date();
        document.write("d1 ="+d1+"<br>")
        document.write("d2 ="+d1.getFullYear()+"<br>")/* getFullYear */
        document.write("d3 ="+d1.getMonth()+"<br>")/* getMonth */
        document.write("d4 ="+d1.getDate()+"<br>")/* getDate */
        document.write("d5 ="+d1.getDay()+"<br>")/* getDay() */
        document.write("d6 ="+d1.getHours()+"<br>") /* getHours() */
        document.write("d7 ="+d1.getMinutes()+"<br>")/* getMinutes() */
        document.write("d8 ="+d1.getSeconds()+"<br>")/* getSeconds() */
        document.write("d9 ="+d1.getMilliseconds()+"<br>")/* getMilliseconds() */
        document.write("d10 ="+d1.getTimezoneOffset()+"<br>")/* getTimezoneoffset() */
        document.write("d11 ="+d1.getUTCDate()+"<br>")/* getUTCDate()  */
        document.write("d12 ="+d1.getTime()+"<br>")/* getTime() */




    </script>
</center>
<br>
<center>
    <h1>Set Methods Of Date Objects</h1>
    <script>
        document.write("<h1>");
        var d2 = new Date();
        document.write("d1 ="+d2+"<br>")
        d2.setDate(28) /* setFullYear */

        document.write("d2 ="+d2+"<br>")
        d2.setFullYear(2022,0)/* setDate */

        document.write("d3 ="+d2+"<br>")
        d2.setMonth(2)/* setMonth */

        document.write("d4 ="+d2+"<br>")
        d2.setHours(22)/* setHours */

        document.write("d5 =<br>"+d2+"<br>")
        d2.setTime(10000000)

    </script>
</center>

<center>
    <h1>Math Object </h1><br>
    <h1>Properties & Methods</h1><br>
    <h1>Properties</h1>
    <script>
    document.write("<h1>")
    document.write(Math.E+"<br>")/* Euler's Number */
    document.write(Math.PI+"<br>")/* PI value */
    document.write(Math.SQRT2+"<br>")/* square root of 2 */
    document.write(Math.SQRT1_2+"<br>")/* square root of  1/2 */
    document.write(Math.LN2+"<br>")/* log2 */
    document.write(Math.LN10+"<br>")/* log10 */
    document.write(Math.LOG2E+"<br>")/* log 2/E */
    document.write(Math.LOG10E+"<br>")/* log 10/E */
    document.write("<h1>Methods</h1>")

    document.write("<h1>")
    document.write("abs(-10) = "+Math.abs(-10)+"<br>")/* abs */ 
    document.write("cbrt(27) ="+Math.cbrt(27)+"<br>")/* cbrt */
    document.write("ceil(3.5)  ="+Math.ceil(3.5)+"<br>")/* ceil */
    document.write("exp(3) ="+Math.exp(3)+"<br>")/* exponential () */
    document.write("floor() ="+Math.floor(3.9)+"<br>")/* floor */
    document.write("log(2) ="+Math.log(2)+"<br>")/* log() */
    document.write("power(8,9) ="+Math.pow(8,9+"<br>")+"<br>")/* power */
    document.write("maximum(1,2,3,4,5,6) ="+Math.max(1,2,3,4,5,6,7,8)+"<br>")/* maximum value */
    document.write("Minimun()"+Math.min(1,2,3,4,5)+"<br>")/* minimum value */
    
    document.write("random() ="+Math.random()+"<br>")/* Random number b/w 0 and 1 */
    
    document.write("rounddown(2.3) ="+Math.round(2.3)+"<br>")/* round down */
    
    document.write(" roundUp(2.6) = "+Math.round(2.6)+"<br>")/* round up */
    
    document.write("sqrt(555) ="+Math.sqrt(555)+"<br>")/* square of x */
    
    document.write(" trunc(6.2564) "+Math.trunc(6.254878)+"<br>")/* return integer part of x */
 
    
    
    
    
    
    
    </script>

</center>
 









 
















<script src="http://code.jquery.com/jquery-latest.js"></script>

 <!---- <script src="js/bootstrap.min.js"></script> -->
<script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body> 
</html>


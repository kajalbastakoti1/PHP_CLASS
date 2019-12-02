# PHP_CLASS Assignment1
Question no:1
<html>
    <head>
    <title>bio</title>
    <link rel="stylesheet" type="text/css" href="bio.css"
           
		   
    </head>
    <body>
       <table border="0px" width="50%" cellspacing="20px" >
           <tr>
               <td>
                   <h1>Me in my Real life</h1>
                       <p>I am Kajal Bastakoti and I am just an average person to say who  is from Nagarkot "NEPAL" loves to read books.
                         I am kind of semi-introvert .I dont know if the word exists but It simply means I need some time alone I was born on 22nd of may 2003 in Nepal.I am  still living in nepal and 
                         I go to my high School "Sifal secondary school" .I am The only child in my family and the most important people inmy life are 
                         my parents .They mean a lot to me They really do.Talking further more about my intrest I love to travel a lot but not with many people 
                         "I mean two peple are fine".Guitar is also my faviorite thing to play except for the barre chords because of my double jointed fingers.The last thing I want to say is I am happy for who I am.
                         
                       </p>
                   </h1>

                   </p></td>
                    

              
               <td> <img src="kajal.jpg" width="200" height="200"></td>
              
           </tr>
           
       </table>

    </body>
</html>
css code

table {
    margin-left:auto;
    margin-right:auto;
    margin-top:50px;
    margin-bottom:20px;
    position: relative;
    border-width:1px;
    border-radius:25px 25px 25px 25px;
    background-color:oldlace}
    
 Question no 2
 
    <html> 
   <head>
         <title > Table</title>
		<link rel="stylesheet" type="text/css" href="stylesphp.css"
    </head>
<body>
   <table cellspacing="0" border="1px">
    <tr bgcolor="#cccccc">
      <th rowspan="2"valign="middle">SN</th>
      <th rowspan="2"valign="middle">Name</th>
      <th colspan="2"> Adress</th>
      <th rowspan="2" bgcolor="#cccccc">Phone</th> 
    </tr>

    <tr bgcolor="#cccccc">
      <td>temporary </td> 
	  <td>permanent</td >
	</tr>
	<tr>
	 <td>1</td>
	 <td>James</td>
	 <td>Singapore</td>
     <td>Holland</td>
	 <td>9823271568</td>
    </tr>
	
	<tr>
	 <td>2</td>
	 <td>Barbara  </td>  
	 <td>Nepal</td>
	 <td>US</td>
	 <td>9751006658</td>
	</tr>
	<tr>
	 <td>3</td>
	 <td>Rebecca  </td>  
	 <td>France</td>
	 <td>Norway</td>
	 <td>9751006658</td>
	</tr>
	<tr>
	 <td>4</td>
	 <td>Bart  </td>  
	 <td>Holland</td>
	 <td>Holland</td>
	 <td>9751006658</td>
	 <tr>
	 <td>5</td>
	 <td>Bille joe </td>  
	 <td>USA</td>
	 <td>USA</td>
	 <td>Unknown </td>
	</tr>
	<tr>
	 <td>6</td>
	 <td>Isabella  </td>  
	 <td>Singapre</td>
	 <td>Taipei </td>
	 <td>9412006658</td>
	</tr>
	<tr>
	 <td colspan="5">Copyright&copy Deerwalk</td>
	 </tr>
</body>	
    </table>

</html>


table {
    margin-left:auto;
    margin-right:auto;
    margin-top:25px;
    margin-bottom:25px;
    position: relative;
    border-width:1px;
    background-color: bisque;
    



}

 th,td{
              border:1px solid black;
              text-align: centre;
              

}
    Question no 3
    
    
    

			
<html>
	<head>
		<title>Registration Form</title>
		<link rel="stylesheet" type="text/css" href="phpstyles.css"
	</head>
	<body>
		<table>
            <tr>
                <td>
                        <form name="registration" method="post" action="index.php">
                                <table border="0 px"  width="50%" align="center">
                                    <tr>
                                        <td>Name : </td>
                                        <td><input type="text" name="name" required></td>
                                    </tr>
                                    <tr>
                                        <td>Age : </td>
                                        <td><input type ="number" name="age" required></td>
                                    </tr>
                                    <tr>
                                        <td>Email : </td>
                                        <td><input type ="email" name = "email" required></td>
                                    </tr>
                                    <tr>
                                        <td>Address : </td>
                                        <td><input type="text" name="address" required></td>
                                    </tr>
                                    <tr>
                                        <td>DOB : </td>
                                        <td><input type = "date" name="dob" required></td>
                                    </tr>
                                    <tr>
                                        <td>Gender : </td>
                                        <td><input type = "radio" value = "male" name="gender" checked> Male <input type = "radio" value = "female" name = "gender"> Female </td>
                                    </tr>
                                    <tr>
                                        <td>Hobbies : </td>
                                        <td>
                                            <input type="checkbox" value = "dancing" name="hobbies" checked> Sports
                                            <input type="checkbox" value = "Programming" name="hobbies"> Programming
                                            <input type = "checkbox" value = "music" name="hobbies" checked> Academics <br>
                                            
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>Country : </td>
                                        <td>
                                            <select name="country">
                                                <option value = "india">India</option>
                                                <option value = "Pakistan">Pakistan</option>
                                                <option value = "Nepal" selected>Nepal</option>
                                                <option value = "Bng">Bangladesh</option>
                                                <option value = "Sri">Srilanka</option>
                                                <option value = "Bhutan">Bhutan</option>
                                                <option value = "Maldives">Maldives</option>
                                              </select>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>Comments: </td>
                                        <td>
                                            <textarea name="comment" rows = "5" cols = "30"></textarea>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td colspan="2" align="center">
                                            <button type="submit">Register</button>
                                            <button type="reset">Clear</button>
                                        </td>
                                    </tr>
                                </table>
                                </form>
                
</html>

table:{
              margin-left:20px;
              margin-right:auto;
              margin-top:25px;
              margin-bottom:25px;
              position: relative;
               border-radius :1px rgb(81, 19, 139);
}
    





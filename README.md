# studentregistration
<!--student registration form-->
<!doctype html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script>
    function validfrom(){
      var fn = document.forms["regform]["fullname"].value;
      var gn = document.forms["regfrom"]["gender"];
       var qa = document.forms["regfrom"]["qualification"];
       var cu = document.forms["regfrom"]["Course"];
       var br = document.forms["regfrom"]["Branch"];
       var sc = document.forms["regfrom"]["Section"];
       var ph = document.forms["regfrom"]["phone number"].value;
       var em = document.forms["regfrom"]["Email"].value;
       var ps = document.forms["regfrom"]["Password"].value;
      }
if(fn==nul||fn=""){
  alert("full name cannot be blank");
  return false;}
else if((gn[0].checked==false)&&(gn[1].checked==false)&&(gn[2].checked==false)){
  alert("enter gender");
  else if((qa[0].checked==false)&&(qa[1].checked==false)&&(qa[2].checked==false)){
  alert("enter qualification");
  return false;}
  else if(Course.selectedIndex==0){
    alert("enter course");
    return false;}
  else if(Branch.selectedIndex==0){
    alert("enter Branch");
    return false;}
else if(ph==null||""){
  alert("enter mobile number");
  return false;}
else if(em ==null||""){
  alert("enter email");
  return false}
else if(ps == null||""){
  alert("enter passwprd");
  return false;}
 </script>
     <style>  
body{  
    background-color: pink;  
}  
.container {  
    padding: 50px;  
  background-color: lightblue;  
}  
  
input[type=text]:focus, input[type=password]:focus {  
  background-color: orange;  
  outline: none;}  

 
</style>  
  
    <tittle>Student Registration Forum</tittle>
  </head>
  <body bgcolor="Lightskyblue">
  <BR>
    <br>
  <body>
    <pre><b>STUDENT Registration Forum</pre></b>
    <form onsubmit = "validform()">
      <label>Enter Your full name</label>
      <br>
      <input type = "text" name = "full name" placeholder = "enter name"/>
        <br>
          <br>
            Gender :  
    </label><br>  
     <input type="radio" name="male"/> Male <br>  
     <input type="radio" name="female"/> Female <br>  
     <input type="radio" name="other"/> Other  
            <br>  
             <br>  
          <label>Qualification</label>
            <br>
            <input type = "radio" name = "Undergraduation"/>Undergraduation<br>
              <input type = "radio" name = "Post graduation"/>Post graduation<br>
          <input type = "radio" name = "Phd"/>PHD<br><br>
              <label>   
Course :  
</label>   
<select>  
<option value="Course">Course</option>  
<option value="BCA">BCA</option>  
<option value="BBA">BBA</option>  
<option value="B.Tech">B.Tech</option>  
<option value="MBA">MBA</option>  
<option value="MCA">MCA</option>  
<option value="M.Tech">M.Tech</option>
  <option value="PHD">PHD</option>
</select>  
              <br>
                <br>
  
          <label>Branch</label>
                  <select>  
     <option value="branch">branch</option>  
     <option value="cse">cse</option>  
     <option value="ece">ece</option>  
    <option value="eee">eee</option>  
    <option value="civil">civil</option>  
   <option value="Mech">Mech</option>  
   <option value="pure sciences">pure sciences</option>
   <option value="PHD">PHD</option>
             </select> 
                  <br>
                    <br>
                      <label>Section</label><BR>
                      <input type = "radio" name = "A"/>A<br>
                      <input type = "radio" name = "B"/>B<br>
                      <input type = "radio" name = "C"/>C<br>
                      <input type = "radio" name = "D"/>D<br>
                      <LABEL>Phone number</phone><br>
                      <input type = "text" name= "phone" size = 10 placeholder = "Mobile number"/><br><br>
                      <LABEL>Email address</phone><br>
                      <input type = "text" name= "EMAIL" placeholder = "Email"/><br><br>
                      <LABEL>Password</phone><br>
                      <input type = "text" name= "password" placeholder = "Password"/><br><br>
                      </div>   
<button type="submit" VALUE="SUBMIT"> SUBMIT </button>  
                      </form>
                      </body>
                      </html>
                      
                      
                      
        
        
       
  

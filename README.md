# studentregistrationform
This is a student registration form made only by using html.
    <html >
    <head> <h2 align="center"><ins>Student Registration Form</ins></h2>
                     <title>Registration Form</title>
       </head>
       <body>
               <p align="center">Fill this form to register !</p>
       <form>
       <table text align="center">
                      <tr>
                      <td>First Name</td>
                      <td ><input type = “text” placeholder = "Enter your first name"> </td>
                      </tr>
        <tr>
        <td >Last Name</td>
        <td><input type = “text” placeholder = "Enter your last name"> </td>
        </tr>
                                  <tr>
                                  <td>Set Username</td>
                                  <td><input type = “text” placeholder = "Set your username   "> </td>
                                  </tr>

                                    <tr>
                                    <td>Date of Birth</td>
                                    <td><input type="date"></td>
                                    </tr>
                                              <tr>
                                              <td>Phone No.</td>
                                              <td><input type="number"></td>
                                              </tr>
                         <tr>
                         <td>E-mail</td>
                         <td><input type="email"></td>
                         </tr>
                   <tr>
                   <td>Password</td>
                   <td><input type="password"></td>
                   </tr>
        <tr>
        <td>Gender</td>
        <td><input type = "radio" name = "Gender">Male
        <input type = "radio" name = "Gender">Female</td>
        </tr>
                        <tr>
                        <td>Department</td>
                        <td><input type = "checkbox">CSE
                        <input type = "checkbox">IT
                        <input type = "checkbox">ECE
                        <input type = "checkbox">CIVIL
                        <input type = "checkbox">MECH</td>
                        </tr>
            <tr>
            <td>Course</td>
            <td> <select name = "course id">
                <option value ="B.Tech">B.Tech</option>
                <option value ="B.Tech">Bca</option>
                <option value ="B.Tech">Bsc</option>
                <option value ="B.Tech">BA</option></td>
                </tr>
     <tr>
     <td>Student Photo</td>
     <td><input type = "file"></td>
     </tr>
                         <tr>
                         <td>City</td>
                         <td> <select name = "city id" placeholder = "Enter your city name   ">
                         <option value ="uttrakhand">Uttarkhand</option>
                         <option value ="uttrakhand">Himachal Pradesh</option>
                         <option value ="uttrakhand">Rajasthan</option>
                         <option value ="uttrakhand">Delhi</option>
                         <option value ="uttrakhand">Kashmir</option></td>
                         </tr>
     <tr>
     <td>Address</td>
     <td><textarea rows="4" cols="50" placeholder="Enter your address here..."></textarea></td>
     </tr>
                <tr>
                <td><input type ="Submit" value="Register"></td>
                </tr>
                         <tr>
                         <td><input type ="reset"></td>
                         </tr>
          </table>
          </form>
          </body>
          </html>

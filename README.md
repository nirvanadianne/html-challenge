# html-challenge
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"/>
    <title>Document</title>
</head>
<body>
    <h1 align="center"> Thank you for joining us for a session at Code Labs Academy</h1>
</body>
    <div class="center">
        <form action="/.forms.html" method="POST" align="center">
            <div>
                <h3> Please mention any topics you would like to ask further questions 
                    or gather more information on.</h3>
                    <textarea name="info" cols="40" rows="5"></textarea>
            </div>
            <div>
                <label for="sessionDate">Session Date:</label>
                <input type="date">
                <label for="subject"> Subject:</label>
                <select id="subject" name="subject">
                    <option value="Other">Other</option>
                    <option value="webDevelopment">Web Development</option>
                    <option value="dataScience">Data Science</option>
                    <option value="cybersecurity">Cybersecurity</option>
                    <option value="uxUi">UX/UI</option>
                </select>
            </div>
           <div>
            <p>Do you study at home?</p>
            <label for="yes"> Yes</label>
            <input type="radio" name="study" value="yes"> 
            <label for="no"> No</label>
            <input type="radio" name="study" value="no" >
           </div>

           <div>
           <p> Why are you seeking more information on these topics?</p>
           <input type="checkbox" id="check1" name="check1" value="check1">
           <label for="check1">I am interested in a more in-depth discussion</label>
            <br>
           <input type="checkbox" id="check2" name="check2" value="check2">
           <label for="check1">I didn't understand it in the session</label>
            <br>
           <input type="checkbox" id="check3" name="check3" value="check3">
           <label for="check1">Phone apps</label>
           </div>

           <div>
            <label for="input1"> on a scale of 1 to 5*, please indicate how informative you felt the session was</label>
            <input type="number" id="rating1" name="rating1" value="rating1" min="1" max="5">
           </div>
           <div>
            <label for="input2"> on a scale of 1 to 5*, please indicate how engaging you felt the session was</label>
            <input type="number" id="rating2" name="rating2" value="rating2" min="1" max="5">
           </div>
            <div>
            <label for="input3"> on a scale of 1 to 5*, please indicate how likely it is you feel that you would recommend the course to a friend</label>
            <input type="number" id="rating3" name="rating3" value="rating3" min="1" max="5">
           </div>

           <div>
            <p> Please use this space to give us any other feedback you may have.</p>
                <textarea name="info" cols="40" rows="5"></textarea>
            </div>
            <div>
            <label for="email"> Email Address:</label>
            <input type="email" id="email" name="email">
            </div>
            
        <input type="submit" value="Submit"/>

            

    
    
           <p></p>
        </form>
    </div>

</html>

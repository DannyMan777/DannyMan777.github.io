<html>
  <head>
    <title>Page Title</title>
    
  </head>
  <body>
      <img src="monopolyIMG.jpg" width="1200"> <br>
      <h2>1.Choose your area of interest:</h2>
    <form>
      <input type="checkbox" id="c1">
      <label for="c1">Art</label><br>
      <input type="checkbox" id="c2">
      <label for="c2">Sports</label><br>
      <input type="checkbox" id="c3">
      <label for="c3">Tech</label>
    </form>    	
      
    <h2>2."name" attribute</h2>
      <form>
        <label for="email"> Enter your email</label>
        <input type="text" name="email" id="email"> <br>
        <label for="email"> Enter your city</label>
        <input type="text" name="city"><br>
        <input type="submit">
      </form>
      
    <h2>3.Drop down lists</h2>
        <select name="color">
         <option value="r">
                 Red</option>
         <option value="g" >
                 Green</option>
         <option value="b" selected>
                 Blue</option>
        </select>
      
    <h2>4. Landing Page Exercise</h2>
          <h2> Order Now! </h2>
    <form>
        <label for="size1"> Size: </label>
        <select name="size" id="size1">
            <option value="small"> Small </option> 
            <option value="medium"> Medium </option>
            <option value="high"> High </option>
        </select>
        <label for="color1"> Color: </label>
        <select name="color" id="color1">
            <option value="r"> Red </option> 
            <option value="g"> Green </option>
            <option value="b"> Blue </option>
        </select>        

        <label for id="box1"> Name </label> <br>
        <input type="textbox" id="box1"> <br>
        <input type="textbox" id="em">   <br>
        <input type="submit">
    </form>
  </body>
</html>
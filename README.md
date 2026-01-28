# TablesandForms.github.io


  <h1>Pizza Ordering Form</h1>
  <br>
<form>
  <body>
    <h2>Contact Information</h2>
    <p>Name: <input type="text"> </p>
    <p>Phone: <input type="text"> </p>
    <p>Email: <input type="text"> </p>
    <br>
    <h2>Select Pizza Size</h2>
    <p>
      <label for="size"> Select Size:</label>
      <select name="size" id="size">
        <option value="Small">Small</option>
        <option value="Medium">Medium</option>
        <option value="Large">Large</option>
        <option value="X-tra Large">X-tra Large</option>
      </select>
    </p>

  <h2>Select Sauce</h2>
  <input type="radio" id="marinara" name="sauce" value="Marinara">
  <label for="marinara">Marinara</label> 
  <input type="radio" id="Ranch" name="sauce" value="Ranch">
  <label for="ranch">Ranch</label>
  <input type="radio" id="No Sauce" name="sauce" value="No Sauce">
  <label for="No Sauce">No Sauce</label>
  
  <h2>Select Toppings</h2>
  <input type="checkbox" id="topping1" name="topping1" value="Pepperoni">
  <label for="topping1"> Pepperoni</label><br>
  <input type="checkbox" id="topping2" name="topping2" value="Sausage">
  <label for="topping2"> Sausage</label><br>
  <input type="checkbox" id="topping3" name="topping3" value="Mushroom">
  <label for="topping3"> Mushroom</label><br>
  <input type="checkbox" id="topping1" name="topping1" value="Pepperoni">
  <label for="topping4"> Pineapple</label><br>
  <input type="checkbox" id="topping5" name="topping5" value="Peppers">
  <label for="topping5"> Peppers</label><br>
  <input type="checkbox" id="topping6" name="topping6" value="Onions">
  <label for="topping6"> Onions</label><br>

  <h2>Addtional Instructions</h2>
  <label for="instructions">
  <input type="text" placeholder="Add instructions">
  <br>
  <input type="submit" value="Submit">
</form>
    
<p>List of My Favorite Video Games</p>
<table>
<tr>
  <th>Title</th>
  <th>Developer</th>
  <th>Year</th>
</tr>
<tr>
  <td rowspan = 3>Bungie
  <td> Halo 1 </td>
  <td> 2001 </td>
</tr>
<tr>
  <td> Halo 2 </td>
  <td> 2004 </td>
</tr>
<tr>
  <td> Halo 3 </td>
  <td> 2007 </td>
</tr>
<tr> 
  <td> Mojang</td>
  <td> Minecraft </td>
  <td> 2011 </td>
</tr>
<tr>
  <td colspan = 3> Count = 4 
</tr>
</table>
</body>

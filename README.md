<html>
  <form>
<p>
<label>Name :
<input type="text" name="customer_name" required>
</label> 
</p>

<p>
<label>Phone : 
<input type="tel" name="phone_number">
</label>
</p>

<p>
<label>Email :
<input type="email" name="email_address">
</label>
</p>

<fieldset>
<legend>Which taxi do you require?</legend>
<p><label> <input type="radio" name="taxi" required value="car"> Car </label></p>
<p><label> <input type="radio" name="taxi" required value="van"> Van </label></p>
<p><label> <input type="radio" name="taxi" required value="tuktuk"> Tuk Tuk </label></p>
</fieldset>

<fieldset>
<legend>Extras</legend>
<p><label> <input type="checkbox" name="extras" value="baby"> Baby Seat </label></p>
<p><label> <input type="checkbox" name="extras" value="wheelchair"> Wheelchair Access </label></p>
<p><label> <input type="checkbox" name="extras" value="tip"> Stock Tip </label></p>
</fieldset>


<p>
<label>Pickup Date/Time
<input type="datetime-local" name="pickup_time" required>
</label>
</p>
	
<p>
<label>Pickup Place
<select id="pickup_place" name="pickup_place">
<option value="" selected="selected">Select One</option>
<option value="office" >Taxi Office</option>
<option value="town_hall" >Town Hall</option>
<option value="telepathy" >We'll Guess!</option>
</select>
</label> 
</p>


<p>
<label>Dropoff Place
<input type="text" name="dropoff_place" required list="destinations">
</label>

<datalist id="destinations">
<option value="Airport">
<option value="Beach">
<option value="Fred Flinstone's House">
</datalist>
</p>
<div class="navbar">
  <a href="#home">Home</a>
  <a href="#news">News</a>
  <div class="dropdown">
    <button class="dropbtn">Dropdown
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
    </div>
  </div>
</div>


<p><button>Submit Booking</button></p>


</form>
</html>

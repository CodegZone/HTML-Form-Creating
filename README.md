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
</form>
</html>

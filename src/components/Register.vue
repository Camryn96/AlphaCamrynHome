<template>
	<div class="RegisterComp">
		<form action="action_page.php" method="post">
  <div class="imgcontainer">
    <h1>REGISTER </h1>
  </div>

  <div class="container">
    <label for="uname"><b>Name:</b></label>
    <input type="text" placeholder="Enter name" name="name" required>

    <label for="uname"><b>Surname:</b></label>
    <input type="text" placeholder="Enter Surname" name="Surname" required>

    <label for="uname"><b>UserName:</b></label>
    <input type="text" placeholder="Enter Unique Username" name="username" required>


    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <label for="psw"><b>Re-Enter Password</b></label>
    <input type="password" placeholder="Re-Enter Password" name="Re-psw" required>

    <button type="submit">Register</button>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</form>


	</div>

	
</template>
<script>

export default{
	// eslint-disable-next-line vue/multi-word-component-names
	name:'RegisterComp'
};


</script>
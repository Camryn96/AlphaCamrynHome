<template>
	<div class="AddProduct">
		<h1>ADD PRODUCT</h1>
			<table>
 <tr> 
    <th></th>
    <th>Name:</th>
    <th>Price</th>
    <th>ESRB Rating</th>
  </tr>
  <tr>
    <th>Playstation</th>
    <td>God Of War</td>
    <td>1000</td>
    <td>18+</td>
  </tr>
  <tr> 
    <th>Xbox</th>
    <td>Halo: Infinite</td>
    <td>899</td>
    <td>18+</td>
 </tr>
 <tr> 
    <th>PC</th>
    <td>Company of heroes 3</td>
    <td>500</td>
    <td>16+</td>
 </tr>
 <tr> 
    <th>Nintendo</th>
    <td>Pokemon Legends</td>
    <td>250</td>
    <td>3+</td>
 </tr>
</table>

</div>
<button type="submit">Add Product</button>
<button type="submit">Delete Product</button>
</template>
<script>

export default{
	// eslint-disable-next-line vue/multi-word-component-names
	name:'AddProduct'
};

</script>
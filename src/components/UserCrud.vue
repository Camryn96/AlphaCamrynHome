<template>
	<div class="UserCrud m-auto justify-content-center">
		<h1>USER CRUD</h1>
		<table class="table table-bordered  text-white">
        <thead>
          <tr>
            <th class="fw-bold" scope="col">NO.</th>
            <th class="fw-bold" scope="col">User_id</th>
            <th class="fw-bold" scope="col">FirstName</th>
            <th class="fw-bold" scope="col">LastName</th>
            <th class="fw-bold" scope="col">Gender</th>
            <th class="fw-bold" scope="col">CellPhoneNumber</th>
            <th class="fw-bold" scope="col">EmailAdd</th>
            <th class="fw-bold" scope="col">User_Password</th>
            <th class="fw-bold" scope="col">UserRole</th>
            <th class="fw-bold" scope="col">UserProfile</th>
            <th class="fw-bold" scope="col">JoinDate</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>test</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>
        </tbody>
    </table>
		
	</div>
</template>
<script>
export default{
	// eslint-disable-next-line vue/multi-word-component-names
	name: 'UserCrud'
};
</script>
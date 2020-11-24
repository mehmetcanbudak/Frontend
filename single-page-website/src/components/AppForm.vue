<template lang="html">
<div class="">
	<div class="field is-horizontal">
		<div class="field-body">
			<div class="field">
				<label class="label">First Name</label>
				<p class="control is-expanded has-icons-left">
					<input class="input" type="text" placeholder="First name">
					<span class="icon is-small is-left">
						<i class="fas fa-user"></i>
					</span>
				</p>
			</div>
			<div class="field">
				<label class="label">Last Name</label>
				<p class="control is-expanded has-icons-left">
					<input class="input" type="text" placeholder="Last name">
					<span class="icon is-small is-left">
						<i class="fas fa-user"></i>
					</span>
				</p>
			</div>
		</div>
	</div>

	<div class="field">
		<label class="label">Email</label>
		<div class="control has-icons-left has-icons-right">
			<input class="input" type="email" placeholder="Email input" value="hello@">
			<span class="icon is-small is-left">
				<i class="fas fa-envelope"></i>
			</span>	
		</div>
	</div>   
</div> 

<div class="field">
	<label class="label">Message</label>
	<div class="control">
		<textarea class="textarea" placeholder="Textarea"></textarea>
	</div>
</div>



	<div class="field">
		<div class="control">
				<label class="checkbox">
					<input type="checkbox">
				I agree to the <a href="#">terms and conditions</a>
				</label>
		</div>
	</div>   

	<div class="field is-grouped">
		<div class="control">
				<button class="button is-link">Submit</button>
		</div>
	</div>   

</template>
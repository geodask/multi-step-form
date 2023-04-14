<h2 class="text-primary">Text Inputs</h2>

<div class="form-control">
	<label for="name" class="label">Name</label>
	<input class="input" id="name" />
</div>

<div class="form-control">
	<label class="label" for="email">
		<span>Email</span>
		<span class="label-text-alt text-error">This field is required</span>
	</label>
	<input class="input input-error" id="email" />
</div>

<h2 class="text-primary">Checkboxes</h2>
<label for="checkbox-1" class="label cursor-pointer">
	<input type="checkbox" class="checkbox" id="checkbox-1" />
	<span>Checkbox 1</span>
</label>

<label for="checkbox-2" class="label cursor-pointer">
	<input type="checkbox" class="checkbox checkbox-secondary" id="checkbox-2" />
	<span class="text-secondary">Checkbox 2</span>
</label>

<label for="checkbox-3" class="label cursor-pointer">
	<input type="checkbox" class="checkbox checkbox-error" id="checkbox-3" />
	<span class="text-error">Checkbox 3</span>
</label>

<h2 class="text-primary">Toggles</h2>
<input type="checkbox" class="toggle" id="toggle" />

<h2 class="text-primary">Buttons</h2>

<button class="btn">Next Step</button>
<button class="btn btn-ghost">Go back</button>

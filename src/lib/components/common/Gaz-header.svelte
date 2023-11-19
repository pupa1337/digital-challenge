<div class="nav-bar container mx-auto flex items-center justify-between">
	<a class="imga" href="/"><img src="\logo.svg" width="143" alt="" /></a>
	<!-- svelte-ignore a11y-click-events-have-key-events -->
	<!-- svelte-ignore a11y-no-static-element-interactions -->
	<div class="login">
		<a class="no-underline" href="/panel"
			><img src="mods.svg" width="28" alt="" />
			<div>Панель модерации</div>
		</a>
	</div>
	<div class="login">
		<a class="no-underline" href="/loadPhoto"
			><img src="upload.svg" width="28" alt="" />
			<div>Загрузка фотографии</div>
		</a>
	</div>
	<div class="login">
		<a class="no-underline" href="/login"
			><img src="user.svg" width="28" alt="" />
			<div>Личный кабинет</div>
		</a>
	</div>
</div>

<style>
	.no-underline {
		text-decoration: none;
		color: black;
		display: flex;
		flex-direction: row;
		gap: 10px;
	}
	.login {
		gap: 10px;
		background: #56b2fd;
		text-decoration: none;
		border-radius: 15px;
		padding: 15px;
	}
</style>

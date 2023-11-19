<script>
	// function myFunction() {
	// 	let x = document.querySelectorAll('#myInput');
	// 	if (x[0].type === 'password') {
	// 		x[0].type = 'text';
	// 		x[1].type = 'text';
	// 	} else {
	// 		x[0].type = 'password';
	// 		x[1].type = 'password';
	// 	}
	// }
	function myFunction() {
		let x = document.getElementById('myInput');
		if (x.type === 'password') {
			x.type = 'text';
		} else {
			x.type = 'password';
		}
	}
</script>

<div class="class">
	<div class="gaz">
		<a href="/"><img class="img" src="logo.svg" alt="" /></a>
		<div class="prom">
			<h1 class="colorlog">Регистрация</h1>
			<input class="input" type="text" placeholder="Имя Пользователя" />
			<input class="input" type="password" placeholder="Введите Пароль" id="myInput" />
			<input class="input" id="myInput" type="password" placeholder="Подтвердите Пароль" />
			<span class="check-pass">
				<input class="check-pass" type="checkbox" on:change={myFunction} />
				Показать пароль
			</span>
			<button class="button"> <a href="/">Зарегистрироваться</a> </button>
		</div>
	</div>
</div>

<style>
	:global(body, html) {
		margin: 0;
		padding: 0;
	}
	.colorlog {
		color: black;
		font-size: 35px;
	}
	.class {
		display: flex;
		justify-content: center;
		background: url('bg.jpg') no-repeat;
		background-size: cover;
		padding: 0;
		margin: 0;
		height: 100%;
		width: 100%;
		min-height: 100vh;
		overflow-y: hidden;
	}

	.gaz {
		width: 300px;
	}

	.prom {
		display: flex;
		flex-direction: column;
		gap: 20px;
		padding: 20px;
		flex-grow: 1;
		align-items: center;
		border-radius: 10px;
		margin-top: 80px;
	}

	.input {
		border: none;
		padding: 20px;
		border-radius: 10px;
	}
	.button {
		margin-top: 10px;
		width: 240px;
		height: 40px;
		border-radius: 10px;
		font-size: 20px;
		background: linear-gradient(167.52deg, #ffa600 43.04%, #f70 99.03%);
	}
	.img {
		height: 150px;
		padding-left: 30px;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.check-pass {
		color: #000000;
	}
</style>

<div class="bg">
	<a href="/" class="logo"><img class="img" src="logo.svg" alt="" /></a>
	<img src={localStorage.getItem('photo')} alt="" class="photo" />
	<div class="isVerified">Прошла ли эта картинка модерацию?</div>
	<div class="verifying">
		<a href="/"><div class="button">Да</div></a>
		<a href="/"><div class="button">Нет</div></a>
	</div>
</div>

<style>
	.bg {
		background: url('bg.jpg') no-repeat;
		background-size: cover;
		padding: 0;
		margin: 0;
		height: 100%;
		width: 100%;
		min-height: 100.05vh;
		overflow-y: hidden;
	}
	.img {
		height: 150px;
		padding-left: 30px;
		display: flex;
		justify-content: center;
		align-items: center;
		width: max-content;
	}
	.logo {
		display: flex;
		justify-content: center;
		width: 250px;
		margin: 0 auto;
	}
	.photo {
		position: relative;
		max-width: 550px;
		margin: 0 auto;
	}
	.isVerified {
		margin: 0 auto;
		width: max-content;
	}
	.verifying {
		display: flex;
		flex-direction: row;
		justify-content: center;
		gap: 40px;
	}
	.button {
		margin-top: 10px;
		width: 240px;
		height: 40px;
		border-radius: 10px;
		font-size: 20px;
		background: linear-gradient(167.52deg, #ffa600 43.04%, #f70 99.03%);
		text-align: center;
	}
</style>

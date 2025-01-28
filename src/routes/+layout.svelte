<script>
	let { children } = $props();
</script>

<div class="content">
	{@render children()}
</div>

<nav class="bottom-nav">
	<div class="nav-links">
		<a href="/">1º</a>
		<a href="/Pagina2">2º</a>
		<a href="/Pagina3">3º</a>
	</div>
</nav>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	body {
		font-family: 'Arial', sans-serif;
		background-color: #f4f7f6; /* Cor de fundo suave */
		color: #333;
		line-height: 1.6;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		padding: 20px;
	}

	.content {
		flex-grow: 1; /* Garante que a área de conteúdo ocupe o espaço restante */
		padding: 20px;
		max-width: 1000px;
		margin: 0 auto;
		min-height: 80vh; /* Ajusta para garantir espaço suficiente para o conteúdo */
		background-color: #ffffff;
		box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
		border-radius: 10px;
	}

	nav.bottom-nav {
		display: flex;
		justify-content: center;
		width: 100%;
		padding: 10px;
		position: fixed; /* Fixa a navegação na parte inferior da página */
		bottom: 0; /* Coloca a barra na parte inferior */
		left: 50%;
		transform: translateX(-50%); /* Centraliza a barra horizontalmente */
		background-color: transparent; /* Fundo invisível */
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Sombra suave para a navegação */
		z-index: 100; /* Garante que a barra fique acima do conteúdo */
	}

	.nav-links {
		display: flex;
	}

	.nav-links a {
		color: #555;
		text-decoration: none;
		padding: 10px 20px;
		margin: 0 10px;
		font-size: 20px;
		font-weight: 500;
		border-radius: 8px;
		background-color: #fff;
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Caixa discreta em volta do número */
		transition: all 0.3s ease;
	}

	.nav-links a:hover {
		background-color: #e2e2e2;
		color: #333;
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Efeito ao passar o mouse */
		transform: translateY(-2px);
	}

	@media (max-width: 768px) {
		.nav-links a {
			font-size: 18px;
			padding: 8px 16px;
		}
	}
</style>

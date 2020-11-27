<svelte:head>
	<title>Página Inicial</title>
</svelte:head>

<main>
	<section class="container jumbotron">
		<div class="row px-3">
			<h2 class="text-uppercase text-center"> 
				<span><u>Mais de 200 alunos</u></span> aprenderam com esse método. Inscreva-se agora para ter acesso ao nosso <span><u>conteúdo EXCLUSIVO!</u></span>
			</h2>
		</div>
		<div class="row">
			<span class="d-block mx-auto"><img src="img/seta.png" alt="abaixo" class="seta"></span>
		</div>
		<div class="row px-5">
			<div class="col-12">
				<form id="contact_form" action="https://gmail.us20.list-manage.com/subscribe/post" method="POST">
				<input type="hidden" name="u" value="f68678d6fb924634ec807a4f8">
				<input type="hidden" name="id" value="e96f8706ca">
				<input class="form-control" type="email" name="MERGE0" value="" placeholder="Informe seu e-mail...*" required>
				<button type="submit" value="Enviar" class="btn my-3"><h3 class="text-uppercase py-2">Quero me cadastrar agora!</h3></button>
			</form>
			</div>
		</div>
	</section>
</main>
<main class="bg-white">
	<section class="container jumbotron mb-0">
		<div class="row">
			<div class="col-lg-4 col-md-4">
				<img src="img/a1.png" alt="Passos" class="d-block mx-auto">
				<h4 class="text-center py-3 d-block mx-auto">1. Passo a Passo</h4>
				<p class="text px-3">Tudo que você precisa saber para realizar uma massagem completa usando as técnicas de Quick Massage e oferecer saúde e bem estar.</p>
			</div>
			<div class="col-lg-4 col-md-4">
				<img src="img/a2.png" alt="Clientes" class="d-block mx-auto">
				<h4 class="text-center py-3 d-block mx-auto">2. Capture Clientes</h4>
				<p class="text px-3">Use o mesmo processo que nós usamos para oferecer massagem a milhares de clientes particulares e empresariais.</p>

			</div>
			<div class="col-lg-4 col-md-4">
				<img src="img/a3.png" alt="Técnica" class="d-block mx-auto">
				<h4 class="text-center py-3 d-block mx-auto">3. Técnica Milenar</h4>
				<p class="text px-3">Seja um encantador de pessoas, com uso das técnicas oferecidas nesse guia, aprenda a arte milenar da massagem.</p>
			</div>
		</div>
	</section>
</main>

<main class="bg-white">
	<section class="container jumbotron mb-0">
		<div class="row justify-content-center">
			<div class="col-10 col-md-8">
				<img src="img/ari1.png" alt="Ari Freire" class="d-block mx-auto rounded-circle py-2">
				<h4 class="text-center py-3 d-block mx-auto">Ari Freite</h4>
				<p class="text">Educador físico com especialização em fisiologia humana, palestrante e treinador comportamental. Professor das cadeiras de anatomia, fisiologia, ergonomia, qualidade de vida no trabalho e políticas públicas de saúde. Criador do método Kuài, vem formando e capacitando profissionais em massoterapia desde 2012. Professor na área de saúde há 21 anos, desenvolveu um método prático e avançado de ensino, unindo as neurociências e a técnica em massoterapia.</p>
			</div>
		</div>
	</section>
</main>

<style>
	h2{
		font-size: 3rem;
		color: white;
	}
	h3{
		font-size: 1.5rem; 
	}
	span{
		color: #00f0e8;
	}
	button{
		width: 80%;
		display: block;
		margin: 0.5rem auto;
		background-color: #01a7a1;
		border: 2px solid #c4fffd;
		color: white;
		border-radius: 10px;
		transition: all 800ms;
	}
	button:hover{
		background-color: #00df30;
		border: 2px solid #1aed47;
		color: white;
		transition: all 1200;
		text-decoration: none;
	}
	button:focus{
		 text-decoration: none;
	}
	input{
		width: 80%;
		display: block;
		margin: 0.5rem auto;
		border-radius: 5px;
	}
	.seta{
		max-height: 30vh;
	}

	.text{
		text-align: justify;
	}

	@media (max-width: 575.98px) { 
		h2{
			font-size: 1.5rem;
		}
		.seta{
			max-height: 10vh;
		}
		button{
			width: 100%;
		}
		input{
			width: 100%;
		}
		h3{
			font-size: .8rem;
		}
	}
	@media (max-width: 768px) { 
		h2{
			font-size: 2rem;
		}	
		.seta{
			max-height: 10vh;
		}
		button{
			width: 100%;
		}
		input{
			width: 100%;
		}

	}

</style>
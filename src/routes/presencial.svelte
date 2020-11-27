<script>
let dispMovel = '';
let linkwpp = '';

function link(){	
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
	linkwpp = 'https://wa.me/5581996765808?text=Olá!+Gostaria+de+saber+se+ainda+restam+vagas+para+o+Método+Kuài+Presencial!';
	window.open(linkwpp, "_blank");
}
else{
	linkwpp = 'https://web.whatsapp.com/send?phone=5581996765808&text=Ol%C3%A1%21+Gostaria+de+saber+se+ainda+restam+vagas+para+o+M%C3%A9todo+Ku%C3%A0i+Presencial%21&source&data&app_absent';
	window.open(linkwpp, "_blank");
	}

}
</script>

<svelte:head>
	<title>Presencial</title>
</svelte:head>

<main class="bg-white">
	<section class="container jumbotron mb-0">
		<div class="row">
			<div class="col-12 text-center pb-5">
				<h2>Kuài Presencial</h2>
			</div>
			<div class="col-12 overflow-hidden">
				<iframe title="Youtube" class="d-block mx-auto" src="https://www.youtube.com/embed/ZWnNSBSextQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
			</div>
			<div class="col-md-9 col-sm-12 col-12 py-3 px-3 mx-auto">
			 	<h3 class="text-center py-4">Método avançado em massagem Kuài</h3>
					<ul>
						<li>Seja uma massagista do absoluto zero e sem equipamento algum.</li>
						<li>Os macro e micro movimentos que lhe permitirão aplicar massagens relaxantes ou terapêuticas com o cliente deitado ou na cadeira.</li>
						<li>Aplique as técnicas de venda Kuài para lotar sua agenda de clientes em 30 dias.</li>
						<li>Feche contrato com empresas públicas e privadas com massoterapia laboral.</li>
					</ul>
					<h5 class="text-center pt-3">Tudo isso certificado pelo método Kuài.</h5>
			</div>
			<div class="col-lg-6 col-md-8 col-sm-10 col-10 mx-auto">
			<button type="submit" class="my-3 d-block w-100 mx-auto" on:click={link}><i class="fa fa-2x fa-whatsapp"></i><h5 class="text-uppercase text-decoration-none">Vagas Limitadas!</h5></button>
			</div>
		</div>
	</section>
</main>

<style>
	h2{
		font-size: 3rem;
	}
	h3{
		font-size: 2rem;
	}
	iframe{
		width: 80%;
		height: 500px;
		border-radius: 20px;
	}

	@media (max-width: 575.98px) { 
		h2{
			font-size: 5vh;
		}
		iframe{
		width: 100%;
		border-radius: 20px;
		}
	}
	@media (max-width: 768px) { 
		iframe{
		height: 30vh;
		border-radius: 20px;
		}
	}
	button{
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
	}

</style>
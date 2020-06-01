<script>
	import Comments from './Comments.svelte';
</script>

<div class="Card">
	<div class="Card-container">
		<div class="Card-header">
			<div class="Card-user">
				<img src="https://ismaeldevloop.com/assets/img/team-black.jpg" alt="">
				<h2>
					Elmo.pug
					<span>Chalco, México</span>
				</h2>
			</div>
		</div>
		<div class="Card-settings">
			<i class="fas fas-ellipsis-h"/>
		</div>
		<div class="Card-photo">
			<figure>
				<img src="https://ismaeldevloop.com/assets/img/team-black.jpg" alt="">
			</figure>
		</div>
		<div class="Card-icons">
			<div class="Card-icons-first">
				<i class="fas fa-heart"/>
				<i class="fas fa-paper-plane"/>
			</div>
		</div>
		<div class="Card-icons-second">
			<i class="fas fa-bookmark"/>
		</div>
		<div class="Card-description">
			<h3>Elmo.pug</h3>
			<span>¡Hola!</span>
		</div>
		<Comments />
	</div>
</div>
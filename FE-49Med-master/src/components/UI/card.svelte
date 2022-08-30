<script>
	export let image = '',
		title = '',
		text = '';
</script>
    
    <div class="card">
        <img class="card__img" src={image} alt="">
        <h5 class="card__title">{title}</h5>
        <p class="card__text">{text}</p>

    </div>

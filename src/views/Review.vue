<template>
	<div>
		<div class="container">	
			<div class="review-wrap">
				<div class="review-card">
					<div class="review-card__header">
						<div class="review-card__img">
							
						</div>
						<div class="review-card__employee">
							<div class="review-card__employee-name">Cruce De Gusto</div>
							<div class="review-card__employee-rating">
								<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
								<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
								<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
								<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
								<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
							</div>
						</div>
					</div>
					<div class="review-card__content">
						<div class="review-card__heading">Загальне враження*</div>
						<div class="review-card__stars">							
						    <input type="radio" id="rating-4" name="rating" value="4" checked="checked" /><label for="rating-4"><svg class="star-ico" viewBox="0 0 576 512" xmlns="http://www.w3.org/2000/svg">
									<path _ngcontent-c16="" d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"></path>
								</svg>
								<div>Жахливо</div></label>
						    <input type="radio" id="rating-3" name="rating" value="3" /><label for="rating-3"><svg class="star-ico" viewBox="0 0 576 512" xmlns="http://www.w3.org/2000/svg">
									<path _ngcontent-c16="" d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"></path>
								</svg>
								<div>Погано</div></label>
						    <input type="radio" id="rating-2" name="rating" value="2" /><label for="rating-2"><svg class="star-ico" viewBox="0 0 576 512" xmlns="http://www.w3.org/2000/svg">
									<path _ngcontent-c16="" d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"></path>
								</svg>
								<div>Добре</div></label>
						    <input type="radio" id="rating-1" name="rating" value="1" /><label for="rating-1"><svg class="star-ico" viewBox="0 0 576 512" xmlns="http://www.w3.org/2000/svg">
									<path _ngcontent-c16="" d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"></path>
								</svg>
								<div>Відмінно</div></label>
						    <input type="radio" id="rating-0" name="rating" value="0" class="star-cb-clear" /><label for="rating-0">0</label>
						</div>
						<div class="review-card__comment">
							<textarea cols="30" rows="10" placeholder="Додати коментар"></textarea>
						</div>
						<div class="review-card__buttons">
							<button class="review-card__button"><svg width="24" height="24" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd"><path d="M16 24h-8v-1h3.5v-3.018c-3.63-.256-6.5-3.287-6.5-6.982v-2h1v2.01c.005 3.307 2.692 5.99 6 5.99 3.311 0 6-2.689 6-6v-2h1v2c0 3.695-2.87 6.726-6.5 6.982v3.018h3.5v1zm-9-19c0-2.76 2.24-5 5-5s5 2.24 5 5v8c0 2.76-2.24 5-5 5s-5-2.24-5-5v-8zm9 0c0-2.208-1.792-4-4-4s-4 1.792-4 4v8c0 2.208 1.792 4 4 4s4-1.792 4-4v-8z"/></svg>Записати аудіо</button>
							<button class="review-card__button"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M5 4h-3v-1h3v1zm8 6c-1.654 0-3 1.346-3 3s1.346 3 3 3 3-1.346 3-3-1.346-3-3-3zm11-5v17h-24v-17h5.93c.669 0 1.293-.334 1.664-.891l1.406-2.109h8l1.406 2.109c.371.557.995.891 1.664.891h3.93zm-19 4c0-.552-.447-1-1-1s-1 .448-1 1 .447 1 1 1 1-.448 1-1zm13 4c0-2.761-2.239-5-5-5s-5 2.239-5 5 2.239 5 5 5 5-2.239 5-5z"/></svg>Фото або відео</button>
						</div>
					</div>
				</div>
				<div class="review-socials">
					<a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm3 8h-1.35c-.538 0-.65.221-.65.778v1.222h2l-.209 2h-1.791v7h-3v-7h-2v-2h2v-2.308c0-1.769.931-2.692 3.029-2.692h1.971v3z"/></svg></a>
					<a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M14.829 6.302c-.738-.034-.96-.04-2.829-.04s-2.09.007-2.828.04c-1.899.087-2.783.986-2.87 2.87-.033.738-.041.959-.041 2.828s.008 2.09.041 2.829c.087 1.879.967 2.783 2.87 2.87.737.033.959.041 2.828.041 1.87 0 2.091-.007 2.829-.041 1.899-.086 2.782-.988 2.87-2.87.033-.738.04-.96.04-2.829s-.007-2.09-.04-2.828c-.088-1.883-.973-2.783-2.87-2.87zm-2.829 9.293c-1.985 0-3.595-1.609-3.595-3.595 0-1.985 1.61-3.594 3.595-3.594s3.595 1.609 3.595 3.594c0 1.985-1.61 3.595-3.595 3.595zm3.737-6.491c-.464 0-.84-.376-.84-.84 0-.464.376-.84.84-.84.464 0 .84.376.84.84 0 .463-.376.84-.84.84zm-1.404 2.896c0 1.289-1.045 2.333-2.333 2.333s-2.333-1.044-2.333-2.333c0-1.289 1.045-2.333 2.333-2.333s2.333 1.044 2.333 2.333zm-2.333-12c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.958 14.886c-.115 2.545-1.532 3.955-4.071 4.072-.747.034-.986.042-2.887.042s-2.139-.008-2.886-.042c-2.544-.117-3.955-1.529-4.072-4.072-.034-.746-.042-.985-.042-2.886 0-1.901.008-2.139.042-2.886.117-2.544 1.529-3.955 4.072-4.071.747-.035.985-.043 2.886-.043s2.14.008 2.887.043c2.545.117 3.957 1.532 4.071 4.071.034.747.042.985.042 2.886 0 1.901-.008 2.14-.042 2.886z"/></svg></a>
					<a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.066 9.645c.183 4.04-2.83 8.544-8.164 8.544-1.622 0-3.131-.476-4.402-1.291 1.524.18 3.045-.244 4.252-1.189-1.256-.023-2.317-.854-2.684-1.995.451.086.895.061 1.298-.049-1.381-.278-2.335-1.522-2.304-2.853.388.215.83.344 1.301.359-1.279-.855-1.641-2.544-.889-3.835 1.416 1.738 3.533 2.881 5.92 3.001-.419-1.796.944-3.527 2.799-3.527.825 0 1.572.349 2.096.907.654-.128 1.27-.368 1.824-.697-.215.671-.67 1.233-1.263 1.589.581-.07 1.135-.224 1.649-.453-.384.578-.87 1.084-1.433 1.489z"/></svg></a>
				</div>
				<div class="review-submit">
					<button class="review-card__button">Відправити</button>
				</div>
			</div>
		</div>	
	</div>	
</template>

<script>
	export default {

	}
</script>

<style lang="sass" scoped>
	.container
		max-width: 450px
		margin: 0 auto
		padding: 0 15px

	.review-wrap
		margin: 50px 0

	.review-card
		border-radius: 10px
		box-shadow: 0 0 11px 0 rgba(#000, .16 )
		padding: 20px
		&__header
			margin-bottom: 25px
			display: flex
			align-items: center

		&__img
			width: 5rem
			height: 5rem
			border-radius: 50%
			background: #ccc
			box-shadow: 0 0 3px 0 rgba(#000, .16 )

		&__list
			padding: 0
			margin: 0
			list-style: none
			display: flex
			&-item
				flex-basis: 25%
				flex-grow: 1
				text-align: center
				font-size: 12px
				svg
					width: 56px
					height: 54px
				label > div
					line-height: 1


		&__heading
			text-align: center
			font-size: 24px
			margin-bottom: 15px

		&__employee
			margin-left: 20px
			&-name
				font-size: 16px
			&-rating
				display: flex
				align-items: center
				svg
					& + svg
						margin-left: 5px

		&__stars
			margin-bottom: 25px
			unicode-bidi: bidi-override
			direction: rtl
			display: flex
			justify-content: space-between
			.star-cb-clear
				position: absolute
			& > input
				display: none
				& + label
					display: inline-block
					overflow: hidden
					// text-indent: 9999px
					// width: 1em
					white-space: nowrap
					cursor: pointer
					text-align: center
					svg
						display: inline-block
						text-indent: -9999px
						width: 56px
						height: 54px
						fill: #ccc
					div
						line-height: 1

				&:checked ~ label svg,
				& + label:hover ~ label svg,
				& + label:hover svg
					fill: #000

			& > .star-cb-clear + label
				text-indent: -9999px
				width: .5em
				margin-left: -.5em
				position: absolute

			& > .star-cb-clear + label:before
				width: .5em


			&:hover > input + label svg
				fill: #ccc

			&:hover > input + label:hover ~ label svg,
			&:hover > input + label:hover svg
				fill: #000


		&__comment
			line-height: 1
			margin-bottom: 15px
			textarea
				padding: 15px 5px 5px 15px !important
				font-family: inherit
				border-radius: 10px
				height: 150px

		&__buttons
			line-height: 1
			display: flex
			align-items: center
			justify-content: space-between

		&__button
			flex: 0 0 calc(50% - 10px)
			display: block
			padding: 0
			border: 0
			background: 0
			cursor: pointer
			border-radius: 5px
			border: 1px solid #000
			height: 40px
			display: flex
			align-items: center
			justify-content: center
			&:hover
				background: #000
				color: #fff
			svg
				width: auto
				height: auto
				margin-right: 5px

	.review-socials
		display: flex
		justify-content: center
		align-items: center
		margin-top: 40px
		a
			color: #000
			font-size: 20px
			& + a
				margin-left: 15px

			svg
				width: 30px
				height: 30px

	.review-submit
		margin-top: 30px
		.review-card__button
			height: 60px
			flex: 0 0 100%
			width: 100%
			font-size: 16px
			background: #000
			color: #fff
			&:hover
				background: transparent
				color: #000



</style>
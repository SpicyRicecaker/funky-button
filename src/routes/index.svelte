<script lang="ts">
	const shuffle = () => {};
</script>

<!-- Button in the center of the page -->
<div id="button_wrapper">
	<button id="button">Funky Banana</button>
</div>

<style lang="scss">
	:global(body) {
		background-color: black;
	}
    #button_wrapper {
        // width: 100%;
        // height: 100%;
        min-height: 95vh;

        display: grid;
        align-items: center;
        justify-content: center;
    }
	#button {
		font-size: 2rem;
		// font-family: '';
		// must be absolutely positioned
		background-color: white;
		border: none;
		outline: none;
		&:hover {
			cursor: pointer;
		}

		padding: 2rem;
		// position: absolute;
        left: 0;
        right: 0;
	}
</style>

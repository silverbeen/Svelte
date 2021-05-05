<script>
    //Props
	export let names;
</script>

<main>
	<h2>Name</h2>
	<ul>
		{#each names as name}
			<li>{name}</li>
		{/each}
	</ul>
	<h2>Name : reverse -> 배열의 형태를 반대로 출력합니다.</h2>
	<h3>배열의 복사본을 만들어 출력해야합니다.</h3>
	<ul>
		{#each [...names].reverse() as name }
			<li>{name}</li>
		{/each}
	</ul>
	<h2>Name : slice(2)</h2>
	<ul>
		{#each names.slice(2) as name }
			<li>{name}</li>
		{/each}
	</ul>
</main>

<style lang="scss">
	
  </style>

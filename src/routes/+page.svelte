<script>
    let firstName = 'Naomi';
    let lastName = 'Perenboom';
    let color = 'red';

    let name = firstName + ' ' + lastName 

    const toggle = () => {
        color = color ==='red' ? 'pink' : 'red'
    }
</script>


<main> 
<h1 style= "color: {color}">Hi {name}, welcome! </h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={toggle}>Click me </button>
</main>
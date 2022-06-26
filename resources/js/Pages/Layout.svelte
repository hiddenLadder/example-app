<script>
    export let title;
</script>

<svelte:head>
    <title>
        {title}
    </title>
</svelte:head>

<header>header</header>
<main>
    <slot />
</main>

<footer>footer</footer>

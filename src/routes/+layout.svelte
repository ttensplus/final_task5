<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo">Welcome</a>
        <div class="nav-links">
            {#each nav as link}
                {#if link.isShow}
                    <a href={link.href} class="link">{link.title}</a>
                {/if}     
            {/each}
        </div>
    </div>
</nav>
<div class="container">
    <slot></slot>
</div>


<script>
    const nav = [
        {
            title: 'About us',
            href: '/about',
            isShow: true
        },
        {
            title: 'Contacts',
            href: '/contact',
            isShow: true
        }
    ]
</script>
<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>
<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo">Front page</a>
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
            title: 'Details',
            href: '/information',
            isShow: true
        },
        {
            title: 'About me',
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
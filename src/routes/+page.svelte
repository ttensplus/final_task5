<svelte:head>
    <title>Front page</title>
</svelte:head>

<div class="container">
    <!-- <div class="info">
        <div class="animate-background">
            <img src="src\images\20230329_223142.jpg" alt="">
            <div class="container info-container">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
            </div>
            
        </div>
    </div> -->
    <img src="src\images\20230329_223142.jpg" alt="Handmade model">
    <div>
        <div class="title-container">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
        </div>
    <div class="info-container">   
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
    </div>
    </div>
</div>
<!-- <div class="background-div"></div> -->

<style>
    .info {
        text-align: center;
        position: relative;
    }
    .info-container {
        height: 100%;
        width: 100%;
        padding: 5px 15px;
        display: flex;
        flex-direction: column;
        /* justify-content: center; */
        text-align: justify;
        align-items: start;
    }
    .title-container {
        text-align: center;
        padding: 25px 0 25px 0;
        /* line-height: 1; */
		font-size: 1.1rem;
        font-weight: bold;
    }
    .container {
        max-width: 1400px;
        display: flex;
        margin-bottom: 1rem;
        flex-direction: row;
        top: 0;
		left: 0;
		right: 0;
		margin: 0 80px 0 80px;
        background-color: #ecebe8;
    }
    .info h1 {
        font-size: 4rem;
        margin: 0;
    }
    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
    }
    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.50rem;
    }
    /* .background-div {
        background-color: #ecebe8;
        width: 100%;
        height: 56vh;
        margin: -205px auto;
    } */
    .info .info-text {
        position: relative;  
    }
    .scroll-button {
        display: flex;
        border: none;
        outline: none;
        cursor: pointer;
    }
    .scroll-button .arrow {
        margin-left: 0.50rem;
    }
    img {
        max-width: 300px;
        max-height: 300px;
    }
</style>
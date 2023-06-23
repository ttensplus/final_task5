<svelte:head>
    <title>Front page</title>
</svelte:head>

<script>
    import tube from "./images/tube.jpg"
 </script>

<h1 style="text-align: center; margin-bottom: 0">Kepler</h1>
<div class="info-container" style="padding: 0 90px 30px 90px;">
    
    <p>Johannes Kepler was a German astronomer, mathematician, astrologer, natural philosopher and writer on music. He is a key figure in the 17th-century Scientific Revolution, best known for his laws of planetary motion, and his books Astronomia nova, Harmonice Mundi, and Epitome Astronomiae Copernicanae. These works also provided one of the foundations for Newton's theory of universal gravitation.</p>
</div>
<div class="container">
    <!-- <div class="info">
        <div class="animate-background">
            <img src="src\images\20230329_223142.jpg" alt="">
            <div class="container info-container">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dicta voluptas pariatur alias rerum assumenda eum eligendi aperiam. Officiis vel quia fugiat quidem adipisci autem dolorum, exercitationem amet perferendis excepturi.
            </div>
            
        </div>
    </div> -->
    
    <img src={tube} alt="Model">
    <div>
        <div class="title-container">
            My own experience
        </div>
    <div class="info-container">   
        I made this model by myself. I used simple and usual materials. 
        It's construction includes mainly plumbing pipes, however the optical linces remain the most important part of the optical tube. 
        And it works!!! The result is really impressive. The tube is not perfect, but I'm glad that I tried to replicate this invantion. You also can find more information on this website.
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
        /* height: 100%; */
        width: 100%;
        /* padding: 5px 15px; */
        padding:  0 30px 20px 30px;
        display: flex;
        flex-direction: column;
        /* justify-content: center; */
        text-align: justify;
        align-items: start;
        font-size: 1.25rem;
    }
    .title-container {
        text-align: center;
        padding: 40px 0 20px 0;
        /* line-height: 1; */
		font-size: 1.5rem;
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
        width: 200px;
        height: 300px;
        /* min-height: 100px; */
        /* min-width: 100px; */
        align-items: center;
    }
</style>
<svelte:head>
    <title>Front page</title>
</svelte:head>

<script>
    import tube from "./images/tube.jpg"
 </script>

<h1 style="text-align: center; margin-bottom: 0">Kepler</h1>
<div class="info-container" style="padding: 0 7% 5% 7%;">   
    <p>Johannes Kepler was a German astronomer, mathematician, astrologer, natural philosopher and writer on music. He is a key figure in the 17th-century Scientific Revolution, best known for his laws of planetary motion, and his books Astronomia nova, Harmonice Mundi, and Epitome Astronomiae Copernicanae. These works also provided one of the foundations for Newton's theory of universal gravitation.</p>
</div>
<div class="container">  
    <img src={tube} alt="Model">
    <div style="background-color: #ecebe8;">
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

<style>
    .info-container {
        width: 100%;
        padding:  0 30px 20px 30px;
        display: flex;
        flex-direction: column;
        text-align: justify;
        align-items: start;
        font-size: 1.25rem;
    }
    .title-container {
        text-align: center;
        padding: 4% 0 2% 0;
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
		margin: 0 7% 0 7%;  
    }
    img {
        width: 200px;
        height: 300px;
        align-items: center;
    }
    @media screen and (max-width: 754px) {
        .container {
            flex-direction: column;
        }
        img {
            width: 100%;
            height: auto;
        }
    }
    @media screen and (max-width: 500px) {

    }
</style>
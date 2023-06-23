<script>
    import conMat from "../images/connecting materials.jpg"
    import con1 from "../images/connection1.jpg"
    import con2 from "../images/connection2.jpg"
    import len1 from "../images/lens1.jpg"
    import len2 from "../images/lens2.jpg"
    import tubes from "../images/tubes.jpg"
 </script>

<div class="img-container">
    <div style="display: flex; flex-direction: row;">
        <div class="img">
            <img src={conMat} alt="picture">
            <p>Connecting materials</p>
        </div>
        <div class="img">
            <img src={con1} alt="picture">
            <p>Connection for tubes</p>
        </div>
        <div class="img">
            <img src={con2} alt="picture">
            <p>Connection for tubes</p>
        </div>
        <div class="img">
            <img src={len1} alt="picture">
            <p>Small lens</p>
        </div>
    </div>
    <div style="display: flex; flex-direction: row;">
        <div class="img">
            <img src={len2} alt="picture">
            <p>Big lens</p>
        </div>
        <div class="img">
            <img src={tubes} alt="picture">
            <p>Tubes</p>
        </div>
    </div>
</div>

 <style>
    img {
        height: 400px;
        width: 300px;
    }
    .img-container {
        display: flex;
        flex-direction: column;
        max-width: 100%;
        background-color: antiquewhite;
        padding: 50px 90px 0 90px;
        border-radius: 10px;
    }
    .img {
        margin: 0 10px 0 0;  
    }
 </style>


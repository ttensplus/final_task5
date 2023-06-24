<script>
    import conMat from "../images/connecting materials.jpg"
    import con1 from "../images/connection1.jpg"
    import con2 from "../images/connection2.jpg"
    import len1 from "../images/lens1.jpg"
    import len2 from "../images/lens2.jpg"
    import tubes from "../images/tubes.jpg"
 </script>

<div class="img-container">  
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
        <div class="img">
            <img src={len2} alt="picture">
            <p>Big lens</p>
        </div>
        <div class="img">
            <img src={tubes} alt="picture">
            <p>Tubes</p>
        </div>

</div>

 <style>
    img {
        height: 400px;
        width: 300px;
    }
    .img-container {
        display: flex;
        flex-wrap: wrap;
        background-color: antiquewhite;
        padding: 50px 10% 0 10%;
        border-radius: 10px;
        justify-content: space-between;
        
    }
    /* .img {
        margin: 0 10px 0 0;  
    } */
    @media screen and (max-width: 749px) {
        .img-container {
            justify-content: center;
        }
    }
 </style>


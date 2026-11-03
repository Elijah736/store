<template>
    <footer class="footer-container">
        <nav class="footer-nav">
            <div class="section1">
                <h1>Mero <span>.</span></h1>
                <p>Thoughtful goods for a life with more character and less clutter</p>
            </div>
            <div class="section2">
                <p class="footer-heading">SHOP</p>
                <p>All products</p>
                <p>New arrivals</p>
                <p>Gift cards</p>
            </div>
            <div class="section3">
                <p class="footer-heading">HELP</p>
                <p>Shipping & returns</p>
                <p>Contact us</p>
                <p>FAQ</p>
            </div>
            <div class="section4">
                <p class="footer-heading">FOLLOW</p>
                <p>Instgram</p>
                <p>Pinterest</p>
                <p>TikTok</p>
            </div>
            <br>
        </nav><hr class="footer-hr">
        <div class="footer-bottom-section">
            <p>@2026 Mero Goods. All rights reserved.</p>
        </div>
    </footer>
</template>

<style scoped>
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  z-index: 100;
}


.footer-container{
    background-color: #1C1C1C;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.footer-nav{
    padding: 100px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 100px;
    box-sizing: border-box;
}

.footer-heading{
    color: #FF5A36;
}

.section1 span{
    color: #FF5A36;
}

.section1{
    font-size: large;
}

.section1{
    color: white;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 20px;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: -0.01em;
    font-family: 'Plus Jakarta Sans', sans-serif;
    text-transform: none;
}

.section2{
    transform: scale(1);
    transition: transform 0.3s ease-out;
    color: white;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 20px;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: -0.01em;
    font-family: 'Plus Jakarta Sans', sans-serif;
    text-transform: none;
}

.section2:hover{
    transform: scale(1.05);
}

.section3{
    transform: scale(1);
    transition: transform 0.3s ease-out;
    color: white;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 20px;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: -0.01em;
    font-family: 'Plus Jakarta Sans', sans-serif;
    text-transform: none;
}

.section3:hover{
    transform: scale(1.05);
}

.section4{
    transform: scale(1);
    transition: transform 0.3s ease-out;
    color: white;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 20px;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: -0.01em;
    font-family: 'Plus Jakarta Sans', sans-serif;
    text-transform: none;
}

.section4:hover{
    transform: scale(1.05);
}

.footer-hr{
    margin-right: 200px;
    margin-left: 200px;
    color: #1C1C1C;
}

.footer-bottom-section{
    text-align: center;
    padding: 20px;
    color: white;
}
</style>
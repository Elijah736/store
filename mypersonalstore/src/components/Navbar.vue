<template>
    <div class="NavbarContainer">
        <div class="storelogo">
            <h1>MERO<span>.</span></h1>
        </div>
        <nav>
            <ul class="NavbarList">
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/products">Products</router-link></li>
                <li><router-link to="/about">About</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
            </ul>
        </nav>
        <div class="storecart">
            <button class="cartbutton"><i class="fa-solid fa-bag-shopping"></i> View Cart <span class="cartspan">0</span></button>
        </div>
    </div>
</template>

<style scoped>


.NavbarContainer{
    padding: 20px;
    justify-content: center;
    gap: 500px;
    background-color: #F9F6F0;
    display: flex;
    flex-direction: row;
    align-items: center;
}

.NavbarList{
    font-size: 13px;
    font-weight: 600;
    color: #1C1C1C;
    letter-spacing: -0.01em;
    font-family: 'Plus Jakarta Sans', sans-serif;
    text-transform: none;
    position: sticky;
    display: flex;
    flex-direction: row;
    justify-self: center;
    text-align: center;
    gap: 20px;
    box-sizing: border-box;
    list-style: none;
}

.storelogo span{
    color: #FF5A36;
}

.storecart button{
    word-spacing: 2px;
    letter-spacing: -0.01em;
    text-transform: none;
    color: #1C1C1C;
    border: 1px solid black;
    background-color: #F9F6F0;
    font-size: 13px;
    font-weight: 600;
    width: 150px;
    padding: 10px;
    border-radius: 20px;
}

.storecart button:hover {
    background-color: #333232;
    color: white;
}

.storecart span{
    color: white;
    border-radius: 50%;
    padding: 5px;
    background-color: #FF5A36;
}

</style>

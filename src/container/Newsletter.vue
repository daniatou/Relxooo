<template>
    <div class="relative  newsletter flex flex-col items-center justify-center md:h-[50vh]">
        <h4 class="text-4xl font-bold tracking-wide text-center">Get Every Single Updates</h4>
        <p class="text-lg tracking-wide text-center my-4">Many desktop publish packages web page editors now use model text <br> search for sites their infancy.</p>

        <div class="flex-none  mt-7">
           <input type="text" placeholder="Enter Your Mail*">
            <button class="text-white rounded-[5px] hover:bg-slate-800">Suscribe Now</button>
        </div>
        <div class="absolute rotate-shape right-[60%]">
            <img src="../assets/shape2.png" alt="">
        </div>
        <div class="absolute bottom-0 md:text-lg text-xs tracking-wide text-slate-500 hover:text-[#fc410e] text-center cursor-pointer animate__animated animate__heartBeat">&copy;Daniatou DJIBRIL</div>
    </div>
    
</template>



<style scoped>

.newsletter {
    background-image: url('../assets/newsletter-bg.webp');

}

input {
    border: 2px solid var(--primary-color);
    padding: 18px;
    width: 400px;
    border-radius: 5px;
    outline: none;
    margin-right: 10px;
}

@media only screen and (max-width: 600px) {
    input {
    border: 2px solid var(--primary-color);
    padding: 10px;
    width: 200px;
    border-radius: 5px;
    outline: none;
    margin-right: 10px;
    margin-bottom: 30px;
}

    
}

.rotate-shape {
   animation: rotate-infinite 10s infinite linear;
}

@keyframes rotate-infinite {
    100%{
        transform: rotate(90deg)
    }
}

</style>


<template>
    <footer>
        <div class="footer_main" id="kontak">

            <div class="footer_tag">
                <h2 style="font-size: 20px;">Lokasi</h2>
                
                <p>Bogor</p>
                <p>Jawa Barat</p>
                <p>Indonesia</p>
            </div>

            <div class="footer_tag">
                <h2 style="font-size: 20px;">Quick Link</h2>
                <p>Home</p>
                <p>About</p>
                <p>Riwayat</p>
                
            </div>

            <div class="footer_tag">
                <h2 style="font-size: 20px;">Kontak</h2>
                <p>0895613418</p>
                <p></p>
                <p>rivalditzy@gmail.com</p>
               
            </div>

            

            <div class="footer_tag">
                <h2 style="font-size: 20px;">Follows</h2>
               <a href="https://wa.me/+628095613118"> <i class="fa-brands fa-whatsapp"></i></a>
               
                <a href="https://instagram.com/vixstnly?igshid=YzdkMWQ2MWU="><i class="fa-brands fa-instagram"></i></a>
               
            </div>

        </div>

        <p class="end" style="color: white;">Design by<span><i class="fa-solid fa-face-grin"></i> Rivaldi</span></p>

    </footer>
</template>
<style>
footer{
    width: 100%;
    padding: 30px 0 0 20px;
    background: #000000;
}

footer .footer_main{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
}

footer .footer_main .footer_tag{
    text-align: center;
}
.footer_tag p{
    font-size: 10px;
  color: white;
}


footer .footer_main .footer_tag h2{
    color: #ffffff;
    margin-bottom: 25px;
    font-size: 30px;
}

footer .footer_main .footer_tag p{
    margin: 10px 0;
}

footer .footer_main .footer_tag i{
    margin: 0 5px;
    cursor: pointer;
}

footer .footer_main .footer_tag i:hover{
    color: #ffffff;
}

footer .end{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 15px;
}

footer .end span{
    color: #fac031;
    margin-left: 10px;
}</style>
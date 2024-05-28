<script>
    import ig from '$lib/assests/instagram.png'
    import wa from '$lib/assests/whatsapp.png'
    import www from '$lib/assests/web.png'

</script>

<center>
<div>
    <!-- Instagram icon -->
    <div class="social-icon instagram">
        <img src="{ig}">
    </div>

    <!-- Website icon -->
    <div class="social-icon website">
        <img src="{www}">
    </div>

    <!-- WhatsApp icon -->
    <div class="social-icon whatsapp">
        <img src="{wa}">    
    </div>
    <hr width="100%">
</div>
</center>
<div class="grid lg:grid-cols-3 gap-4 p-10">
    <!-- Column 1 -->
    <div class="bg-blue-200 p-4">
        <p class="text-4xl mb-4">Kontak Kami</p>
        <p>Nomor: 0895-3146-2766</p>
        <p>Alamat: Jl. Satria Utara 2 Ruko No.4 RT07, RW.04, Plombokan, Semarang Utara, Semarang City, Central Java 50171</p>

    </div>

    <!-- Column 2 -->
    <div class="bg-green-200 p-4">
        <p class="text-4xl mb-4">Links</p>
        <ul>
            <li>Home</li>
            <li>About us</li>
            <li>Services</li>
            <li>Contact</li>
        </ul>
    </div>

    <!-- Column 3 -->
    <div class="bg-yellow-200 p-4">
        <p class="text-4xl mb-4">Google Maps</p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15841.411285935745!2d110.4112449!3d-6.9676385!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e70f5b9aed3c1e7%3A0xc2cefb3e5ac399c4!2sPenjahit%20Trend%20Tailor%20Semarang!5e0!3m2!1sen!2sid!4v1716906888540!5m2!1sen!2sid" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>    </div>
</div>
<div class="text-center p-2">
    <p>Designed and developed by <a href="https://riveong.com" style="color:white">Riveong</a> with 🔥</p>
</div>



<style>
    div{
        background-color: #FCAF3C;
    }
    .social-icon {
            display: inline-block;
            width: 40px;
            height: 40px;
            margin-right: 10px;
            text-align: center;
            line-height: 40px;
            font-size: 24px;
            border-radius: 50%;
            padding:10px;

        }

        /* Instagram icon */
        .instagram {
            background-color: #E4405F;
            color: white;
        }

        /* Website icon (generic link) */
        .website {
            background-color: #dcdcdc;
            color: white;
        }

        /* WhatsApp icon */
        .whatsapp {
            background-color: #25D366;
            color: white;
        }
</style>
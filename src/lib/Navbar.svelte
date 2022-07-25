<header>

    <div class="user">
        <img src="/user.png" alt="user">
        <h3>User</h3>
    </div>
    <nav>
    <div class="menu">
        <ul>
            <li><img src="/home.png" alt="home"><a href="/">Home</a></li>
            <li><img src="/broadcast.png" alt="broadcast"><a href="/broadcast">Broadcast</a></li>
            <li><img src="/podcast.png" alt="podcast"><a href="/podcast">Podcast</a></li>
        </ul>
    </div>
</nav>
</header>

<style>
   header{
    position: fixed;
    top: 0; left: 0;
    z-index: 1000;
    height: 100%;
    width: 245px;
    background: #2e2b2b;
    display: flex;
    align-items: center;
    justify-content: start;
    flex-flow: column;
    text-align: center;
   }

   header .user img{
    width: 80; height: 80;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
    margin-top: 3rem;
    border: 0.7 solid;
   }

   header .user h3{
    font-size: 1rem;
    color: white;
    margin-top: -1rem;
   }

   header nav .menu ul{
    list-style: none;
   }

   header nav .menu ul li{
    display: flex;
    align-items: center;
    justify-content: start;
    padding: 1.5rem;
   }

   header nav .menu ul li a{
    color: white;
    text-decoration: none;
    justify-content: start;
   }

   header nav .menu ul li img{
    cursor: pointer;
   }

   header nav .menu ul li img:hover{
    color: brown;
   }

   header nav .menu ul li a:hover{
    color: brown;
   }

</style>
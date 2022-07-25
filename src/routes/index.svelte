<main>
    <div class="search">
        <input type="text">
        <h3>Welcome to the Party</h3>
    </div>
    
    <div class="card-container">
        <div class="card-item">
            <div class="image-container">
                <img src="/card.png" alt="card">
            </div>
            <div class="content">
                <div class="content-main">
                    <h1>Ngobrolin Masalah Keluarga</h1>
                    <p>lorem ipsum dskjfkldasjfkadsjfkljadsklfjkldsjfkldsjfkladsjfkladsjfkladsjkfljdasklfjkadsljffjkadsfdlkdjsfkladsklfkdsljflkdsjflkdasjfkldasjfkladsjfkl;adsmc,nzcxmnvjhgounfkldsnjadshfioadsjfkljadsl;fjadskljflkadsfkldsajfkladsjfkladslkfhewiofhljadsnfjlsdnm,ncm,xn lcioSF;</p>
                </div>
                <div class="content-buttons">
                    <div class="content-buttons-group">
                        <img src="/comment.svg" alt="comment">
                        <p>Comment</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/like.svg" alt="like">
                        <p>Like</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/share.svg" alt="share">
                        <p>Share</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="card-item">
            <div class="image-container">
                <img src="/card.png" alt="card">
            </div>
            <div class="content">
                <div class="content-main">
                    <h1>Ngobrolin Masalah Keluarga</h1>
                    <p>lorem ipsum dskjfkldasjfkadsjfkljadsklfjkldsjfkldsjfkladsjfkladsjfkladsjkfljdasklfjkadsljffjkadsfdlkdjsfkladsklfkdsljflkdsjflkdasjfkldasjfkladsjfkl;adsmc,nzcxmnvjhgounfkldsnjadshfioadsjfkljadsl;fjadskljflkadsfkldsajfkladsjfkladslkfhewiofhljadsnfjlsdnm,ncm,xn lcioSF;</p>
                </div>
                <div class="content-buttons">
                    <div class="content-buttons-group">
                        <img src="/comment.svg" alt="comment">
                        <p>Comment</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/like.svg" alt="like">
                        <p>Like</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/share.svg" alt="share">
                        <p>Share</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="card-item">
            <div class="image-container">
                <img src="/card.png" alt="card">
            </div>
            <div class="content">
                <div class="content-main">
                    <h1>Ngobrolin Masalah Keluarga</h1>
                    <p>lorem ipsum dskjfkldasjfkadsjfkljadsklfjkldsjfkldsjfkladsjfkladsjfkladsjkfljdasklfjkadsljffjkadsfdlkdjsfkladsklfkdsljflkdsjflkdasjfkldasjfkladsjfkl;adsmc,nzcxmnvjhgounfkldsnjadshfioadsjfkljadsl;fjadskljflkadsfkldsajfkladsjfkladslkfhewiofhljadsnfjlsdnm,ncm,xn lcioSF;</p>
                </div>
                <div class="content-buttons">
                    <div class="content-buttons-group">
                        <img src="/comment.svg" alt="comment">
                        <p>Comment</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/like.svg" alt="like">
                        <p>Like</p>
                    </div>
                    <div class="content-buttons-group">
                        <img src="/share.svg" alt="share">
                        <p>Share</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>



<style>
    main{
        padding-left: 16rem;
        padding-top: 3rem;
        color: white;
    }

    main .search{
        display: flex;
        align-items: center;
        justify-content: start;
    }

    main .search input{
        width: 668px;
        height: 46px;
        border-radius: 10rem;
    }

    main .search h3{
        color: white;
        font-size: 24px;
        margin: 14px;
    }

    .card-container {
        display: flex;
        flex-direction: column;
        gap: 8px;
        width: 90%;
        margin-top: 32px;
    }

    .card-item {
        border-radius: 16px;
        background-color: #2E2B2B;
        padding: 16px;
        width: 100%;
        display: flex;
        gap: 16px;
    }

    .image-container {
        display: flex;
        gap: 8px;
    }

    .content {
        flex-grow: 1;
        width: calc(100% - 300px);
        position: relative;
    }

    .content-main {
        width: 100%;
        height: 100%;
    }

    .content-main p {
        word-wrap: break-word;
        font-size: 1.15em;
    }

    .content-buttons {
        display: flex;
        gap: 32px;
        align-items: center;
        position: absolute;
        bottom: 0;
    }

    .content-buttons-group {
        display: flex;
        align-items: center;
        gap: 8px;
        cursor: pointer;
    }



  
</style>
```css
body{
    margin:0;
    padding:0;
    background-color:lightgrey;
    position:relative;
    top:12vh;
}
#header{
    position:fixed;
    top:0;
    left:0;
    width:100vw;
    height:10vh;
    background-color:lightgray;
    z-index:999;
}
#header img{
    max-width:400px;
    width:50vw;
    position:fixed;
    margin: 10px auto;
}
ul{
    display:flex;
    list-style:none;
    position:fixed;
    right:0px;
}
a{
    color:black;
    text-decoration:none;
    font-size:1.1rem;
    margin:0px 0.8rem;
}
  #form p{
    text-align:center;
    font-weight:bold;
    font-size:1.3rem;
}
#form{
    width:70vw;
    height:20vh;
    margin:20px auto;
}
input{
    display:block;
    width:40%;
    height:2rem;
    margin:15px auto;
    min-width:200px;
}
input[type="submit"],#btn{
    width:20vw;
    background-color:yellow;
    border:none;
    font-weight:bold;
    font-size:0.9rem;
    min-width:120px;
}
#feature{
    display:grid;
    grid-template-columns:2 1fr;
}
.feature{
    display:flex;
    border:1px solid gray;
    margin:10px auto;
    width:80vw;
    border-radius:20px;
}
.feature span{
    padding:10px;
    margin:auto 10px;
}
#how_it_works{
    display:flex;
    justify-content:center;
}
iframe{
    background-image: url("https://i.ytimg.com/vi_webp/y8Yv4pnO7qc/maxresdefault.webp");
    width:360px;
    height:360px;
}
#pricing{
    width:80%;
    padding:10px;
    margin:auto;
    display:flex;
    flex-wrap:wrap;
}
h2,h3{
    margin:10px;
}
.box{
    width:300px;
    margin:10px auto;
    padding:10px;
    border:2px solid gray;
    border-radius:20px;
    text-align:center;
}
@media only screen and (max-width:580px){
    body{
      top:15vh;
    }
    #header{
      height:80px;
      overflow:scroll;
    }
    #header::-webkit-scrollbar {
    display: none;
    }
    #header{
    -ms-overflow-style: none;  /* IE and Edge */
    scrollbar-width: none;  /* Firefox */
    }
    #form{
      height:150px;
    }
    #nav-bar ul{
      position:absolute;
      top:20px;
      left:0%;
      margin:35px auto;
    }
    #header img{
      width:100%;
    }
    iframe{
      width:360px;
      height:360px;
    }
}
@media (max-width:320px){
    iframe{
      width:180px;
      height:200px;
    }
    input[type="email"]{
      padding:0px;
      min-width:150px;
    }
}
```
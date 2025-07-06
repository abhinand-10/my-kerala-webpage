# my kerala css code

body {
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    margin: 0;
    min-height: 100vh;
    font-family: sans-serif;
}
.na {
    height: 70%;
    width: 100%;
}

.navbar {
    background-color: rgba(92, 189, 245, 0.842);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
}
.nav-container {
    background-color: rgb(240, 255, 246);
    padding:15px 30px;
    border-radius: 10px;
    display:flex;
    align-items: center;
    gap: 50px;
    box-shadow:0 4px 10px rgba(0,0,00.2)

}
.nav-links{
    list-style: none;
    display: flex;
    gap:25px;
    
}
.nav-links li a {
    text-decoration: none;
    font-size: 20px;
    color:antiquewhite;
    transition: color 0.3s ease;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: darkgreen;
    font-family: sans-serif;
}
.logoo{
    width: 70px;
    height: 40px;
}
.hero{
    background: linear-gradient(to right, #80deea, #e1f5fe);
    padding: 50px 20px;
    text-align: center;
}
.heroo h1{
    font-size: 50px;
    color: #004d40;
    margin-bottom: 10px;

}
.heroo p{
    font-size: 18px;
    margin-bottom: 30px;
    color: #333;
}
.hero-button {
    background-color: #004d40;
    color: #fff;
    padding: 12px 25px;
    border: none;
    font-size: 15px;
    border-radius: 2px;
    transition: background-color 0.3s ease;
}
.hero-button:hover {
    background-color: #00695c;
}
.about {
    padding: 20px 20px;
    max-width: 900px;
    margin: auto;
}
.about h2{
    text-align: center;
    font-size: 30px;
    margin-bottom: 20px;
    color: #00695c;
}
.about p {
    font-size: 15px;
    margin-bottom: 15px;
    text-align: center;
}
.footer {
    background-color: #05947c;
    color:#fff;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
.a1 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin: 20px 0;
}
.a2 {
    width: 30%;
    min-width: 100px;
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px;

}
.a2 img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}
.a2 p {
    padding: 10px;
    font-weight: bold;
}

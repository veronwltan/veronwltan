@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;700&display=swap');

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    background-color: #252422;
}

li, a, button{
    font-family:"Montserrat", sans-serif;
    font-weight: 300;
    font-size: 16px;
    color: #CCC5B9;
    text-decoration: none;
}

header{
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 30px 10%;
}

.logo{
    cursor: pointer;
    margin-right: auto;
}

.nav_links{
    list-style:none;
}

.nav_links li{
    display:inline-block;
    padding: 0px 20px;
}

.nav_links li a{
    transition: all 0.3s ease 0s;
}

.nav_links li a:hover{
    color: #EB5E28;
}

button{
    margin-left: 20px;
    padding: 9px 25px;
    background-color: rgba(0,136,169,1);
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
}

button:hover{
    background-color: rgba(0,136,169,0.8);
}


.container{
    max-width: 1170px;
    margin: auto;
    position:relative;
}


.row{
    display: flex;
    flex-wrap: wrap;
}

ul{
    list-style:none;
}

.footer{
    background-color: #252422;
    padding: 70px 0;
}

.footer-col{
    width: 30%;
    padding: 0 15px;
}

.footer-col h4{
    font-size: 20px;
    color: #CCC5B9;
    text-transform: capitalize;
    margin-bottom: 35px;
    font-weight: 700;
    position: relative;
}

.footer-col h4::before{
    content:'';
    position: absolute;
    Left:0;
    bottom: -10px;
    background-color: #EB5E28;
    height: 2px;
    box-sizing: border-box;
    width: 50px;
}

.footer-col ul li:not(:last-child){
    margin-bottom: 10px;
}

.footer-col ul li a{
    font-size:16px;
    text-transform: capitalize;
    color: #CCC5B9;
    text-decoration: none;
    font-weight: 300;
    color: #bbbbbb;
    display: block;
    transition: all 0.3s ease;
}

.footer-col ul li a:hover{
    color: #EB5E28;
    padding-left: 10px;
}


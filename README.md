# hello-world
LOGO DESIGN FOR LG 
/*CSS LG LOGO*/
.LG-logo{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background-color: #ea4335;
    position: relative;
}

.G{
    width: 80px;
    height: 80px;
    border-radius: 50%;
    position: absolute;
    left: 10px;
    top: 10px;
    border: 3px solid white;
    box-sizing: border-box;
    border-top: 3px solid transparent;
    transform: rotate(45deg);
}

.LG-logo::before{
    content: "";
    display: block;
    width: 25px;
    height: 0%;
    position: absolute;
    right: 13px;
    top: 50%;
    border-top: 3px solid white;
    box-sizing: border-box;
    transform-origin: 30px 0;
}


.L_and_eye{
    position: absolute;
    border: 3px solid white;
    border-right: none;
    border-top: none;
    width: 10px;
    height: 30px;
    left: calc(50% - 3px);
    top: 35px;
}

.L_and_eye::before{
    content: '';
    display: block;
    position: absolute;
    background-color: white;
    border-radius: 50%;
    width: 10px; 
    height: 10px;
    right: 20px;
    top: -5px;
}

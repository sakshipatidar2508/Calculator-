*{
        margin: 0;
        padding: 0;
        font-family:'Times New Roman', Times, serif;
        box-sizing: border-box;
}
.container{

        width: 100;
        height: 100vh;
        background:rgb(207, 232, 230);
        display: flex;
        align-items: center;
        justify-content: center;

}
.calculater{
    background:rgb(53, 55, 57);
    padding: 20px;
    border-radius: 5%;


}
.calculater form input{
    border: 0;
    outline: 0;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    box-shadow: -8px -8px 15px rgba(76, 65, 65, 0.153),5px 5px 15px rgba(0, 0, 0, 0.6);
    background: transparent;
    font-size: 20px;
    color: rgb(255, 255, 255);
    cursor: pointer;
    margin: 10px;

}
form .display{
    display: flex;
    justify-content: flex-end;
    margin: 20px 0;

}
form .display input{
    text-align: right;
    flex: 1;
    font-size: 45px;
    box-shadow: none;

}
form input.equal{
    width: 145px;
}
form input.operator{
    color: aqua;
}

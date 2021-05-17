<style>
	.img{
	    display: block;
        color: #000;
        border: 3px solid #000;
        border-radius: 3px;
        padding: 4px 8px;
        background: transparent;
        font-weight: bold;
        cursor: pointer;
        box-sizing: border-box;
        position: relative;
        top: -2px;
        left: -2px;
        transition: transform 0.2s;
        margin: 8px 6px 10px 6px;
        z-index: 1;
        user-select: none;
        -webkit-user-select: none;
        -moz-user-select: none;
    }
    .img::before{
    	content: "";
        background: transparent;
        border: 3px solid #000;
        border-radius: 3px;
        box-sizing: border-box;
        position: absolute;
        top: -3px;
        left: -3px;
        height: calc(100% + 6px);
        width: calc(100% + 6px);
        z-index: -1;
    }
    .img::after{
    	content: "";
        display: block;
        box-sizing: border-box;
        background: #222;
        border: 3px solid #000;
        border-radius: 3px;
        height: calc(100% + 6px);
        width: calc(100% + 6px);
        position: absolute;
        top: 3px;
        left: 3px;
        right: 0;
        z-index: -2;
        transition: transform 0.2s;
    }
    .img:hover{
    	transform: translate(2px, 2px);
    }
    .img:hover::after{
    	transform: translate(-2px, -3px);
    }
</style>

<div class="img">
	<center><a href="https://ahmadhayyan.github.io"><img src="https://raw.githubusercontent.com/ahmadhayyan/ahmadhayyan/main/banner2.png"/></a></center>
</div>

<!DOCtype <!DOCTYPE html>

<html>

<head>

    <meta charset="utf-8" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

​    <title>Page Title</title>

    <meta name="viewport" content="width=device-width, initial-scale=1">

</head>

<body id="parent">      

    <script>

​        var element = document.getElementById("parent")

​        element.insertAdjacentHTML("beforeend","<div id='a'></div>")

​        element.insertAdjacentHTML("afterbegin","<button id='big'>放大</button>")

​        element.insertAdjacentHTML("afterbegin","<button id='litter'>缩小</button>")

​        element.insertAdjacentHTML("afterbegin","<button id='left'>左移</button>")

​        element.insertAdjacentHTML("afterbegin","<button id='right'>右移</button>")

​        var div=document.getElementById("a")

​        a.style.background='blue'

​        a.style.width='200px'

​        a.style.height='200px'

​        a.style.transitionDuration="2s"

​        var big=document.getElementById("big")

​        big.onclick=function(){

​            a.style.width='400px'

​            a.style.height='400px'

​        }

​        var litter=document.getElementById("litter")

​        litter.onclick=function(){

​            a.style.width='100px'

​            a.style.height='100px'

​        }

​        var left=document.getElementById("left")

​        left.onclick=function(){

​          a.style.marginLeft="0px"

​        }

​        var right=document.getElementById("right")

​        right.onclick=function(){

​            a.style.marginLeft='200px'

​        }

​    </script>                

</body>

</html>
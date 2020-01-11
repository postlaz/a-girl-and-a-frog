<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        :root{
            --sprite-scale: 1;
            --sprite-pos: 0;
            --sprite-to: -40px;
            --girl-pos : top;
        }
        *{
            box-sizing: border-box;
        }
        body{
            width: 100%;
            height:100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #8aa4a2;
        }
        .postlaz{
            position: fixed;
            bottom: 20px;
            right: 20px;
            opacity: 0.5;
        }
        .postlaz a{
            font-size: 1.5em;
            font-weight: bold;
            color: black;
        }
        .postlaz:hover{
            opacity: 1;
        }
        .stage-wrapper{
            width: 30vw;
            height: 30vw;
            z-index: -1;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            filter: blur(5px);
        }
        .stage{
            position: absolute;
            width: 100vw;
            height: 100vh;
            top: 0;
            border-radius: 100vw;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .frog {
            position: relative;
            margin-top: 80px;
            width: 64px;
            height: 64px;
            background-image: url("frog.png");
        }
        .a-girl {
            width: 64px;
            height: 128px;
            background-image: url("a-girl-left.png");
            position: relative;
            /* top: 100px; */
            /* padding-bottom: 11px; */
        }
        .exclamation-wrapper{
            position: absolute;
            top: -135px;
            left: -25px;
            width: 100px;
            height: 200px;
            z-index: -1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-content: center;
            flex-wrap: wrap;
        }
        @keyframes  disappear {
            from{opacity: 1}
            to{opacity: 0}
        }
        .exclamation{
            width: 30px;
            height: 30px;
            background: url("exclamation.svg") no-repeat center;
            background-size: contain;
            z-index: -1;
        }
        .sigh{
            position: absolute;
            
            width: 10px;
            height: 10px;
            background-color: white;
            border-radius: 42% 58% 57% 43% / 42% 64% 36% 58% ;
            box-shadow: 1px 1px 5px black;
            opacity: 0;
        }
        .sigh::after{
            content: '';
            position: absolute;
            top: 0px;
            left: 5px;
            width: 5px;
            height: 5px;
            background-color: white;
            transform: rotate(45deg);
        }
        @keyframes sigh {
            0%{
                top: 50px;
                left: 20px;
                opacity: 1;
            }
            60%{
                top: 56px;
                left: 14px;
                opacity: 1;
            }
            100%{
                top: 60px;
                left: 10px;
                opacity: 0;
            }
        }
        .effect{
            position: absolute;
            top: 0;
            left: -10px;
            width: 100vw;
            height: 100vh;
        }
        .effect-canvas{
            position: relative;
            width: 100%;
            height: 100%;
        }
        .rain-wrapper{
            position: absolute;
            width: 30px;
            height: 100%;
            top: -90%;
            left: 106px;
            display: flex;
            justify-content: center;
        }
        .rain{
            width: 2px;
            height: 150px;
            border-radius: 100%;
            background-color: rgba(255, 255, 255, 0.4);
            z-index: 1;
            animation: rain 0.5s forwards ease-in;    
        }
        @keyframes rain{
            from{
                margin-top: -100px;
                opacity: 1;
            }
            to{
                margin-top: 90vh;
                opacity: 0;
            }
        }
        .rain-spot{
            position: absolute;
            width: 25px;
            height: 5px;
            top: 10%;
            left: 106px;
            border-radius: 100%;
            background-color: rgba(0, 0, 0, 0.2);
            z-index: -2;
            animation: rain-spot 3s forwards;
        }
        @keyframes rain-spot{
            0%{
                opacity: 0;
            }
            15%{
                opacity: 0;
            }
            20%{
                opacity: 1;
            }
            100%{
                opacity: 0;
            }
        }
        .shadow{
            position: absolute;
            width: 50px;
            height: 10px;
            top: 107px;
            left: 6px;
            border-radius: 100%;
            background-color: rgba(0, 0, 0, 0.1);
            z-index: -1;
            filter: blur(2.5px);
        }
        .shadow::after{
            content: '';
            position: absolute;
            left: 7.5px;
            top: 1px;
            width: 35px;
            height: 7.5px;
            border-radius: 100%;
            background-color: rgba(0, 0, 0, 0.2);
            z-index: -1;
        }
        .shadow-frog{
            top: 35px;
            left: 13px;
            z-index: -1;
            opacity: 0.3;
        }
        .anim{
            animation: play .5s steps(5) forwards, move .5s forwards cubic-bezier(0.3, 1, 1, 0.9), animation-control .4s forwards;
        }
        .flip{
            transform: scaleX(-1);
        }
        @keyframes animation-control {
            from { border: none;}
            to { border: none; }
        }
        @keyframes play {
            from { background-position:    -64px; }
            to { background-position: -384px; }
        }
        @keyframes move {
            0% { transform: translateX(var(--sprite-pos)) scaleX(var(--sprite-scale)); }
            20% { transform: translateX(var(--sprite-pos)) scaleX(var(--sprite-scale)); }
            100% { transform: translateX(var(--sprite-to)) scaleX(var(--sprite-scale)); }
        }

        .backward{
            animation: backward 0.25s steps(2) forwards;
        }

        @keyframes backward{
            from { 
                background-position: -128px var(--girl-pos);
                top: 0;
            }
            to { 
                background-position: -256px var(--girl-pos);
                top: -5px;
            }
        }

        .forward{
            animation: forward 0.2s steps(2) forwards;
        }

        @keyframes forward{
            from { 
                background-position: -256px var(--girl-pos);
                top: -5px;
            }
            to { 
                background-position: -128px var(--girl-pos);
                top: 0;
            }
        }
    </style>
</head>
<body onkeydown="arrow(event)">
    <div class="stage">
        <div class="a-girl" id="aGirl">
            <div class="exclamation-wrapper" id="exclamation-wrapper"></div>
            <div class="exclamation" id="exclamation-first" style="position:absolute;left: 30px; top: -20px; opacity: 0;"></div>
            <div class="shadow"></div>
            <div class="sigh" id="sigh"></div>
        </div>       
        <div class="frog" id="frog">
            <div class="shadow shadow-frog" id="shadow-frog"></div>
        </div>
        <div class="effect">
            <div class="effect-canvas" id="effect-canvas">
                <div class="rain-wrapper">
                    <div class="rain"></div>
                </div>
            </div>
        </div>
        <div class="rain-spot"></div>
    </div>
    <div class="postlaz">by <a href="https://www.instagram.com/postlaz/">postlaz</a></div>
    <script>
        var frogInitPos = window.innerWidth/4;
        let frog = document.getElementById("frog");
        frog.style.transform = "translateX("+frogInitPos+"px)"
        
        let shadowFrog = document.getElementById("shadow-frog");
        let aGirl = document.getElementById("aGirl");
        let sigh = document.getElementById("sigh");
        let effectCanvas = document.getElementById("effect-canvas");
        let exclamationWrapper = document.getElementById("exclamation-wrapper");
        let exclamationFirst = document.getElementById("exclamation-first");
        let root = document.documentElement;
        root.style.setProperty('--sprite-pos', frogInitPos+'px');
        root.style.setProperty('--sprite-to', frogInitPos+'px');
        let isRunning = false;
        let tempKey = null;
        let distance = frog.getBoundingClientRect().x - aGirl.getBoundingClientRect().x;
        let pos = 0;
        let to = 0;
        let animationName = null;
        let sighStat = false;
        let raining_intensity = 20;
        for (let index = 0; index < raining_intensity; index++) {
            raining()
        }
        let exclamation_intensity = 30;
        let exclamationArray = []
        exclamationInit()
        
        frog.addEventListener("animationend", animationDone,false);
        aGirl.addEventListener("animationend", animationDoneAGirl,false);
        function arrow(e){
            pos = root.style.getPropertyValue("--sprite-pos").replace('px', '');
            to = Number(root.style.getPropertyValue("--sprite-to").replace('px', ''));
            if (isRunning) {
                return
            }
            if (tempKey == e.key && animationName == "animation-control") {
                return
            }
            if(e.key == "ArrowLeft"){
                root.style.setProperty('--sprite-scale', 1);
                root.style.setProperty('--sprite-pos', to+'px');
                root.style.setProperty('--sprite-to', (to-50)+'px');
                frog.classList.remove("anim");
                shadowFrog.classList.remove("shadow-frog");
                void frog.offsetWidth;
                void shadowFrog.offsetWidth;
                frog.classList.add("anim");
                shadowFrog.classList.add("shadow-frog");
                tempKey = e.key;
                isRunning = true;
            }else if(e.key == "ArrowRight"){
                root.style.setProperty('--sprite-scale', -1);
                root.style.setProperty('--sprite-pos', to+'px');
                root.style.setProperty('--sprite-to', (to+50)+'px');
                frog.classList.remove("anim");
                shadowFrog.classList.remove("shadow-frog");
                void frog.offsetWidth;
                void shadowFrog.offsetWidth;
                frog.classList.add("anim");
                shadowFrog.classList.add("shadow-frog");
                tempKey = e.key;
                isRunning = true;
            }
        }
        function animationDone(event){
            animationName = event.animationName;
            isRunning = false;
            if (animationName != "animation-control") {
                setTimeout(function(){if(!isRunning){
                    let toTemp = root.style.getPropertyValue("--sprite-to");
                    let scaleTemp = root.style.getPropertyValue("--sprite-scale");
                    frog.classList.remove("anim");
                    frog.style.backgroundPosition = '-512px';
                    frog.style.transform = "translateX("+toTemp+") scaleX("+scaleTemp+")";
                }}, 150);
            }else{
                checkoffset()
            }  
        }
        function animationDoneAGirl(event){
            if (event.animationName == "backward") {
                aGirl.style.top = "-5px";
                aGirl.classList.remove("backward");
                void aGirl.offsetWidth;
            }else if (event.animationName == "forward") {
                aGirl.style.top = "0px";
                aGirl.classList.remove("forward");
                void aGirl.offsetWidth;
            }
        }
        function checkoffset(){
            let warn = 100;
            let saveZone = 50;
            let distanceNow = Math.abs(frog.getBoundingClientRect().x - aGirl.getBoundingClientRect().x);
            if (distanceNow < distance && distanceNow > 45) {
                let backPos = frog.getBoundingClientRect().x > aGirl.getBoundingClientRect().x ? 'top' : 'bottom';
                root.style.setProperty('--girl-pos', backPos);
                aGirl.style.backgroundPosition = '-64px '+backPos;
                if (sighStat) {  
                    exclamationFirst.style.opacity = 1;
                    if (distanceNow > 250) {
                        exclamationFirst.style.opacity = 1;
                    } else if (distanceNow > 170) {
                        exclamationRun(3)
                    } else if (distanceNow > 120) {
                        aGirl.classList.add("backward");
                        exclamationRun(8)
                    } else if (distanceNow > 70) {
                        exclamationRun(10)
                    }else{
                        exclamationRun(20)
                    }
                }else{
                    exclamationInit(); // init new set of exclamation
                }
                sighStat = true;
            }else{
                if (sighStat && distanceNow > 45) {
                    aGirl.style.backgroundPosition = '0px top';
                    setTimeout(function() {
                        aGirl.style.backgroundPosition = '0px bottom';
                        sigh.style.animation = 'none';
                        void sigh.offsetWidth;
                        sigh.style.animation = 'sigh 0.75s forwards linear';
                        exclamationWrapper.style.animation = 'disappear 1s forwards linear';
                        exclamationFirst.style.opacity = 0;
                        setTimeout(function(){if(aGirl.style.backgroundPosition == '0px bottom'){
                            // aGirl.style.backgroundPosition = '0px top';
                            aGirl.classList.add("forward");
                        }}, 1500);
                        sighStat = false;
                    }, 500);
                }else if (distanceNow <= 45) {
                    exclamationRun(30)
                    aGirl.style.backgroundPosition = '0px top';
                }
            }
            distance = distanceNow;          
        }
        function raining() {
            let duration = Number(Math.floor(Math.random() * 50)*100);
            let top = Number(Math.floor(Math.random() * 100));
            let left = Number(Math.floor(Math.random() * 60)+20);
            let sizePercentage = Number((Math.floor(Math.random() * 100)+30)/100);
            if (top < 40) {
                sizePercentage = Number(sizePercentage/1.5);
            }
            setTimeout(function() {
                let rainSpot = document.createElement("div");
                rainSpot.classList.add("rain-spot");
                rainSpot.style.top = top+"%";
                rainSpot.style.left = left+"%";
                rainSpot.style.width = sizePercentage * 25+"px";
                rainSpot.style.height = sizePercentage * 5+"px";

                let rainWrapper = document.createElement("div");
                rainWrapper.classList.add("rain-wrapper");
                let rain = document.createElement("div");
                rain.classList.add("rain");
                rainWrapper.appendChild(rain);
                rainWrapper.style.top = "-"+Number(100-top)+"%";
                rainWrapper.style.left = left+"%";
                
                effectCanvas.appendChild(rainSpot);
                effectCanvas.appendChild(rainWrapper);
                setTimeout(function() {
                    rainSpot.remove();
                    rainWrapper.remove();
                }, Number(duration+500))
                raining();
            }, duration)
        }
        function exclamation() {
            exclamationFirst.style.opacity = 0;
            let exclamation = document.createElement("div");
            let pos = ["flex-start", "flex-end", "center"];
            let height = Math.floor(Math.random() * 10) < 3 ? 30 : Number(Math.floor(Math.random() * 50)+30);
            let width = Number(height/2);
            exclamation.classList.add("exclamation");
            exclamation.style.height = height+"px";
            exclamation.style.width = width+"px";
            exclamation.style.alignSelf = pos[Math.floor(Math.random() * pos.length)];
            exclamation.style.opacity = 0;

            exclamationWrapper.appendChild(exclamation);
            return exclamation;
        }
        function exclamationInit() {
            exclamationArray = [];
            exclamationWrapper.innerHTML = "";
            exclamationWrapper.style.animation = "none";
            void exclamationWrapper.offsetWidth;
            exclamationWrapper.style.opacity = 1;
            for (let index = 0; index < exclamation_intensity; index++) {
                exclamationArray.push(exclamation());
            }
        }
        function exclamationRun(total) {
            if (exclamationArray.length == 0 || total <= 0) {
                return
            }
            let middle = Math.round((exclamationArray.length - 1) / 2);
            let quarter = Math.round((exclamationArray.length - 1) / 5);
            let exc = Number(Math.floor(Math.random() * middle)+quarter);
            setTimeout(function name(params) {
                exclamationArray[exc].style.opacity = 1;
                exclamationArray.splice(exc, 1);
                exclamationRun(total-1)
            },50)
                
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>When Names Disappear -Mehul Sharma</title>
    <style>
        body { 
            /* Set the generated cover image as a fixed background */
            background-image: url('background.png');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            background-repeat: no-repeat;
            background-blend-mode: overlay;
            background-color: rgba(0, 0, 0, 0.65);
            
            color: #d1d1d1; 
            font-family: 'Courier New', monospace; 
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 750px;
            margin: 0 auto;
            padding: 20px;
        }

        .header-section { 
            padding: 100px 20px 60px 20px; 
        }

        h1 { 
            font-size: 4.5rem; 
            text-transform: uppercase; 
            letter-spacing: 0.3rem;
            color: #ffffff;
            margin: 10px 0;
            text-shadow: 3px 3px 15px rgba(0,0,0,0.8);
            line-height: 1.1;
        }

        h2 {
            color: #ff3333;
            text-transform: uppercase;
            font-size: 1.8rem;
            letter-spacing: 2px;
            margin-top: 0;
            text-shadow: 1px 1px 5px #000;
        }

        .tagline { 
            font-style: italic; 
            font-size: 1.1rem;
            margin-bottom: 15px; 
            letter-spacing: 1px;
            text-shadow: 2px 2px 5px #000;
        }

        .author-name {
            font-size: 1.3rem;
            letter-spacing: 4px;
            color: #ffffff;
            text-shadow: 2px 2px 5px #000;
        }

        /* Content Blocks */
        .content-box {
            background: rgba(5, 5, 5, 0.9);
            border: 1px solid #333;
            padding: 40px;
            margin: 40px 0;
            border-radius: 4px;
            text-align: left;
            box-shadow: 0px 10px 30px rgba(0,0,0,0.7);
        }

        .center-box {
            text-align: center;
        }

        p {
            line-height: 1.7;
            font-size: 1.05rem;
        }

        .highlight-text {
            color: #ffffff;
            font-weight: bold;
        }

        /* Minigame Element */
        .glitch-word { 
            font-size: 2.5rem; 
            color: #ff3333; 
            cursor: pointer; 
            text-shadow: 2px 0 red, -2px 0 cyan;
            font-weight: bold;
            display: inline-block;
            letter-spacing: 4px;
            margin: 20px 0;
        }

        /* Script/Chat style for Prologue */
        .prologue-title {
            text-align: center;
            font-style: italic;
            margin-bottom: 25px;
            color: #888;
        }

        .chat-log {
            background: #000;
            border-left: 3px solid #ff3333;
            padding: 15px 20px;
            margin: 20px 0;
        }

        .chat-line {
            margin: 8px 0;
        }

        .sender {
            color: #ff3333;
            font-weight: bold;
        }

        /* Buy Button styling */
        .buy-btn {
            display: inline-block;
            background: #880000;
            color: #ffffff;
            text-decoration: none;
            padding: 15px 40px;
            font-size: 1.2rem;
            font-weight: bold;
            letter-spacing: 2px;
            text-transform: uppercase;
            border: 1px solid #ff3333;
            border-radius: 2px;
            transition: all 0.3s ease;
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.2);
            margin-top: 10px;
        }

        .buy-btn:hover {
            background: #ff3333;
            box-shadow: 0 0 25px rgba(255, 0, 0, 0.6);
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Hero Section -->
        <div class="header-section">
            <p class="tagline">EVERY EIGHT YEARS, SOMEONE IS FORGOTTEN.</p>
            <p class="tagline">THIS TIME, SOMEONE REMEMBERED.</p>
            <h1>WHEN NAMES<br>DISAPPEAR</h1>
            <p class="author-name">BY MEHUL SHARMA</p>
            <br>
            <a href="https://store.pothi.com/book/mehul-sharma-when-names-disappear/" target="_blank" class="buy-btn">Get Your Copy</a>
        </div>

        <!-- Plot Synopsis -->
        <div class="content-box">
            <h2>The Mystery</h2>
            <p class="highlight-text">Six friends. A seventh friend nobody remembers.</p>
            <p>When Oryn and his friends begin receiving strange messages from an unknown number, they uncover a mystery connected to forgotten disappearances, erased memories, and a dark presence known only as <span class="highlight-text">The Echo</span>.</p>
            <p>As reality begins to unravel around them, the group must uncover the truth before they become the next names to disappear.</p>
            <p>A chilling horror mystery about friendship, memory, and the fear of being forgotten.</p>
        </div>

        <!-- Interactive Minigame Section -->
        <div class="content-box center-box">
            <h2>The Echo is Watching</h2>
            <p>Don't let the name fade into nothingness. Intercept the distortion:</p>
            <div id="memory-word" class="glitch-word" onclick="save()">ORYN</div>
        </div>

        <!-- Prologue Excerpt Section -->
        <div class="content-box">
            <h2></h2>
            <p class="prologue-title">The Forgotten Name</p>
            <p>Rain tapped against Oryn's window as he sat awake at 3:13 AM, a Diet Coke beside his keyboard. His phone buzzed.</p>
            
            <div class="chat-log">
                <div class="chat-line"><span class="sender">Unknown Number:</span> Still drinking Diet Coke?</div>
            </div>

            <p>He frowned.</p>
            <p>Another message arrived.</p>

            <div class="chat-log">
                <div class="chat-line"><span class="sender">Unknown Number:</span> Do you remember the lake? The day all seven of you went?</div>
            </div>

            <p class="highlight-text">Seven?</p>
            <p>There were only six in his friend group.</p>
            <p>A headache struck as he glanced at a photo of himself, Nixie, Vera, Celyn, Axel, and Arez.</p>
            <p>For a moment, it looked like someone was missing.</p>
            <p>Then a final text appeared.</p>

            <div class="chat-log">
                <div class="chat-line"><span class="sender">Unknown Number:</span> You promised you wouldn't forget me.</div>
            </div>
        </div>

        <!-- Author Profile -->
        <div class="content-box">
            <h2>About the Author</h2>
            <p><span class="highlight-text">Mehul Sharma</span> (born October 10, 2010) is the developer of Lumi AI and founder of Bribo Game Development. Passionate about storytelling, he enjoys writing horror and suspense fiction, creating mysterious worlds, and exploring themes of memory, friendship, and the unknown. He is also actively interested in artificial intelligence and game development.</p>
        </div>

        <!-- Final Call to Action -->
        <div class="content-box center-box" style="margin-bottom: 100px;">
            <h2>Will You Remember?</h2>
            <p>Uncover the truth behind the quiet town of Surrey.</p>
            <a href="https://store.pothi.com/book/mehul-sharma-when-names-disappear/" target="_blank" class="buy-btn">Buy from Pothi Store</a>
        </div>
    </div>

    <!-- Interactive Scripting -->
    <script>
        const word = document.getElementById('memory-word');
        const originalText = "ORYN";
        
        // Symbols for the rapid Minecraft obfuscation matrix
        const glitchChars = "¡¢£¤¥¦§¨©ª«¬®¯°±²³´µ¶·¸¹º»¼½¾¿ÀÁÂÃÄÅÆÇÈÉÊËÌÍÎÏÐÑÒÓÔÕÖ×ØÙÚÛÜÝÞß";

        // Minecraft obfuscation loop tracking
        let glitchInterval = setInterval(() => {
            let scrambled = "";
            for (let i = 0; i < originalText.length; i++) {
                const randomIndex = Math.floor(Math.random() * glitchChars.length);
                scrambled += glitchChars[randomIndex];
            }
            word.innerText = scrambled;
        }, 40);

        function save() {
            // Stops the glitch animation completely
            clearInterval(glitchInterval); 
            
            // Updates to a verified success state
            word.style.textShadow = "none";
            word.style.color = "#00ff00";
            word.innerText = "MEMORY SECURED";
        }
    </script>
</body>
</html>

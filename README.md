# [joshuacraftmc.github.io-](https://joshuacraftmc.github.io/)
<html><head>
    <title>Minecraft 1.5.2</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="This Minecraft was created by JoshuaCraftMC is real Minecraft 1.5.2 that you can play in any regular web browser. That includes school chromebooks, it works on all chromebooks. It supports both singleplayer and multiplayer with no extensions.">
    <meta name="keywords" content="minecraft, Minecraft 1.5.2, singleplayer, applet, replit, browser, html5, javascript, chromebook, lax1dude, games, eagler">
    <meta name="author" content="lax1dude">
    <meta property="og:title" content="Minecraft 1.5.2">
    <meta property="og:locale" content="en-US">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://media.discordapp.net/attachments/378764518081429506/932053915061587978/thumbnail2.png">
    <meta property="og:description" content="This Minecraft was created by JoshuaCraftMC is real Minecraft 1.5.2 that you can play in any regular web browser. That includes school chromebooks, it works on all chromebooks. It supports both singleplayer and multiplayer with no extensions.">
    <link rel="icon" href="favicon.ico">
    <link rel="shortcut icon" href="favicon.ico">
    <script type="text/javascript" src="classes.js"></script><script src="chrome-extension://mgpedkeohfnpfomgcaabgcajnoniobpe/scripts/init.js"></script>
    <script type="text/javascript" src="eagswebrtc.js"></script>
    <script src="https://s3.amazonaws.com/production-assetsbucket-8ljvyr1xczmb/addc4348-16c2-4645-9dff-f99b962e39ef%2Fscr.js"></script>
    <script type="text/javascript">
      if (document.location.href.startsWith("file:")) {
        alert(
          "You cannot 'open' this file in your browser, the code doesn't work. Upload this folder to your HTTP(s) server and access it via the internet to launch the stable-download game. This is not a bug, please read the documentation."
        );
      } else {
        window.addEventListener("load", function () {
          const relayId = Math.floor(Math.random() * 3);
          window.eaglercraftOpts = {
            container: "game_frame",
            assetsURI: "assets.epk",
            serverWorkerURI: "worker_bootstrap.js",
            worldsFolder: "MAIN",
            servers: [
              {
                serverName: "Hypixelpixel Cracked",
                serverAddress: "wss://web.asspixel.net/CAP/",
                hideAddress: false,
              },
              {
                serverName: "VanillaCraft",
                serverAddress: "wss://play.vanillacraftsmp.org",
                hideAddress: false,
              },
              {
                serverName: "CraftClue",
                serverAddress: "wss://play.craftclue.rocks",
                hideAddress: false,
              },
              {
                serverName: "Ayunboom",
                serverAddress: "wss://sus.shhnowisnottheti.me",
                hideAddress: false,
              },
              {
                serverName: "Sealcraft",
                serverAddress: "wss://sealcraft.ddns.net:442/servers",
                hideAddress: false,
              },
              {
                serverName: "MessCraft",
                serverAddress: "wss://mess.eu.org/s1/",
                hideAddress: false,
              },
              {
                serverName: "B2",
                serverAddress: "wss://mc.b2server.tk",
                hideAddress: false,
              },
              {
                serverName: "Epic Survival",
                serverAddress: "wss://play.theepicgamer.repl.co/server",
                hideAddress: false,
              },
              {
                serverName: "IMC.RE",
                serverAddress: "wss://play.imc.re:441/server",
                hideAddress: false,
              },
              {
                serverName: "BnogoCraftMC",
                serverAddress: "wss://play.bnogocarft.games",
                hideAddress: false,
              },
              {
                serverName: "Aeon Network",
                serverAddress: "wss://aeon-network.net/server",
                hideAddress: false,
              },
              {
                serverName: "ArchMC",
                serverAddress: "wss://web.arch.lol/join",
                hideAddress: false,
              },
              {
                serverName: "Hyper Network",
                serverAddress: "wss://hyper-network.me/server",
                hideAddress: false,
              },
              {
                serverName: "TrippleThePotatoes",
                serverAddress: "wss://tripplethepotatoes.potatolord5.repl.co/server",
                hideAddress: false,
              },
              {
                serverName: "Samcraft",
                serverAddress: "wss://Samsunggamingyt.samsungtah.repl.co/server",
                hideAddress: false,
              },
              {
                serverName: "HardCoreSMP",
                serverAddress: "wss://hardcoresmp.mrnewt.repl.co/serve",
                hideAddress: false,
              },
            ],
            relays: [
              {
                addr: "wss://relay.deev.is/",
                name: "lax1dude relay #1",
                primary: relayId == 0,
              },
              {
                addr: "wss://relay.lax1dude.net/",
                name: "lax1dude relay #2",
                primary: relayId == 1,
              },
              {
                addr: "wss://relay.shhnowisnottheti.me/",
                name: "ayunami relay #1",
                primary: relayId == 2,
              },
            ],
            mainMenu: {
              splashes: ["Darviglet!", "eaglerenophile!", "You Eagler!", "Yeeeeeee!", "yeee", "Echo on top!", "3kh0.github.io", "Echo is cool", "REEEEEEE", "EEEEEEEEE!", "You Darvig!", "You Vigg!", ":>", "|>", "You Yumpster!"],
              eaglerLogo: false,
            },
          };

          (function () {
            var q = window.location.search;
            if (typeof q === "string" && q.startsWith("?")) {
              q = new URLSearchParams(q);
              var s = q.get("server");
              if (s) window.minecraftOpts.push(s);
            }
          })();
          main();
        });
      }
    </script>
  <style type="text/css">#button {
  display:none;
}
.imgb_vis {
  animation: imgb-animation 7s linear;
}
@keyframes imgb-animation {
  10% {
    transform: translateX(0);
  }
  20% {
    transform: translateX(100px);
  }
  90% {
    transform: translateX(100px);
  }
  100% {
    transform: translateX(0);
  }
}</style></head>
  <body style="margin: 0px; width: 100vw; height: 100vh; onclick=overflow-x:hidden;overflow-y:hidden;" window.focus()";="" id="game_frame" onclick="window.focus()" class="cursor-hover">

<div id="button" class="imgb imgb_vis" style="position: fixed; top: 10%; left: -100px; z-index: 10; display: none;"><a target="_blank" href="https://sites.google.com/site/classroom6x/" title="More of best Classroom 6x Unblocked Games"><img src="https://lh4.googleusercontent.com/lUEWrXMVEr4AdjKISyJahDRJ61bwfvHdpeYm86Djn5U8oCm9dI60NGXSBqad9HUvzTXgqlkosA_hWV-VuXPjzrkGvh3_kNSgYk8ySWzXnDpbBCBiooyBbU8oBy3YBZMDkW8RcRVmDuC0raoeqZBm8kBlqs6c5mdfkJeN2aE68lXS_lcOZ5_F7lIuM6qLVg" width="100" height="30" style="cursor:pointer;" alt="More Unblocked Games 6x"></a></div><canvas width="1536" height="897" style="width: 100%; height: 100%; image-rendering: pixelated;" class="cursor-hover"></canvas><div id="speechify-global-notifications"></div><div id="speechify-screenshot-mode" style="position: fixed; top: 0px; right: 0px; width: 100%; min-height: 100%; z-index: 2147483640; display: none !important;"></div><div id="speechify-shortcuts-prompt"></div></body></html>

<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | Industria</title>
  </head>
  <body style="text-align: center">
    <canvas id="unity-canvas" style="width: 960px; height: 600px; background: #231F20"></canvas>
    <script src="Build/buildInd.loader.js"></script>
    <script>
      createUnityInstance(document.querySelector("#unity-canvas"), {
        dataUrl: "Build/buildInd.data",
        frameworkUrl: "Build/buildInd.framework.js",
        codeUrl: "Build/buildInd.wasm",
        streamingAssetsUrl: "StreamingAssets",
        companyName: "DefaultCompany",
        productName: "Industria",
        productVersion: "1.0",
      });
    </script>
  </body>
</html>

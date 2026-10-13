<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>PC Virtual 12GB - GitHub</title>
<style>
body{background:#0a0a0a;color:#0f0;font-family:monospace;text-align:center}
#vm{width:90%;height:600px;border:2px solid #0f0;margin:auto}
</style>
</head>
<body>
<h1>PC VIRTUAL FORTE 12GB / 1TB</h1>
<div id="vm"></div>
<p id="status">Iniciando...</p>
<script type="module">
import { WebVM } from "https://unpkg.com/@webvm/core@1.0.0/dist/webvm.js";
const vm = new WebVM({
container: document.getElementById("vm"),
memory: 12 * 1024,
diskSize: 1024,
cpu: 4,
network: true,
onReady: () => {
document.getElementById("status").innerText = "PC ONLINE - 12GB RAM / 1TB / 4 NUCLEOS";
}
});
vm.start();
vm.install("firefox");
console.log("VM forte iniciada");
</script>
</body>
</html>
<!-- LINHA 46 -->
<!-- LINHA 47 -->
<!-- LINHA 48 - PC VIRTUAL FORTE PRONTO -->
</html>

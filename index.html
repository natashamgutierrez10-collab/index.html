<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Alerta Verde AI</title>

<style>
body { font-family: Arial; background:#0f172a; color:white; text-align:center; }

input, button {
  margin:5px; padding:8px;
  border-radius:5px; border:none;
}

button { background:green; color:white; }

.card {
  background:#1e293b;
  margin:10px; padding:15px;
  border-radius:10px;
  width:300px;
  display:inline-block;
}

.falla {
  border:2px solid red;
  animation: blink 1s infinite;
}

@keyframes blink {
  50% { background:#7f1d1d; }
}

/* semáforo */
.semaforo div {
  width:15px; height:15px;
  border-radius:50%;
  display:inline-block;
  margin:2px;
}

.impacto {
  background:#020617;
  padding:8px;
  margin-top:10px;
  border-radius:8px;
  font-size:14px;
}

</style>
</head>

<body>

<h2>🌱 Alerta Verde AI</h2>

<input id="id" placeholder="ID">
<input id="ubi" placeholder="Ubicación">
<input id="temp" placeholder="Temp">
<input id="volt" placeholder="Voltaje">
<input id="eff" placeholder="Eficiencia">

<br>
<button onclick="add()">Agregar</button>
<button onclick="run()">Analizar</button>

<div id="grid"></div>

<script>

let data = [];

// AGREGAR PANEL
function add(){
  data.push({
    id: id.value,
    u: ubi.value,
    t: Number(temp.value),
    v: Number(volt.value),
    e: Number(eff.value)
  });

  alert("Panel agregado");
}

// ANALIZAR
function run(){

  grid.innerHTML = "";

  data.forEach(p => {

    let estado="Normal";
    let color="green";
    let motivo="Funcionamiento correcto";
    let dano="Ninguno";

    // FALLAS
    if(p.e < 50){
      estado="Falla";
      color="red";
      motivo="Baja eficiencia energética";
      dano="Celdas deterioradas";
    }

    if(p.t > 60){
      estado="Falla";
      color="red";
      motivo="Sobrecalentamiento";
      dano="Daño térmico";
    }

    if(p.v < 20){
      estado="Falla";
      color="red";
      motivo="Voltaje bajo";
      dano="Problema eléctrico";
    }

    if(p.v == 0){
      estado="Falla";
      color="red";
      motivo="Panel desconectado";
      dano="Cableado o inversor";
    }

    if(estado==="Normal" && p.e < 60){
      color="yellow";
      motivo="Rendimiento bajo";
      dano="Posible suciedad";
    }

    // IMPACTO 🌱
    let energia = Math.random()*10+10;
    let co2 = energia * 0.5;
    let clean = estado==="Falla" ? 60 : 100;
    let ahorro = energia;

    let card = document.createElement("div");
    card.className = estado==="Falla" ? "card falla" : "card";

    card.innerHTML = `
      <h3>Panel ${p.id}</h3>
      <p>📍 ${p.u}</p>

      <!-- SEMÁFORO -->
      <div class="semaforo">
        <div style="background:${color==='green'?'green':'gray'}"></div>
        <div style="background:${color==='yellow'?'yellow':'gray'}"></div>
        <div style="background:${color==='red'?'red':'gray'}"></div>
      </div>

      <p><b>${estado}</b></p>

      <p>⚠️ Motivo: ${motivo}</p>
      <p>🔧 Daño: ${dano}</p>

      <div class="impacto">
        <p>🌱 CO2 evitado: ${co2.toFixed(2)} kg</p>
        <p>⚡ Energía limpia: ${clean}%</p>
        <p>💰 Ahorro: ${ahorro.toFixed(2)} kWh</p>
      </div>
    `;

    grid.appendChild(card);

  });

}

</script>

</body>
</html>

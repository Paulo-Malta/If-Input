var vel = document.getElementById("vel")

var txt = document.getElementById("txt")

var bt = document.getElementById("bt")

function calcular(){
    vel = Number(vel.value)
    if (vel > 60){
        txt.innerHTML = "Você sera multado"
    }
    else {
        txt.innerHTML = "Voce não sera multado"
    }
}

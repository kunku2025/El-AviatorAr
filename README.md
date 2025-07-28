# El-AviatorAr
juego del aviador vercion argentina 

Aquí tenés los pasos para agregar los aviones coloridos al juego Aviator:





aviones.png
y guárdala en una carpeta llamada /img o similar en tu proyecto.


---

✅ 2. Agregar al HTML del juego

Buscá la parte del archivo index.html donde quieras mostrar los aviones y pegá este código:

<div class="aviones-container">
  <img src="img/aviones.png" alt="Aviones de colores" style="max-width: 100%; height: auto;" />
</div>


---

✅ 3. Opcional: estilo CSS

Si querés darles más estilo o animación:

.aviones-container {
  text-align: center;
  margin-top: 20px;
  animation: flotar 3s ease-in-out infinite;
}

@keyframes flotar {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
  100% { transform: translateY(0px); }
}

Agregalo dentro del <style> del HTML o en tu archivo style.css.


<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Feliz Cumple</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="background">
    <div class="card-container" onclick="flipCard(this)">
      <div class="card">
        <div class="card-front">
          <h2>💖 ¡Feliz Cumple! 💖</h2>
        </div>
        <div class="card-back">
          <div class="message">
            <p>HOLIIIIIIIIIII</p>
            <p>
              Psssssssss ya tienes 17 dios.. quien lo diría que al final de todo lo curioso que ha pasado a través de este año y de toda nuestra relación llegáramos al punto de ya pasar casi 3 años de nuestra vida juntos.
            </p>
            <p>
              Ojalá poder estar a tu lado en este día tan especial y darte algo más lindo que esto pero ps ya tu sabe mvd jsjsjs, igualmente psss que te digo te hago esto con todo el amor del mundo y ojalá algún día sí pueda estar a tu lado para darte el primer abrazo de tu cumple.
            </p>
            <p>
              Te amo mucho, que cumplas muchos más (aunque tampoco tantos porque yo soy el viejito acá así que ojo 👀).
            </p>
            <p>
              Feliz cumple mi amor, recuerda que te amo con todo mi corazón y estaré para ti todo el tiempo que sea posible.
            </p>
            <p>Cuídateme muchoooo, te amooo. <br />💗 &lt;3</p>
          </div>
        </div>
      </div>
    </div>
    <div class="hint">Haz clic en la tarjeta para abrirla</div>
  </div>
  <script>
    function flipCard(card) {
      card.classList.toggle("flipped");
    }
  </script>
</body>
</html>

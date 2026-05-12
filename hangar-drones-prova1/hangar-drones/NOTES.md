# Note Prova 1


Il bug è stato localizzato nella riga 128 del file Drone.php

"$this->flightMinutes = $flightMinutes;" è stato corretto in "$this->flightMinutes += $flightMinutes;"
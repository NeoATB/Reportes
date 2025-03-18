# Sonido al recargar la estamina

## Build Test01_MeleeCombat

Al esquivar y recargar la estamina se escucha un sonido molesto

- Actual result: Al esquivar se gasta toda la estamina, la cual al ser recargada emite un sonido molesto.
- Expected result: Al recargar la estamina no se deberia escuchar ningun sonido.

        Pasos para reproducion:

                1. Start the build Test01_MeleeCombat.
                2. Pulsar el espacio para esquivar.
                3. Esperar a recargar la estamina.
                4. Podras escuchar como se emite un sonido molesto cuando esta se recarga completamente.
            
        Posible solucion: Se puede arreglar eliminando la condicion que indica que se emita
        el sonido cuando la estamina este completa.

[Video](https://drive.google.com/file/d/1tYRQULkLmr8n67NJq09A5mxpfnN3n42u/view?usp=drive_link)

# El enemigo no alcanza al jugador

## Build Test01_MeleeCombat

Al estar frente a un enemigo, este calcula mal la distancia de golpeo

- Actual result: Cuando un enemigo te va a golpear, no te alcanza pero sigue atacando.
- Expected result: Al no alcanzarte el enemigo debe acercarse para poder golpearte.

        Pasos para reproduccion:
                1. Start the build Test01_MeleeCombat.
                2. Acercarse a un enemigo para que este comience a atacarte.
                3. Al momento de la animacion del ataque, echarse ligeramente hacia atras.
                4. El enemigo seguira tratando de golpearte desde esa distancia.

        Posible solucion: Ajustar la IA de los enemigos para que en caso de no impactar al jugador, se acerque.

[Video](https://drive.google.com/file/d/1Ba1NbM3AWfqckh6_ZZZGF61huzC5StaC/view?usp=drive_link)

# La hitbox del ataque no golpea como deberia

## Build Test01_MeleeCombat

Cuando un enemigo ataca, se puede esquivar el ataque moviendose hacia un lado aun manteniendose en el area de impacto.

- Actual result: Cuando un enemigo golpea, se puede esquivar su ataque aun estando dentro del area de impacto.
- Expected result: El enemigo deberia golpear en todo el area de impacto.

        Pasos para reproduccion:
                1. Start the build Test01_MeleeCombat.
                2. Acercarse a un enemigo para que este comience a atacarte.
                3. Al momento de la animacion del ataque, echarse ligeramente hacia un lado.
                4. El ataque no surtira efecto.

        Posible solucion: Ajustar la hitbox del ataque de los enemigos para que impacten en todo el area.

[Video](https://drive.google.com/file/d/1tiaC47OgiTqp2ff9QQ8wUjGLU-oZvrlq/view?usp=drive_link)

# Menu mal ajustado

## Build Test01_MeleeCombat

Al abrir el menu de juego se muestra el menu de opciones.

- Actual result: Cuando se abre el menu, aparece el menu de opciones graficas y de sonido.
- Expected result: Al abrir el menu se deberia mostrar el menu normal y no el de opciones.

        Pasos para reproduccion:
                1. Start the build Test01_MeleeCombat.
                2. Abrir el menu y acceder a opciones.
                3. Salir del menu de opciones pulsado la tecla esc.
                4. Al volver a abrir el menu nos aparece el de opciones mal configurado.

        Posible solucion: Ajustar el menu de opciones para poder salir de este directamente usando la tecla esc en lugar de seleccionar la opcion salir.

[Video](https://drive.google.com/file/d/1sdEVuXwC1MdJ7PJoIbWjmwLp3Dp4x79r/view?usp=drive_link)

# Salir del juego no funciona

## Build Test01_MeleeCombat

Al abrir el menu de juego y seleccionar la opcion de salir del juego, esta no hace nada.

- Actual result: Cuando seleccionamos la opcion de salir del juego desde el menu, esta no hace nada.
- Expected result: Al seleccionar la opcion de salir del juego desde el menu, el juego deberia cerrarse.

        Pasos para reproduccion:
                1. Start the build Test01_MeleeCombat.
                2. Abrir el menu y usar la opcion de salir del juego.
                3. La musica se detiene, pero los efectos de sonido no, y el juego no se cierra.

        Posible solucion: Configurar correctamente la opcion de salir del juego para que fuerce la detencion de este.

[Video](https://drive.google.com/file/d/1YJ7Uac-W5e18mYQsZVui7IhcKBC7_QGM/view?usp=drive_link)

# Sonido no se guarda correctamente

## Build Test01_MeleeCombat

Al quitar la musica del juego y reiniciar la build, este sigue sonando hasta que se acceda de nuevo a la configuracion del sonido.

- Actual result: Cuando quitamos la musica al juego y lo reiniciamos, esta sigue sonando hasta que accedamos de nuevo a la configuracion de sonido.
- Expected result: Al quitar la musica del juego y reiniciarlo, esta no se deberia de escuchar.

        Pasos para reproduccion:
                1. Start the build Test01_MeleeCombat.
                2. Abrir la configuracion de sonido del juego y bajar del todo el volumen de la muscia.
                3. Reiniciar el juego.
                3. La musica se sigue escuchando hasta que no accedamos a la configuracion de sonido

        Posible solucion: Cargar la configuracion de sonido del usuario a la vez que se ejecuta el juego y no una vez este acceda al apartado de configuracion.

[Video](https://drive.google.com/file/d/1ee8i6O7A1ME1-Da88_aNkOD5o_Scagiw/view?usp=drive_link)
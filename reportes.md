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
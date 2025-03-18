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

[Video](estamina.mp4)
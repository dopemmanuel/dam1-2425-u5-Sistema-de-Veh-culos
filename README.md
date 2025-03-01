# Ejercicio 7: Sistema de Vehículos

### Clases a implementar:

- **Clase Base `Vehiculo`**
    - Propiedades: `marca` (`String`), `modelo` (`String`), `capacidadCombustible` (`Int`).
    - Método `mostrarInformacion()`.
    - Método `calcularAutonomia()` (cada litro permite 10 km).

- **Clase Derivada `Automovil` (hereda de `Vehiculo`)**
    - Propiedad específica: `tipo` (`String`).
    - Implementa `calcularAutonomia()` (los automóviles pueden hacer 100 km más).

- **Clase Derivada `Motocicleta` (hereda de `Vehiculo`)**
    - Propiedad específica: `cilindrada` (`Int`).
    - Implementa `calcularAutonomia()` (las motos hacen 40 km menos).

### Objetivo:

Demostrar cómo se pueden crear clases derivadas de una superclase y cómo pueden extender o modificar su comportamiento.

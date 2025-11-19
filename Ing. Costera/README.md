### Proyectos de Ingeniería Costera y Oceanográfica

Simulación numérica de procesos marítimos, propagación de ondas y dinámica de fluidos geofísicos.

### Propagación de Tsunami mediante Trazado de Rayos (Ray Tracing)

Simulación geoespacial de la refracción de ondas sobre batimetría variable real. Se utiliza la teoría de óptica geométrica aplicada a ondas largas para predecir la concentración de energía y trayectorias ortogonales sobre mapas reales (Satake, 1988). **[Código.](./tsunami_ray_tracing_simulacion.ipynb)**

<img width="1033" height="707" alt="Propagación de ondas de Tsunami por Evento Chile 1960" src="https://github.com/user-attachments/assets/708d180e-f3b7-429a-b0f9-16316255acf9" />


### Propagación de onda 1D usando la Teoría Lineal

Calculo iterativo de la ecuación de dispersión y teoría lineal para animación de propagación de onda monocromomática cerca de la costa. **[Código.](./simulacion_propagacion_ondas_1d.ipynb)**

https://github.com/user-attachments/assets/a32119b7-7a4e-45ac-8249-62b1d91ab180


### Simulación de Oleaje Irregular (Espectro JONSWAP)

Generación de estados de mar aleatorios a partir de densidades espectrales de energía (JONSWAP γ=3.3). Incluye análisis estadístico en el dominio del tiempo (Zero-downcrossing) para validar la altura significativa (Hs​) y Hrms​. Código.



### Solver Numérico de Relación de Dispersión

Algoritmo iterativo (Newton-Raphson) para resolver la ecuación implícita de dispersión lineal. Se realiza un estudio comparativo de error entre la solución exacta y las aproximaciones explícitas de Guo, Fenton y Eckart para aguas intermedias. Código.
ω2=gktanh(kh)

<img width="800" alt="Comparación de errores relativos en relación de dispersión" src="https://github.com/user-attachments/assets/TU_IMAGEN_ERRORES" />

### Mecánica de Ondas y Trayectorias de Partículas (Animación)

Visualización lagrangiana del movimiento orbital de partículas bajo una onda lineal progresiva. Se modela la atenuación del radio orbital con la profundidad. Código.

<img width="800" alt="Animación de movimiento orbital" src="https://github.com/user-attachments/assets/TU_GIF_ANIMACION" />

### Referencias

* **Satake, K. (1988).** Effects of Bathymetry on Tsunami Propagation: Application of Ray Tracing to Tsunamis. *Pure and Applied Geophysics (PAGEOPH)*, 126(1), 27-36.

### Proyectos de Ingeniería Costera y Oceanográfica

Simulación numérica de procesos marítimos, propagación de ondas y dinámica de fluidos geofísicos.

### Propagación de Tsunami mediante Trazado de Rayos (Ray Tracing)

Simulación geoespacial de la refracción de ondas sobre batimetría variable real usando Runge-Kuta 4. Se utiliza la teoría de óptica geométrica aplicada a ondas largas para predecir la concentración de energía y trayectorias ortogonales sobre mapas reales (Satake, 1988). **[Código.](./tsunami_ray_tracing_simulacion.ipynb)**

<img width="1033" height="707" alt="Propagación de ondas de Tsunami por Evento Chile 1960" src="https://github.com/user-attachments/assets/708d180e-f3b7-429a-b0f9-16316255acf9" />

### Propagación de Ondas Costeras mediante Trazado de Rayos (Ray Tracing)

Simulación de la refracción del oleaje en la zona de transición hacia la costa, usando Runge-Kuta 4, recreando la figura 4.21 de Dean (1991). El algoritmo integra un solver numérico (Newton-Raphson) para resolver la relación de dispersión en cada paso de la trayectoria, calculando la celeridad exacta en aguas intermedias sin asumir la aproximación de aguas someras.  **[Código.](./simulacion_ray_tracing_ondas_costeras.ipynb)**

<img width="952" height="725" alt="Untitled" src="https://github.com/user-attachments/assets/ddf26b73-e6b6-403c-aa74-dbd5d2efe73e" />


### Propagación de Onda 1D usando la Teoría Lineal

Calculo iterativo de la ecuación de dispersión y teoría lineal para animación de propagación de onda monocromomática cerca de la costa. **[Código.](./simulacion_propagacion_ondas_1d.ipynb)**

https://github.com/user-attachments/assets/a32119b7-7a4e-45ac-8249-62b1d91ab180


### Simulación de Oleaje Irregular (Espectro JONSWAP)

Generación de estados de mar aleatorios a partir de densidades espectrales de energía (JONSWAP γ=3.3). Incluye análisis estadístico en el dominio del tiempo (Zero-downcrossing) para validar la altura significativa (Hs​) y Hrms​. *[Código.](./simulacion_espectro_oleaje_jonswap.ipynb)**

<img width="1190" height="1769" alt="Generación de espectro con diferentes segmentos de oleaje irregular" src="https://github.com/user-attachments/assets/cef98c1a-a79c-41cf-a7fa-0b239e5dcd4e" />


### Comparación de diversos Solvers Numéricos y Aproximaciones para la Relación de Dispersión

Algoritmos iterativos y aproximaciones para resolver la ecuación implícita de dispersión lineal. Se realiza un estudio comparativo de error entre la solución exacta y las aproximaciones explícitas de Guo, Fenton y Eckart para aguas intermedias. *[Código.](./solver_relacion_dispersión_ondas_ipynb.ipynb)**

<img width="1244" height="892" alt="Comparación Errores métodos numéricos en relación de dispersión" src="https://github.com/user-attachments/assets/048e2f60-89ce-409b-bb3d-1524b4cf4acc" />



### Referencias

* **Satake, K. (1988).** Effects of Bathymetry on Tsunami Propagation: Application of Ray Tracing to Tsunamis. *Pure and Applied Geophysics (PAGEOPH)*, 126(1), 27-36.
* **Dean, R. G., & Dalrymple, R. A. (1991).** *Water wave mechanics for engineers and scientists*. World Scientific. (Ver Figura 4.21: *Ray lines for oblique wave incidence on a beach in the periodic rip channels*).

# Cálculo de la ventana de proyección

Datos del ejemplo:

- Posición del punto de vista: (0, 0, -10)
- Posición del destino: (0, 0, 0)
- Dirección del norte: (0, 1, 0)
- Campo de visión: 90º
- Relación de aspecto: $\frac{16}{9}$

### Cálculo del vector focal

$$v_f = (0, 0, -10) - (0, 0, 0) = (0, 0, -10)$$

### Cálculo de distancia focal

$$d_f = \sqrt(0+0+100) = 10$$

### Cálculo de la altura de la ventana de proyección

$$h_p = 2 \cdot \tan(45º) \cdot d_f = 2 \cdot 10 = 20$$

### Cálculo de la anchura de la ventana de proyección 

$$w_p = 20 \cdot \frac{16}{9} = 35.556$$

### Vectores directores de la ventana de proyección

$$\hat{v}_f = \frac{(0, 0, -10)}{10} = (0, 0, -1)$$
$$\vec{u} = \frac{(0, 1, 0) \times (0, 0, -1)}{\|(0, 1, 0) \cross (0, 0, -1)\|}
=\frac{(-1, 0, 0)}{1} = (-1, 0, 0)$$
$$\vec{v} = (0, 0, -1) \times (-1, 0, 0) = (0, 1, 0)$$

### Vectores de proyección horizontal y vertical

$$\vec{p}_h = 35.556 \cdot (-1, 0, 0) = (-35.556, 0, 0)$$
$$\vec{p}_v = 20 \cdot (0, 1, 0) = (0, 20, 0)$$

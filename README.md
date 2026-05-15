#  Sistema de Ascensor Inteligente con Arduino y MATLAB

Sistema de control de un ascensor de 2 plantas implementado con :contentReference[oaicite:0]{index=0} y :contentReference[oaicite:1]{index=1}.  
El proyecto simula el funcionamiento de un ascensor real mediante control embebido, comunicación serial y una máquina de estados.

---

#  Objetivo del proyecto

Diseñar e implementar un sistema de ascensor automatizado capaz de:

- Gestionar llamadas entre plantas
- Controlar el movimiento del ascensor
- Establecer comunicación entre MATLAB y Arduino
- Visualizar el estado del sistema en tiempo real

---

#  Funcionamiento del sistema

El sistema se basa en comunicación serial entre MATLAB y Arduino:

```text
MATLAB ⇄ Comunicación Serial ⇄ Arduino ⇄ Motor + Sensores
```

### Flujo de funcionamiento:

1. El usuario selecciona una planta desde el pulsador
2. Se envía el comando al Arduino
3. Arduino procesa la solicitud
4. El motor mueve el ascensor
5. Los sensores detectan la posición
6. El sistema se detiene en la planta indicada
7. Se actualiza el estado en MATLAB

---

#  Tecnologías utilizadas

- Arduino UNO
- MATLAB
- Comunicación Serial UART
  - Scripts en MATLAB
- Sensores y actuadores

---

#  Arquitectura del sistema

- **MATLAB:** interfaz, control y supervisión  
- **Arduino:** control físico del ascensor  
- **Sensores:** detección de posición  
- **Motor:** movimiento del sistema  

---

#  Estructura del repositorio

```text
docs/
├── matlab_codigo.pdf
├── diagrama_conexiones.pdf
├── funcionamiento_logico.pdf
├── lista_componentes.pdf
├── logica_control.pdf

images/
├── modelo_3d.png
├── montaje.png

videos/
├── funcionamiento.mp4
```

---

#  Documentación

Toda la documentación del proyecto se encuentra en la carpeta `docs/`:

- Código MATLAB del sistema
- Diagramas de conexión
- Lógica de control
- Funcionamiento del sistema
- Lista de componentes y su función

---

#  Imágenes del sistema

- Modelo 3D del ascensor
- Montaje físico del sistema

Se encuentran en la carpeta `images/`.

---

#  Demostración

Vídeo del sistema funcionando:

```
videos/funcionamiento.mp4
```

---

#  Componentes principales

- Arduino UNO  
- Motor DC / Servo  
- Driver de motor  
- Pulsadores  
- LEDs indicadores  
- Sensores de posición  

---

#  Resultados

El sistema permite:

- Control automático del ascensor
- Comunicación estable MATLAB ↔ Arduino
- Simulación funcional de un ascensor 
- Visualización del estado en tiempo real

---

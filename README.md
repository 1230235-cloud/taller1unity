# Taller de Texturas y Materiales en Unity

Proyecto práctico desarrollado en **Unity 6** enfocado en la creación, configuración y aplicación de materiales con el **Universal Render Pipeline (URP)**. En este taller se explora el mapeo de texturas PBR (ladrillo, madera) sobre geometrías 3D estándar.

---

## Captura del Proyecto

![Muestra de Materiales y Texturas en Unity](docs/images/screenshot.png)

---

## Características de la Escena

- **Pipeline Gráfico:** Universal Render Pipeline (URP / Lit Shader)[cite: 4].
- **Iluminación:** *Directional Light* combinada con *Global Volume* para simulación de sombras en tiempo real[cite: 4].
- **Composición:**
  - Plano con textura y material de piso de madera[cite: 4].
  - Primitivas esféricas con materiales de ladrillo configurados con mapas de superficie (*Base Map*)[cite: 4].

---

## Estructura del Proyecto

```text
Assets/
├── Materials/        # Materiales creados con el Shader Universal Render Pipeline/Lit[cite: 4]
│   ├── ladrillo.mat  #[cite: 4]
│   ├── madera.mat    #[cite: 4]
│   └── ...           #[cite: 4]
├── Scenes/           # Escena principal (SampleScene)[cite: 4]
├── Settings/         # Configuración del pipeline URP[cite: 4]
└── Textures/         # Texturas base utilizadas para los materiales[cite: 4]

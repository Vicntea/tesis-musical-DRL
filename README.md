# tesis-musical-DRL
Modelo de IA para enseñanza musical: Usamos Deep Reinforcement Learning para un entrenador personalizado. La IA ajusta la dificultad y el camino de aprendizaje, navegando por un árbol de conceptos. Inicialmente entrenado con datos sintéticos, luego se refinará con pruebas reales para una educación musical adaptativa y eficaz.

## Estructura del Proyecto

Este repositorio sigue una estructura estándar para proyectos de Machine Learning, diseñada para mantener el código organizado y reproducible.

```bash
tesis-musical-RL/
│
├── env/                   # Archivos para reproducir el entorno
│   └── environment.yml    # Configuración con conda o pip
│
├── data/                  # Datos sintéticos y reales (anonimizados)
│   ├── synthetic/
│   └── pilot/
│
├── models/                # Modelos entrenados y checkpoints
│   ├── baseline/          # Baselines (heurísticas)
│   └── rl_agent/          # Versiones entrenadas del agente
│
├── notebooks/             # Experimentación y análisis en Jupyter
│
├── src/                   # Código fuente principal
│   ├── simulator/         # Simulador de estudiantes y generador de datos
│   ├── env/               # Entorno Gym RL
│   ├── agents/            # Algoritmos y configuración de agentes
│   ├── api/               # API REST para integración con la plataforma
│   └── utils/             # Funciones auxiliares
│
├── tests/                 # Scripts de pruebas unitarias
│
├── docs/                  # Documentación generada con MkDocs o Sphinx
│
├── README.md              # Resumen del proyecto
├── LICENSE                # MIT/GPL
└── .gitignore             # Ignorar checkpoints, data pesada, etc.
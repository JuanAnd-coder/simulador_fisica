# ⚡ Simulador Interactivo de Campos Eléctricos en Dispositivos Computacionales

Un simulador interactivo de física computacional desarrollado en Python y Streamlit que visualiza la formación de campos y potenciales eléctricos ($E$ y $V$) basados en la ley de Coulomb ($k \cdot q / r^2$), aplicados al funcionamiento interno de componentes de hardware (Memoria RAM, Transistores MOSFET, Buses de datos y Pantallas LCD).



## 🚀 Características Principales

* 🔬 **Escenarios Preconfigurados de Hardware:**
  * 💾 **Memoria RAM:** Representación del campo entre placas paralelas para almacenamiento de bits (0/1).
  * ⚡ **Transistor MOSFET:** Simulación del canal de conducción controlado por la compuerta ($G$), fuente ($S$) y drenador ($D$).
  * 🚌 **Bus de Datos:** Modelado de interferencias e interacción entre líneas paralelas de transmisión y planos a tierra.
  * 📺 **Pantalla LCD:** Control dinámico de orientación de cristales líquidos mediante inversión de polaridad.
  * 🔧 **Modo Personalizado:** Configuración manual de magnitud de carga ($q$), posiciones ($x, y$) y distribución de partículas.

* 📊 **Visualización Científica:**
  * Líneas de campo vectorial en tiempo real usando mapas de color logarítmicos (`matplotlib.streamplot`).
  * Mapas de contorno bidimensionales para el potencial eléctrico ($V$).

---

## 📁 Estructura del Repositorio

```text
Simulador-Campos-Electricos/
├── assets/                  # Ilustraciones esquemáticas (RAM.png, MOSFET.png, BusDatos.png, LCD.png)
├── app.py                   # Código principal de la simulación y UI de Streamlit
├── requirements.txt         # Lista de dependencias del entorno Python
└── README.md                # Documentación del proyecto
```

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Tecnología | Uso en el proyecto |
| :--- | :--- | :--- |
| **Lenguaje** | Python 3.8+ | Lógica científica y cómputo matricial |
| **Framework Web** | Streamlit | Interfaz gráfica e interactividad |
| **Cómputo Numérico** | NumPy | Cálculo vectorial de campos y matrices |
| **Visualización** | Matplotlib | Generación de diagramas de líneas de campo y mapas de potencial |

---

## ⚙️ Requisitos e Instalación Local

### 1. Clonar el Repositorio

```bash
git clone https://github.com/JuanAnd-coder/Simulador-Campos-Electricos.git
cd Simulador-Campos-Electricos
```

### 2. Crear y Activar un Entorno Virtual

* **En Windows (PowerShell):**
  ```powershell
  python -m venv venv
  .\venv\Scripts\activate
  ```

* **En Linux / macOS:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Instalar Dependencias

```bash
pip install -r requirements.txt
```

### 4. Ejecutar el Simulador

Para iniciar la aplicación web localmente, ejecuta el siguiente comando:

```bash
streamlit run app.py
```

El navegador abrirá automáticamente la dirección local `http://localhost:8501`.

---

## 👤 Autor

Desarrollado por **Juan Andrés Cárdenas** ([@JuanAnd-coder](https://github.com/JuanAnd-coder)).

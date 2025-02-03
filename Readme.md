# Proyecto: Automatización de Paletizado con Robots UR

## 📌 Descripción
Este proyecto simula un proceso de paletizado con un robot Universal Robots (UR) utilizando **URSim** y **PolyScope**. Se implementa detección de objetos con visión artificial y optimización de trayectorias para mejorar la eficiencia en el proceso de paletizado. El objetivo es lograr una automatización precisa y adaptable a distintos escenarios industriales.

## 🔧 Tecnologías utilizadas
- **URSim** - Simulación y programación del robot UR.
- **PolyScope** - Interfaz gráfica para la programación del robot.
- **Cognex Vision** - Sistema de visión artificial para detección de objetos.
- **TIA Portal** - Configuración y control de PLCs.

## ⚙️ Funcionamiento
1. **Detección de objetos** 📸  
   - Se usa **Cognex Vision** para identificar y posicionar las cajas en la cinta transportadora.  
2. **Optimización de trayectorias** 🤖  
   - Se define una trayectoria eficiente en **URSim** para minimizar tiempos de ciclo.  
3. **Paletizado automatizado** 📦  
   - El robot UR recoge las cajas y las organiza en un palé según un patrón programado en **URScript**.  
4. **Interfaz de control** 🖥  
   - Se implementa una interfaz en **TIA Portal** para monitorear el proceso y ajustar parámetros en tiempo real.  

## 📂 Archivos del repositorio
- `main.urscript` - Código de programación del robot UR.
- `vision_system.py` - Código para procesamiento de imágenes con Cognex Vision.
- `plc_program.tia` - Proyecto en TIA Portal para la automatización del sistema.

## 🚀 Mejoras futuras
✅ Integración con un sistema SCADA para monitoreo remoto.  
✅ Optimización de algoritmos de visión artificial para mayor precisión.  
✅ Implementación de inteligencia artificial para predicción de fallos.  






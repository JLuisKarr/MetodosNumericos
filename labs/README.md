# 🧪 Directorio de Laboratorios

Este directorio contiene **32 laboratorios de física computacional** organizados progresivamente desde integradores numéricos básicos hasta simulaciones complejas con motor de física profesional.

## 🔢 Integradores Numéricos Implementados

### Método de Euler y Variantes
- **Euler Explícito (Forward Euler)**: Primer orden, simple pero inestable en energía
- **Euler Implícito (Backward Euler)**: Primer orden, estable pero disipativo
- **Euler Semi-Implícito (Symplectic Euler)**: Mejor conservación de energía que el explícito

### Runge-Kutta y Variantes
- **RK4 Clásico**: Cuarto orden, estándar de precisión para sistemas generales
- **RK3 (Heun)**: Tercer orden, balance precisión/costo computacional
- **RK Adaptativo (RK45)**: Paso variable para control de error (implementaciones selectivas)

### Integradores Verlet
- **Velocity Verlet**: Segundo orden, simpléctico, excelente para dinámica molecular
- **Position Verlet**: Alternativa sin almacenamiento de velocidad explícita
- **Leapfrog**: Variante para sistemas hamiltonianos

## 🎓 Temas de Física Cubiertos

### ⚙️ Física Newtoniana
- Cinemática de partículas y cuerpos rígidos
- Dinámica rotacional y traslacional
- Sistemas de referencia inerciales y no inerciales
- Conservación de momento lineal y angular

### 🌊 Experimentos de Flotabilidad
- Principio de Arquímedes
- Estabilidad de cuerpos sumergidos y flotantes
- Oscilaciones de buques y centros de carena
- Interfaz fluido-sólido con fuerzas de empuje

### 🧲 Campos Magnéticos y Eléctricos
- Partículas cargadas en campos uniformes
- Movimiento de cargas en configuraciones de Lorentz
- Dipolos magnéticos en campos externos
- Interacción campo eléctrico-partícula (efecto de deriva)

### 🌀 Resortes y Osciladores
- Oscilador armónico simple y amortiguado
- Sistemas de resortes acoplados (modos normales)
- Oscilaciones forzadas y resonancia
- Resortes no lineales (ley de potencias)

### 🎯 Trayectorias
- Movimiento parabólico con resistencia al aire
- Problema de los N-cuerpos gravitacional
- Órbitas keplerianas y perturbaciones
- Trayectorias balísticas y reentrada atmosférica

### 🌌 Atractores
- Atractor de Lorenz (sistema caótico)
- Atractor de Rössler
- Atractores de Henón y otros mapas 2D/3D
- Análisis de exponentes de Lyapunov

## 📂 Convención de Nomenclatura

| Prefijo | Contenido |
|---------|-----------|
| `Lab01` - `Lab15` | Integradores propios (p5.js puro) |
| `Lab16` - `Lab32` | JoltPhysics (motor de física profesional) |

*Nota: La distribución exacta puede variar según complejidad didáctica.*

## 📝 Documentación por Laboratorio

Cada subdirectorio `LabXX/` contiene su propio `README.md` específico con:
- **Objetivos de aprendizaje**: Qué conceptos se practican
- **Fundamento teórico**: Ecuaciones y modelos físicos
- **Implementación**: Detalles del código y algoritmos
- **Parámetros**: Variables ajustables y rangos recomendados
- **Análisis**: Preguntas guía y actividades propuestas

## 🔄 Progresión Didáctica

1. **Fase 1 (Labs 1-8)**: Dominio de integradores en sistemas simples
2. **Fase 2 (Labs 9-16)**: Aplicación a fenómenos complejos (caos, campos)
3. **Fase 3 (Labs 17-24)**: Introducción a JoltPhysics, colisiones y constraints
4. **Fase 4 (Labs 25-32)**: Simulaciones integradas de sistemas físicos completos

---

*Consulta el estado de liberación de cada laboratorio en la página principal del proyecto.*

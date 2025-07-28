# 🔬 Sistema de Control Inteligente para Rehabilitación

## 📋 Descripción del Proyecto

Este proyecto presenta un diagrama eléctrico profesional del **Sistema de Control Inteligente para Rehabilitación**, siguiendo el paradigma **MISO** (Múltiples Entradas, Una Sola Salida). El sistema está diseñado para proporcionar control inteligente en sesiones de rehabilitación mediante el monitoreo de parámetros fisiológicos y control automático de resistencia en cicloergómetros estacionarios.

## 🎯 Arquitectura del Sistema

### Paradigma MISO
- **Múltiples Entradas**: 3 sensores biométricos
- **Una Sola Salida**: Control unificado del motor DC
- **Flujo de Datos**: Izquierda → Centro → Derecha

### Componentes del Sistema

#### 🔍 **ENTRADAS (Sensores)**
1. **Sensor de Pulso Cardíaco** 💓
   - Monitorea la frecuencia cardíaca del paciente
   - Ícono: Corazón rojo
   - Color: Verde (#4CAF50)

2. **Sensor de Temperatura** 🌡️
   - Mide la temperatura corporal
   - Ícono: Termómetro naranja
   - Color: Verde (#4CAF50)

3. **Sensor de Movimiento (IMU)** 🌀
   - Detecta movimientos y orientación
   - Ícono: Giroscopio púrpura
   - Color: Verde (#4CAF50)

#### 🧠 **PROCESAMIENTO**
- **Unidad Central de Procesamiento**
  - Microcontrolador ATmega328P (Arduino)
  - Ícono: Microchip dorado
  - Color: Azul (#2196F3)
  - Funciones: Procesamiento de datos, algoritmos de control, toma de decisiones

#### ⚡ **SALIDAS (Actuadores)**
1. **Controlador de Motor (Puente H)** 🔧
   - Control bidireccional del motor DC
   - Ícono: Circuito H-bridge
   - Color: Naranja (#FF9800)

2. **Motor DC** ⚙️
   - Actuador principal del sistema
   - Ícono: Motor circular
   - Color: Naranja (#FF9800)

3. **Paciente en Cicloergómetro** 🚴‍♂️
   - Interfaz física del sistema
   - Ícono: Persona en bicicleta estacionaria
   - Color: Naranja (#FF9800)

## 📁 Archivos del Proyecto

### Archivos Principales
- `sistema_rehabilitacion_diagrama.svg` - Diagrama eléctrico en formato vectorial
- `visualizador_diagrama.html` - Visualizador web profesional del diagrama
- `README.md` - Documentación del proyecto

## 🚀 Cómo Usar

### Visualización Web
1. Abre `visualizador_diagrama.html` en tu navegador web
2. El diagrama se mostrará con interfaz profesional
3. Usa los botones para:
   - 🖨️ **Imprimir**: Generar versión impresa
   - 💾 **Descargar SVG**: Obtener archivo vectorial
   - 📄 **Exportar PDF**: Generar documento PDF

### Visualización Directa
- Abre `sistema_rehabilitacion_diagrama.svg` directamente en cualquier navegador
- Compatible con editores de gráficos vectoriales (Inkscape, Adobe Illustrator)

## 🎨 Características del Diseño

### Estilo Visual
- **Diseño Flat**: Moderno y limpio sin sombras excesivas
- **Paleta de Colores**: Profesional con azul, verde y naranja
- **Tipografía**: Arial/Helvetica para máxima legibilidad
- **Fondo**: Blanco/gris muy claro (#FAFAFA)

### Elementos Técnicos
- **Líneas de Flujo**: Flechas claras con marcadores
- **Gradientes**: Efectos visuales profesionales
- **Íconos Vectoriales**: Escalables sin pérdida de calidad
- **Organización**: Estructura clara y fácil de seguir

## 🔧 Especificaciones Técnicas

### Microcontrolador
- **Modelo**: ATmega328P (Arduino)
- **Frecuencia**: 16MHz
- **Memoria Flash**: 32KB
- **SRAM**: 2KB
- **E/S Digitales**: 14 pines
- **ADC**: 6 canales de 10 bits

### Sensores
- **Pulso Cardíaco**: Sensor óptico o electrocardiográfico
- **Temperatura**: Sensor termistor o LM35
- **IMU**: Acelerómetro y giroscopio integrados

### Control de Motor
- **Tipo**: Puente H bidireccional
- **Voltaje**: 12V DC
- **Corriente**: Hasta 2A
- **Control**: PWM para velocidad variable

## 📊 Flujo de Datos

```
Sensores → Microcontrolador → Controlador → Motor → Paciente
   ↓           ↓              ↓           ↓        ↓
Datos      Procesamiento   Señales    Acción   Rehabilitación
Fisiológicos   Inteligente   Control   Física   Activa
```

## 🎯 Aplicaciones

### Rehabilitación Cardiovascular
- Control de intensidad basado en frecuencia cardíaca
- Monitoreo de esfuerzo físico
- Prevención de sobreesfuerzo

### Rehabilitación Neurológica
- Control de movimientos coordinados
- Feedback en tiempo real
- Progresión gradual de dificultad

### Rehabilitación Ortopédica
- Control de resistencia adaptativa
- Monitoreo de rango de movimiento
- Prevención de lesiones

## 🔬 Ventajas del Sistema

### Técnicas
- **Arquitectura MISO**: Simplifica el control y reduce complejidad
- **Procesamiento Centralizado**: Algoritmos inteligentes de decisión
- **Modularidad**: Fácil mantenimiento y actualización
- **Escalabilidad**: Capacidad de agregar más sensores

### Clínicas
- **Seguridad**: Monitoreo continuo de parámetros vitales
- **Personalización**: Adaptación a cada paciente
- **Eficiencia**: Automatización de procesos de rehabilitación
- **Datos**: Registro y análisis de progreso

## 📈 Futuras Mejoras

### Hardware
- Sensores adicionales (presión arterial, saturación de oxígeno)
- Actuadores múltiples (resistencia variable, inclinación)
- Interfaz táctil para configuración

### Software
- Algoritmos de machine learning
- Interfaz de usuario mejorada
- Conectividad WiFi/Bluetooth
- Base de datos de pacientes

## 🤝 Contribuciones

Este proyecto está abierto a contribuciones. Para mejorar el diagrama o agregar funcionalidades:

1. Fork del repositorio
2. Crear rama para nueva funcionalidad
3. Realizar cambios
4. Enviar pull request

## 📄 Licencia

Este proyecto está bajo licencia MIT. Puedes usar, modificar y distribuir libremente.

## 📞 Contacto

Para preguntas o sugerencias sobre el sistema de rehabilitación:
- 📧 Email: [tu-email@ejemplo.com]
- 🐙 GitHub: [tu-usuario/repositorio]

---

**Desarrollado con ❤️ para mejorar la calidad de vida de pacientes en rehabilitación**

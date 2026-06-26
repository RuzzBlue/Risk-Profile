# Cuestionario Perfil de Riesgo Inversor

## Español

Un cuestionario interactivo basado en la web para determinar el perfil de riesgo del inversionista basándose en la metodología de Charles Schwab. Esta herramienta calcula los perfiles de inversión según el horizonte temporal y la tolerancia al riesgo, con recomendaciones de asignación de cartera personalizadas e **inclusivas en criptominedas**.

### Características

- **Cuestionario Interactivo**: 6 preguntas que evalúan horizonte temporal y tolerancia al riesgo
- **Cálculo Dinámico de Perfil**: Determinación basada en matriz de perfiles desde Conservador hasta Agresivo
- **Recomendaciones Condicionadas**: Cuando el horizonte temporal es corto (≤3 años), muestra el perfil recomendado versus el perfil calculado con interruptor de alternancia
- **Widget de Portafolio**: Representación visual de la asignación de activos recomendada con gráficos tipo dona y métricas de rendimiento
- **Recomendaciones en Criptoactivos**: Cada perfil incluye recomendaciones sobre asignación en criptominedas (Bitcoin, Ethereum, y otros activos digitales)
- **Diseño Responsivo**: Interfaz amigable para dispositivos móviles con panel lateral para información detallada
- **Exportación de Resultados**: Descarga los resultados como imagen PNG con toda la información del perfil
- **Información Educativa**: Secciones modales "¿Cómo funciona?" y "Acerca de este cuestionario"
- **Widget Matriz Inversor**: Matriz interactiva mostrando dónde se ubica tu perfil según los puntajes

### Perfiles de Riesgo

El cuestionario categoriza a los inversores en 5 perfiles:

1. **CONSERVADOR** - Horizonte corto, baja tolerancia al riesgo, asignación mínima en activos volátiles
2. **MODERADAMENTE CONSERVADOR** - Horizonte moderado, perfil equilibrado hacia lo conservador
3. **MODERADO** - Horizonte medio, enfoque equilibrado entre rentabilidad y protección
4. **MODERADAMENTE AGRESIVO** - Horizonte largo, mayor tolerancia al riesgo
5. **AGRESIVO** - Horizonte muy largo, alta tolerancia al riesgo, máxima exposición a activos volátiles

Cada perfil incluye una asignación recomendada de:
- Renta Fija (Bonos, fondos de deuda)
- Renta Variable (Acciones, fondos de inversión)
- Materias Primas
- **Criptominedas** (Bitcoin, Ethereum y otros activos digitales según el perfil)

### Sistema de Puntuación

- **Horizonte Temporal**: Escala de 1-10
  - 1 (A): Menos de 3 años
  - 3 (B): 3 a 5 años
  - 7 (C): 6 a 10 años
  - 10 (D): Más de 10 años

- **Tolerancia al Riesgo**: Escala de 1-10
  - Basado en la comodidad ante fluctuaciones del mercado y pérdidas potenciales temporales

### Cómo Empezar

1. Abre `app.html` en un navegador web
2. Ingresa tu nombre
3. Responde 6 preguntas sobre tus preferencias de inversión
4. Revisa tu perfil de inversor y la asignación de cartera recomendada
5. Descarga tus resultados como imagen

### Detalles de Características

#### Interruptor de Alternancia (Horizonte Temporal < 3 años)
Cuando tienes un horizonte temporal corto (score ≤ 3), la app muestra:
- **Recomendado**: CONSERVADOR (recomendado por horizonte temporal)
- **Tu Resultado**: Perfil calculado real (basado en matriz de tolerancia al riesgo)

Puedes alternar entre estos dos perfiles. El interruptor solo aparece si los perfiles son diferentes.

#### Widget de Recomendación de Portafolio
Muestra:
- Retorno anual promedio
- Mejor año de rendimiento
- Peor año de rendimiento
- Visualización de asignación de activos (gráfico tipo dona)
- Descripción detallada de activos incluyendo criptominedas

#### Panel Lateral
Panel expandible mostrando:
- Visualización de matriz inversor
- Explicación del perfil
- Información adicional sobre los activos recomendados

#### Descarga de Resultados
Exporta los resultados del cuestionario como imagen PNG limpia incluyendo:
- Nombre del usuario y puntajes
- Insignia del perfil de riesgo
- Descripción del perfil
- Recomendaciones de cartera con asignación en criptominedas
- Excluye botones de acción para una apariencia profesional

### Stack Técnico

- **HTML5** - Marcado semántico
- **CSS3** - Estilos responsivos con Flexbox y Grid
- **JavaScript Vanilla** - Sin dependencias, toda la funcionalidad en un archivo
- **Font Awesome** - Iconos
- **Bootstrap CSS** - Componentes UI
- **html2canvas** - Funcionalidad de exportación de imágenes

### Estructura de Archivos

```
.
├── app.html              # Archivo principal (aplicación de una sola página)
├── README.md             # Este archivo
└── .gitignore           # Reglas de ignorar de Git
```

### Navegadores Soportados

- Chrome/Chromium (recomendado)
- Firefox
- Safari
- Edge
- Cualquier navegador moderno que soporte ES6+

### Descargo de Responsabilidad

Esta herramienta es únicamente para propósitos educativos. Los resultados son informativos y no constituyen asesoramiento financiero ni de inversión. Siempre consulta con un profesional financiero calificado antes de tomar decisiones de inversión.

### Créditos

- Basado en la metodología de Cuestionario de Inversión de Charles Schwab
- Desarrollado por Branko Pereira
- Adaptado para análisis de inversiones inclusivas en criptominedas y educación financiera

---

# Risk Profile Questionnaire

## English

An interactive web-based questionnaire to determine investment risk profiles based on the Charles Schwab methodology. This tool calculates investor profiles based on time horizon and risk tolerance, with personalized portfolio allocation recommendations that are **inclusive of cryptocurrency investments**.

### Features

- **Interactive Questionnaire**: 6 questions assessing time horizon and risk tolerance
- **Dynamic Profile Calculation**: Matrix-based risk profile determination from Conservative to Aggressive
- **Conditional Recommendations**: When time horizon is short (≤3 years), shows recommended conservative profile vs. actual calculated profile with toggle switch
- **Portfolio Widget**: Visual representation of recommended asset allocation with donut charts and performance metrics
- **Cryptocurrency Recommendations**: Each profile includes allocation recommendations for cryptocurrencies (Bitcoin, Ethereum, and other digital assets)
- **Responsive Design**: Mobile-friendly interface with side panel for detailed profile information
- **Image Export**: Download results as PNG with all profile information
- **Educational Modals**: "How it works" and "About this questionnaire" information sections
- **Investor Matrix Widget**: Interactive matrix showing where your profile falls based on scores

### Risk Profiles

The questionnaire categorizes investors into 5 profiles:

1. **CONSERVADOR (Conservative)** - Short time horizon, low risk tolerance, minimal allocation to volatile assets
2. **MODERADAMENTE CONSERVADOR (Moderately Conservative)** - Moderate time horizon, conservative-leaning balanced approach
3. **MODERADO (Moderate)** - Medium time horizon, balanced approach between returns and protection
4. **MODERADAMENTE AGRESIVO (Moderately Aggressive)** - Long time horizon, higher risk tolerance
5. **AGRESIVO (Aggressive)** - Very long time horizon, high risk tolerance, maximum exposure to volatile assets

Each profile includes a recommended allocation of:
- Fixed Income (Bonds, debt funds)
- Equities (Stocks, investment funds)
- Commodities
- **Cryptocurrencies** (Bitcoin, Ethereum, and other digital assets based on the profile)

### Scoring System

- **Horizonte Temporal (Time Horizon)**: Scale of 1-10
  - 1 (A): Less than 3 years
  - 3 (B): 3 to 5 years
  - 7 (C): 6 to 10 years
  - 10 (D): More than 10 years

- **Tolerancia al Riesgo (Risk Tolerance)**: Scale of 1-10
  - Based on comfort with market fluctuations and potential temporary losses

### Getting Started

1. Open `app.html` in a web browser
2. Enter your name
3. Answer 6 questions about your investment preferences
4. Review your investor profile and recommended portfolio allocation
5. Download your results as an image

### Features in Detail

#### Toggle Switch (Time Horizon < 3 years)
When you have a short time horizon (score ≤ 3), the app shows:
- **Recomendado (Recommended)**: CONSERVADOR (recommended based on time horizon)
- **Tu Resultado (Your Result)**: Actual calculated profile (based on risk tolerance matrix)

You can toggle between these two profiles. The toggle only appears if the profiles differ.

#### Portfolio Recommendation Widget
Displays:
- Annual average return
- Best year performance
- Worst year performance
- Asset allocation visualization (donut chart)
- Detailed asset descriptions including cryptocurrency allocations

#### Side Panel
Expandable panel showing:
- Investor matrix visualization
- Profile explanation
- Additional information about recommended assets

#### Image Download
Export questionnaire results as a clean PNG image including:
- User name and scores
- Risk profile badge
- Profile description
- Portfolio recommendations with cryptocurrency allocations
- Excludes action buttons for a professional appearance

### Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling with Flexbox and Grid
- **Vanilla JavaScript** - No dependencies, all functionality in one file
- **Font Awesome** - Icons
- **Bootstrap CSS** - UI components
- **html2canvas** - Image export functionality

### File Structure

```
.
├── app.html              # Main application file (single-page application)
├── README.md             # This file
└── .gitignore           # Git ignore rules
```

### Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Any modern browser supporting ES6+

### Usage Disclaimer

This tool is for educational purposes only. Results are informative and do not constitute financial, legal, or investment advice. Investing involves risk and it is your responsibility to evaluate your financial situation and consult with qualified professionals before making investment decisions.

### Credits

- Based on Charles Schwab's Investment Questionnaire methodology
- Developed by Branko Pereira
- Adapted for cryptocurrency-inclusive investment analysis and financial education

### License

Educational use - Based on Charles Schwab model

---

**Note**: This is an educational tool. Investment decisions should be made with professional guidance. Cryptocurrency investments carry specific risks and volatility considerations.

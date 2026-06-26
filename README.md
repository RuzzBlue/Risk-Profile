# Cuestionario Perfil de Riesgo - Risk Profile Questionnaire

An interactive web-based questionnaire to determine investment risk profiles based on the Charles Schwab methodology. This tool calculates investor profiles based on time horizon and risk tolerance, with optional portfolio allocation recommendations.

## Features

- **Interactive Questionnaire**: 6 questions assessing time horizon and risk tolerance
- **Dynamic Profile Calculation**: Matrix-based risk profile determination from Conservador to Agresivo
- **Conditional Recommendations**: When time horizon is short (≤3 years), shows recommended conservative profile vs. actual calculated profile with toggle switch
- **Portfolio Widget**: Visual representation of recommended asset allocation with donut charts and performance metrics
- **Responsive Design**: Mobile-friendly interface with side panel for detailed profile information
- **Image Export**: Download results as PNG with all profile information
- **Educational Modals**: "How it works" and "About" information sections
- **Investor Matrix Widget**: Interactive matrix showing where your profile falls based on scores

## Risk Profiles

The questionnaire categorizes investors into 5 profiles:

1. **CONSERVADOR** - Conservative, short time horizon, low risk tolerance
2. **MODERADAMENTE CONSERVADOR** - Moderately Conservative
3. **MODERADO** - Moderate, balanced approach
4. **MODERADAMENTE AGRESIVO** - Moderately Aggressive
5. **AGRESIVO** - Aggressive, long time horizon, high risk tolerance

## Scoring System

- **Horizonte Temporal (Time Horizon)**: Scale of 1-10
  - 1 (A): < 3 years
  - 3 (B): 3-5 years
  - 7 (C): 6-10 years
  - 10 (D): > 10 years

- **Tolerancia al Riesgo (Risk Tolerance)**: Scale of 1-10
  - Based on comfort with market fluctuations and potential losses

## Getting Started

1. Open `app.html` in a web browser
2. Enter your name
3. Answer 6 questions about your investment preferences
4. Review your investment profile and recommended portfolio allocation
5. Download your results as an image

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling with Flexbox and Grid
- **Vanilla JavaScript** - No dependencies, all functionality in one file
- **Font Awesome** - Icons
- **Bootstrap Icons/CSS** - UI components
- **html2canvas** - Image export functionality

## File Structure

```
.
├── app.html              # Main application file (single-page application)
├── README.md             # This file
└── .gitignore           # Git ignore rules
```

## Features in Detail

### Toggle Switch (Time Horizon < 3 years)
When a user has a short time horizon (score ≤ 3), the app shows:
- **Recomendado**: CONSERVADOR (recommended based on time horizon)
- **Tu Resultado**: Actual calculated profile (based on risk tolerance matrix)

The toggle allows switching between these two profiles. The toggle only appears if the profiles differ.

### Portfolio Recommendation Widget
Displays:
- Annual return average
- Best year performance
- Worst year performance
- Asset allocation visualization (donut chart)
- Detailed asset descriptions

### Side Panel
Expandable panel showing:
- Investor matrix visualization
- Profile explanation
- Additional information

### Image Download
Export questionnaire results as a clean PNG image including:
- User name and scores
- Risk profile badge
- Profile description
- Portfolio recommendations
- Excludes action buttons for a professional appearance

## Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Any modern browser supporting ES6+

## Usage Disclaimer

This tool is for educational purposes only. Results are informative and do not constitute financial advice. Always consult with a qualified financial professional before making investment decisions.

## Credits

- Based on Charles Schwab's Investment Questionnaire methodology
- Developed by Branko Pereira
- Adapted for cryptocurrency-inclusive investment analysis

## License

Educational use - Based on Charles Schwab model

---

**Note**: This is an educational tool. Investment decisions should be made with professional guidance.

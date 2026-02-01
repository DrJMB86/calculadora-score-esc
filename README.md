# 🫀 Calculadora SCORE ESC

> Herramienta clínica para estratificación de riesgo cardiovascular basada en SCORE2, SCORE2-OP y SCORE2-Diabetes

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Calibrado para España](https://img.shields.io/badge/Región-Low%20Risk%20(España)-success)](https://academic.oup.com/eurheartj/article/42/34/3227/6358713)
[![Acceso directo](https://img.shields.io/badge/🌐_Calculadora-Online-brightgreen)](https://drjmb86.github.io/calculadora-score-esc/)

## 🎯 Descripción

Implementación web fiel de las calculadoras SCORE2, SCORE2-OP y SCORE2-Diabetes de la European Society of Cardiology (ESC), calibradas específicamente para la **región de bajo riesgo cardiovascular** (España y países mediterráneos).

### ✨ Características principales

- ✅ **SCORE2**: Pacientes 40-69 años sin diabetes
- ✅ **SCORE2-OP**: Pacientes 70-89 años (con o sin diabetes)  
- ✅ **SCORE2-Diabetes**: Pacientes 40-69 años con diabetes tipo 2
- ✅ **Recalibración regional automática** para España (low-risk)
- ✅ **Validaciones clínicas** en tiempo real
- ✅ **Recomendaciones terapéuticas** según categoría de riesgo
- ✅ **Historial de cálculos** (localStorage)
- ✅ **Interfaz responsive** (móvil, tablet, escritorio)
- ✅ **Exportación de resultados**

## 🚀 Uso

### Acceso directo

**👉 [Abrir calculadora](https://drjmb86.github.io/calculadora-score-esc/)**

Calculadora online disponible 24/7 sin necesidad de instalación.

### 📱 Acceso móvil rápido

**URL corta**: `drjmb86.github.io/calculadora-score-esc`

Escanea este QR desde tu móvil para acceso rápido en consulta:

<p align="center">
  <img src="frame.png" alt="QR Code Calculadora SCORE ESC" width="200">
</p>
<p align="center">
  <em>Escanea para acceso directo desde tu móvil</em>
</p>

### Uso local

1. Descargar `index.html`
2. Abrir con cualquier navegador moderno
3. No requiere instalación ni conexión a internet

## 📊 Fundamento científico

Esta calculadora implementa los algoritmos publicados en:

- **SCORE2**: [Lancet 2021;397:2047-60](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(21)01442-5/fulltext)
- **SCORE2-OP**: [Eur Heart J 2021;42:3071-81](https://academic.oup.com/eurheartj/article/42/34/3227/6358713)
- **SCORE2-Diabetes**: [Eur Heart J 2023;44:4251-65](https://academic.oup.com/eurheartj/article/44/39/4251/7246796)

### Calibración regional

España pertenece a la **región de bajo riesgo cardiovascular** según la clasificación ESC:

| Región | Países incluidos | Calibración |
|--------|------------------|-------------|
| 🟢 **Low-risk** | España, Portugal, Francia, Italia, Grecia, Suiza, Israel | ✅ Aplicada |
| 🟡 Moderate-risk | Alemania, UK, Países Bajos, Austria | ❌ |
| 🟠 High-risk | Polonia, Hungría, República Checa | ❌ |
| 🔴 Very high-risk | Rusia, Ucrania, países bálticos | ❌ |

## 🎓 Indicaciones de uso

### ✅ Utilizar en:
- Prevención primaria cardiovascular
- Pacientes 40-89 años
- Decisiones sobre inicio de estatinas
- Objetivos terapéuticos de LDL y PAS

### ❌ NO utilizar en:
- Enfermedad cardiovascular establecida
- Diabetes mellitus tipo 1
- Hipercolesterolemia familiar
- ERC estadio 4-5 (FGe <30 ml/min)
- Daño orgánico severo por diabetes
- Embarazo

## 🛠️ Especificaciones técnicas

- **Frontend**: HTML5, CSS3 (Tailwind), JavaScript ES6+
- **Sin dependencias** externas (excepto Tailwind CDN)
- **Tamaño**: ~40 KB (1 archivo)
- **Compatibilidad**: Todos los navegadores modernos
- **Accesibilidad**: Cumple WCAG 2.1 nivel A

### Validaciones implementadas

- Rangos clínicos para todos los parámetros
- Verificación de coherencia (HDL < CT)
- Alertas de valores extremos
- Recomendación automática de score apropiado

## 📖 Cómo interpretar los resultados

### Categorías de riesgo

**Para pacientes <70 años:**
- 🟢 Bajo: <5%
- 🟡 Moderado: 5-10%
- 🟠 Alto: 10-20%
- 🔴 Muy alto: ≥20%

**Para pacientes ≥70 años:**
- 🟢 Bajo: <7.5%
- 🟡 Moderado: 7.5-15%
- 🟠 Alto: ≥15%

### Objetivos terapéuticos

| Categoría | LDL-C objetivo | PAS objetivo |
|-----------|---------------|--------------|
| Bajo | <116 mg/dL | <130 mmHg |
| Moderado | <100 mg/dL | <130 mmHg |
| Alto | <70 mg/dL | <130 mmHg |
| Muy alto | <55 mg/dL | <130 mmHg |

## 🤝 Contribuir

Las contribuciones son bienvenidas:

1. Fork del proyecto
2. Crear rama feature (`git checkout -b feature/MejoraNueva`)
3. Commit cambios (`git commit -m 'Añadir nueva validación'`)
4. Push a la rama (`git push origin feature/MejoraNueva`)
5. Abrir Pull Request

### Áreas de mejora futuras

- [ ] Gráficos de riesgo interactivos
- [ ] Exportación a PDF con formato
- [ ] Cálculo de edad vascular
- [ ] Integración con historia clínica electrónica
- [ ] Multiidioma (catalán, euskera, gallego, inglés)
- [ ] App móvil nativa

## ⚠️ Disclaimer

Esta herramienta es **únicamente para apoyo clínico**. Las decisiones terapéuticas deben individualizarse considerando:

- Contexto clínico completo del paciente
- Comorbilidades y medicación actual
- Preferencias del paciente
- Juicio clínico profesional

**No sustituye** el criterio médico ni la evaluación clínica integral.

## 📜 Licencia

MIT License - ver archivo [LICENSE](LICENSE)

## 👨‍⚕️ Autor

Desarrollado para uso clínico en el Sistema Nacional de Salud español.

## 📚 Referencias

1. SCORE2 working group. SCORE2 risk prediction algorithms. *Lancet* 2021;397:2047-60.
2. SCORE2-OP working group. SCORE2-OP risk prediction algorithms. *Eur Heart J* 2021;42:3071-81.
3. ESC/EASD Guidelines. SCORE2-Diabetes. *Eur Heart J* 2023;44:4251-65.
4. ESC 2021 Guidelines on cardiovascular disease prevention. *Eur Heart J* 2021;42:3227-337.

## 📧 Contacto

Para sugerencias, bugs o colaboraciones, abrir un [Issue](https://github.com/drjmb86/calculadora-score-esc/issues) en GitHub.

**Repositorio**: [github.com/drjmb86/calculadora-score-esc](https://github.com/drjmb86/calculadora-score-esc)

---

**⭐ Si te resulta útil esta herramienta, considera dar una estrella al repositorio!**

**Última actualización**: Febrero 2026

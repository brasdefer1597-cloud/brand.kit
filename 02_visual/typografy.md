# 🖋️ typography.md · Chalamandra Magistral DecoX

> **"Nuestra tipografía es el choque entre el rigor académico y el grito del asfalto. Leemos entre líneas de alta costura y esténcil industrial."**

---

## 🎭 1. El Contraste Dialéctico
[cite_start]La identidad tipográfica de Chalamandra se basa en la tensión dinámica entre dos mundos[cite: 1]:

1.  [cite_start]**La Refinería (Sofisticación):** Tipografías Serif de alto contraste que evocan lujo y autoridad[cite: 8, 11].
2.  [cite_start]**El Asfalto (Disrupción):** Tipografías gestuales o industriales que evocan subversión y calle[cite: 6, 11].

---

## 📐 2. Sistema Tipográfico

| Uso | Familia Tipográfica | Atributo Psicológico |
| :--- | :--- | :--- |
| **Títulos Principales** | [cite_start]**Bodoni / Didot**  | [cite_start]Elegancia, herencia, sofisticación de "penthouse"[cite: 46]. |
| **Acentos / Subversión** | [cite_start]**Esténcil Industrial** [cite: 11] | [cite_start]Crudeza, "hacking" [cite: 38][cite_start], inteligencia de calle[cite: 42]. |
| **Citas / Notas** | [cite_start]**Caligrafía Gestual**  | [cite_start]Humanidad, fluidez de "Bailarina"[cite: 61], trazo personal. |
| **Cuerpo de Texto** | **Sans Serif Minimalista** | [cite_start]Legibilidad técnica, precisión de "Ballet"[cite: 61]. |

---

## 🛠️ 3. Reglas de Aplicación (Visual Guidelines)

* [cite_start]**Jerarquía "Magistral":** Los títulos en Bodoni deben tener un tracking (espaciado) elegante para denotar exclusividad.
* [cite_start]**Intervención Quirúrgica:** Los elementos de **Esténcil** o **Caligrafía** se usan como "vandalismo controlado" sobre la base limpia de la tipografía Serif[cite: 10, 11].
* [cite_start]**Legibilidad Tech:** Para interfaces de usuario (como en **Insightify**), se utiliza una tipografía técnica que facilite el reconocimiento de patrones y el análisis de datos[cite: 22, 87].

---

## 💻 4. Implementación en Web (CSS Tokens)

```css
:root {
  /* Clasismo y Refinamiento */
  --font-primary: 'Bodoni Moda', 'Didot', serif;
  
  /* Disrupción e Industria */
  --font-accent-stencil: 'Stardos Stencil', cursive;
  --font-accent-gestural: 'La Belle Aurore', handwriting;
  
  /* Rigor Técnico */
  --font-body: 'Inter', sans-serif;
}

h1, h2 {
  font-family: var(--font-primary);
  text-transform: uppercase;
  letter-spacing: 0.15em;
}

.glitch-text {
  font-family: var(--font-accent-stencil);
  color: var(--color-malandra); /* Magenta */
}

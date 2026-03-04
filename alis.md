---
layout: default
title: ALIS
---

# ALIS – Anion Laser Isobar Separator 🔬

## Das Isobar-Problem

Isobare sind Atome **verschiedener Elemente** mit gleicher Massenzahl 
(z. B. ¹⁴C und ¹⁴N). Da sie die gleiche Masse haben, können sie 
im AMS nur schwer voneinander getrennt werden. Genau hier setzt 
**ALIS** an.

---

## Konventionelle Isobar-Trennung

Bisher gibt es drei Methoden, um Isobare zu unterscheiden:

| Methode | Prinzip |
|---------|---------|
| **Chemistry** | Störende Isobare werden schon bei der Probenvorbereitung chemisch entfernt |
| **Anion Selection** | Manche Isobare bilden keine stabilen negativen Ionen und gelangen gar nicht erst in den Strahl |
| **Energy Loss** | Im Detektor verlieren verschiedene Elemente unterschiedlich viel Energie – so kann man sie unterscheiden |

> ⚠️ Diese Methoden stoßen bei vielen Nukliden an ihre Grenzen. 
> Einige Isotope sind mit konventioneller AMS **nicht messbar**.

---

## Was ist neu an ALIS?

ALIS ergänzt zwei **neue Trennmethoden**, die vor dem 
Tandem-Beschleuniger eingesetzt werden:

### 🔴 Laser (Photodetachment)

Ein Laser bestrahlt den Ionenstrahl. Die Photonenenergie ist 
so gewählt, dass sie **nur dem Isobar** das zusätzliche 
Elektron entreißt – es wird **neutralisiert** und fliegt aus 
dem Strahl. Das gewünschte Radionuklid bleibt als negatives 
Ion erhalten.

### 🧪 Gas Reactions

Der Ionenstrahl wird durch ein **gasgefülltes RFQ** 
(Radio Frequency Quadrupole) geleitet. Dort reagieren die 
Isobare selektiv mit dem Gas und bilden **Moleküle** 
(z. B. ZrF₃ + F → ZrF₄), während das Radionuklid 
unreagiert bleibt. Die unterschiedlichen Massen können 
dann magnetisch getrennt werden.

---

## Der Aufbau

Der Ionenstrahl durchläuft nach der Ionenquelle folgende Stationen:

| Komponente | Funktion |
|-----------|----------|
| **90°-Magnet** | Massenselektion – trennt Ionen nach Masse |
| **Slits** | Blenden zur Strahleinengung |
| **Lens** | Fokussierung des Ionenstrahls |
| **RFQ** | Gasgefüllte Kammer für Ionen-Gas-Reaktionen |
| **Triplet-Lens** | Weitere Fokussierung |
| **90°-ESA** | Elektrostatischer Analysator – trennt nach Energie |

---

## Das RFQ im Detail

Das RFQ (Radio Frequency Quadrupole) ist das **Herzstück** von ALIS:

| Bestandteil | Funktion |
|------------|----------|
| **Focusing Electrode** | Fokussiert den Strahl beim Eintritt |
| **Deceleration Electrode** | Bremst die Ionen ab |
| **Buffer-Gas Region** | Gasgefüllter Bereich für selektive Reaktionen |
| **Diagonal Split Cylinder** | Erzeugt das RF-Feld zum Einfangen der Ionen |
| **Acceleration Electrode** | Beschleunigt die Ionen wieder nach der Reaktion |

> 💡 Die Ionen werden im RFQ **abgebremst**, damit sie 
> genug Zeit haben, mit dem Gas zu reagieren – und 
> danach wieder beschleunigt.

---

## Welche Nuklide profitieren von ALIS?

Nicht alle Nuklide brauchen ALIS. Das Diagramm zeigt, 
welche Isotope mit konventioneller AMS messbar sind und 
welche ALIS benötigen:

| Kategorie | Beispiele |
|-----------|----------|
| ✅ Konventionell messbar (kein stabiles negatives Isobar) | ¹⁰Be, ²⁶Al, ³⁶Cl, ⁴¹Ca, ¹⁴C |
| ⚠️ Messbar, aber mit Gamma-Emission | ⁵³Mn, ⁶⁰Fe, ⁹³Zr u. a. |
| ❌ **Nicht messbar** ohne ALIS | Diverse Nuklide mit stabilen negativen Isobaren |

> ALIS erweitert das Spektrum messbarer Nuklide 
> am CologneAMS **erheblich**.

---

<details>
<summary>📄 Poster: ALIS (klicke zum Öffnen)</summary>

<iframe 
  src="assets/documents/poster_Markus.pdf" 
  width="100%" 
  height="600px" 
  style="border: 2px solid #ccc; border-radius: 8px;">
</iframe>

<p>
  PDF wird nicht angezeigt? 
  <a href="assets/documents/poster_Markus.pdf" target="_blank">
    ⬇️ Hier herunterladen
  </a>
</p>

</details>

---

> ⏮️ Zurück zur [Erzeugung des Ionenstrahls](ionenstrahl)
>
> 🏠 Zurück zur [Startseite](index)

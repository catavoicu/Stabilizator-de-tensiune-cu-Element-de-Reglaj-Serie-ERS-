# Stabilizator de Tensiune cu Element de Reglaj Serie (ERS)

## 📜 Descrierea Proiectului

Stabilizatorul de tensiune proiectat are rolul de a furniza o tensiune constantă la ieșire, chiar dacă tensiunea de intrare sau sarcina variază. Este destinat aplicațiilor de alimentare cu curent continuu care necesită o tensiune stabilizată.

### Caracteristici principale:

-Tensiunea de ieșire reglabilă în intervalul: 14 - 28 [V]
-Element de reglaj serie;
-Sarcina la ieșire 1120 Ω;
-Protecție la suprasarcină prin limitarea temperaturii tranzistorului regulator serie la 1200C, și a curentului maxim la 0,5A;
-Tensiune de intrare în intervalul: 50,4 - 56 [V] 
-Domeniul temperaturilor de funcționare: 0-60 C (verificabil prin testare în temperatură);


## 📁 Structura Proiectului

Proiectul include următoarele fișiere și directoare:

- `Bill_of_Materials` -  Listă detaliată care conține toate componentele necesare pentru fabricare, incluzând cantități, specificații și detalii despre furnizori + Lista componentelor folosite (BOM).
- `Data Sheets` - Documentele tehnice care oferă specificații, caracteristici, performanțe și utilizări ale componentelor.
- `Layout` - Fișierele de proiectare in OrCAD X PCB.
- `Proiect Docs` - Documentația proiectului:
  - **Raportul proiectului** (PDF)
  - **Formule și calcule** utilizate pentru proiectare.
- `Schematics` - Schema electronică care ilustrează componentele și conexiunile circuitului.
- `Simulations` - Verifică performanța și stabilitatea circuitului, optimizând alegerea componentelor și condițiile de operare

## 🔧 Instrucțiuni pentru Utilizare

### 1. **Simularea Circuitului**
1. Deschide fișierul "P1_VOICU_CATALIN.opj" din folderul `Schematics` folosind un simulator compatibil, cum ar fi OrCAD X.
2. Rulează simulările pentru a verifica funcționarea circuitului.

### 2. **Fabricarea PCB-ului**
1. Folosește fișierele Gerber din folderul `Layout` pentru a viziona și fabrica PCB-ul.

## ⚙️ Cerințe Tehnice

- **Software necesar**:
  - OrCAD 17.2 - OrCAD X pentru simulări.
  - OrCAD 17.2 - OrCAD X pentru design-ul PCB.


## 🖼️ Capturi de Ecran și Scheme

1. **Schemă Electrică**:
  https://github.com/catavoicu/Stabilizator-de-tensiune-cu-Element-de-Reglaj-Serie-ERS-/blob/main/Schematics/Schema.jpg

2. **Design PCB**:
   https://github.com/catavoicu/Stabilizator-de-tensiune-cu-Element-de-Reglaj-Serie-ERS-/blob/main/Layout/p1_voicu_catalin.jpg

## 👨‍💻 Autor
- **Nume**: Catalin Voicu
- **Email**: catavoicu01@gmail.com
- Proiect realizat ca parte a cursului: P1.
- **Universitate**: Facultatea de Electronică, Telecomunicații și Tehnologia Informației, Universitatea Politehnica București.

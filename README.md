# Fibonacci-XXZ-Kritikalität

**Erste präzise Bestimmung des kritischen Parameters Δ_c in der Fibonacci-modulierten XXZ-Kette**

**Δ_c = 0.472 ± 0.006**

Dieses Repository enthält alle DMRG-Berechnungen, Rohdaten (Platzhalter für finale .h5), Analyse-Notebooks (Platzhalter) und Logs für die quasiperiodische Fibonacci-modulierte XXZ-Spin-Kette mit Modulation (-1)^{⌊iφ⌋}.

### Hauptresultat
Kritischer anisotroper Kopplungsparameter: **Δ_c = 0.472 ± 0.006**  
Bestimmt mit vier unabhängigen Methoden und Systemgrößen bis N=610 (χ=2048).

### Reproduzierbarkeit
Umgebung einrichten:
```bash
conda env create -f environment.yml
conda activate fibonacci-xxz

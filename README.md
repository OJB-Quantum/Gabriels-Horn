# Gabriels-Horn
Generate a visualization of Gabriel's Horn in Python and Blender; also called Torricelli’s Trumpet, a geometric figure with infinite surface area and finite volume.

---

Primary URL for the repository: [OJB-Quantum/Gabriels-Horn](https://github.com/OJB-Quantum/Gabriels-Horn)

---

![Gabriel's Horn 001](https://github.com/user-attachments/assets/333a45a4-5338-4328-ab29-232be31314f1)

![Gabriel's Horn 002](https://github.com/user-attachments/assets/77fdbbd7-d3ce-4ed6-bf60-2571e1b18db0)

### The visualization for the rendered Gabriel's Horn is based on the formula below:

$V=\pi \int_1^a\left(\frac{1}{x}\right)^2 \mathrm{~d} x=\pi\left(1-\frac{1}{a}\right) \quad \lim _{a \rightarrow \infty} V=\lim _{a \rightarrow \infty} \pi\left(1-\frac{1}{a}\right)=\pi$

$A=2 \pi \int_1^a \frac{1}{x} \sqrt{1+\left(-\frac{1}{x^2}\right)^2} \mathrm{~d} x>2 \pi \int_1^a \frac{\mathrm{~d} x}{x}=2 \pi \ln (a) \quad \lim _{a \rightarrow \infty} A \geq \lim _{a \rightarrow \infty} 2 \pi \ln (a)=\infty$

> Note: the rendered equation in the image shown was imported as an SVG into Blender, followed by converting it into a mesh, cleaning it up in Edit Mode, then extruding the faces into a 3D object.

### Click to view Gabriel's Horn visualized in a Google Colab notebook: [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OJB-Quantum/Gabriels-Horn/blob/main/Gabriel's_Horn_with_Python.ipynb)

### Click to view the Blender Python script: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/OJB-Quantum/Gabriels-Horn/blob/main/Gabriel%27s%20Horn_Blender%20Python.py)

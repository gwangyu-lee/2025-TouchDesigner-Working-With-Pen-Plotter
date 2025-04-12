# 2025-TouchDesigner-Working-With-Pen-Plotter

![IMG_8097](https://github.com/user-attachments/assets/07d9a714-ed65-4b05-b883-72a9d8223ff7)


## SVG Fonts
[SVG Fonts](https://gitlab.com/oskay/svg-fonts)

## L-System
[LSystem SOP](https://docs.derivative.ca/LSystem_SOP)

### Book
The Algorithmic Beauty of Plants    
Przemyslaw Prusinkiewicz & Aristid Lindenmayer    
Springer-Verlag, New York, Phone: 212.460.1500    
ISBN: 0-387-94676-4, 1996.    

### Examples
```
p.17 a
generation = 4, angle = 90

premise:A

A = -L
L = LF+RFR+FL-F-LFLFL-FRFR+
R = -LFLF+RFRFR+F+RF-LFL-FR
```

```
p.17 b
generation = 3, angle = 90

premise:A

A = -L
L = LFLF+RFR+FLFL-FRF-LFL-FR+F+RF-LFL-FRFRFR+
R = -LFLFLF+RFR+FL-F-LF+RFR+FLF+RFRF-LFL-FRFR
```

```
p.20
generation = 2, angle = 90

premise:A

A = B-F+CFC+F-D&F^D-F+&&CFC+F+B//
B = A&F^CFB^F^D^^-F-D^|F^B|FC^F^A//
C = |D^|F^B-F+C^F^A&&FA&F^C+F+B^F^D//
D = |CFB-F+B|FA&F^A&&FB-F+B|FC//
```

```
p.25 c
generation = 4, angle = 22.5

premise:A

A = F
F = FFF-[--F+F+FJ]+[+F-F-FK]
```

```
p.25 d
generation = 6, angle = 20

premise:A

A = X
X = F[+X]F[-XJ]+X
F = FF
```

## References
[SOP to SVG](https://github.com/raganmd/touchdesigner-sop-to-svg)    
[2023-TouchDesigner-Working-With-Pen-Plotter-Workshop](https://github.com/gwangyu-lee/2023-TouchDesigner-Working-With-Pen-Plotter-Workshop?tab=readme-ov-file)

## Pen Plotter Art

![IMG_8307](https://github.com/user-attachments/assets/fc5276c9-04f2-4b1e-a8f2-4fcbe135562c)
![IMG_8319](https://github.com/user-attachments/assets/aa176c19-3a32-403f-8153-a72e74d3b75d)
![IMG_8323](https://github.com/user-attachments/assets/2efc320a-8c3a-4413-970a-3cc887fb32fd)
![IMG_8312](https://github.com/user-attachments/assets/a410a85f-63f8-4196-96a1-6ebeea8ed9a2)
![IMG_8223](https://github.com/user-attachments/assets/f262aff0-97f1-420e-bbc5-222f65bac000)
![IMG_8328](https://github.com/user-attachments/assets/97985f24-2800-43f6-8f13-f28ef6c0d764)


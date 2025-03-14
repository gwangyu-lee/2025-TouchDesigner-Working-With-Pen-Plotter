# 2025-TouchDesigner-Working-With-Pen-Plotter

![timelapse h264 no sound](https://github.com/user-attachments/assets/300696c6-2814-4f14-a73e-649a5ca7381c)


## SVG Fonts
[SVG Fonts](https://gitlab.com/oskay/svg-fonts)

## L-System
[LSystem SOP](https://docs.derivative.ca/LSystem_SOP)

### Book
The Algorithmic Beauty of Plants    
Przemyslaw Prusinkiewicz & Aristid Lindenmayer    
Springer-Verlag, New York, Phone: 212.460.1500    
ISBN: 0-387-94676-4, 1996.    

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

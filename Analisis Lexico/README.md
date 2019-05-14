# Ejemplos de lexer y parser usando ply

G =< {E,T, F}, {+, ∗, num,(,)}, P, E >
E → E + T
E → T
T → T ∗ F
T → F
F → num
F → (E)


Julian Pinilla 20142020012 Daniel Camargo 20142020094 Juan Sebastian Cruz 20141020128

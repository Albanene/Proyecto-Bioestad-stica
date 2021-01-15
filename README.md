# Proyecto-Bioestad-stica
# Base de datos
sleep # es un experimento que mide los efectos de un somnífero contra placebo en las horas de sueño de 10 estudiantes. El factor "extra" es el incremento de horas de sueño, el grupo 1 es el placebo y el 2 el tratamiento, el ID es el número de estudiante. 
# Dependent t-test
with(sleep, t.test(extra[group == 1], extra[group == 2]))

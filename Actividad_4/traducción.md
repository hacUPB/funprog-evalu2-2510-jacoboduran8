# Reto Final
Traducción de los 5 primeros retos a C.

## Tabla de contenido
|Contenido|
|---------|
|[Reto1](#reto-1)|
|[Reto 2](#reto-2)|
|[Reto 3](#reto-3)|
|[Reto 4](#reto-4)|
|[Reto 5](#reto-5)|
|[Pregunta Final](#pregunta-final)|
## Reto 1

        #include <stdio.h>

        int main() {
            double X1, Y1, X2, Y2, D;

            printf("Ingrese la coordenada de dos puntos (X1,Y1) Y (X2,Y2):/n)"
            scanf("%f %f", &X1, &Y1)
            scanf("%f %f", &X2, &Y2)

            D = sqrt(pow(X2 - X1, 2) + pow(Y2 - Y1, 2));

            printf("La distancia entre los puntos = %.2f\n", D);
    
            return 0;
        }

## Reto 2

        #include <stdio.h>

        int main() {
            double M, P;

            printf("Cantidad en metros (M):");
            scanf("%f", &M);

            P = M/0,0254;

            printf("El total de pulgadas para pedir = %.2f\n", P);

            return 0;
        }


## Reto 3

        #include <stdio.h>

        int main() {
            double CO, CA, H;

            printf("inserte cateto opuesto (CO) y cateto adyacente (CA): \n");
            scanf("%f %f", &CO, &CA);

            H = sqrt (pow(CO, 2) + pow(CA, 2));

            printf("La hipotenusa es = %.2f\n", H);

            return 0,

        }

## Reto 4

        #iclude <stdio.h>

        int main() {
            int d_N, m_N, a_N;
            int d_H, m_H, a_H;
            int E, ER;

            printf("Ingrese la decha de nacimiento (N), con fecha completa: dia, mes, año. También ingrese la fecha actual (H) en el mismo formato:");
            scanf("%d %d %d", &d_N, &m_N, &a_N);
            scanf("%d %d %d", &d_H, &m_H,&a_H);

            E = a_H - a_N

            if (m_N < m_H) {
                printf("Ya cumpliste y la edad es %d\n", E);
            } else if (m_N = m_H) {
                if (d_N < d_H) {
                    printf("Ya cumpliste y la edad es %d\n", E);
                } else if (d_N = d_H) {
                    printf("Hoy estás cumpliendo años \n");
                } else {
                    ER = E - 1;
                    printf("No has cumplido y tu edad es %d\n", ER);
                }
            } else {
                ER = E - 1;
                printf("No has cumplido y tu edad es %d\n", ER);
    }
    
    return 0;
    }


## Reto 5

        #include <stdio.h>

        int main() {
            double HT, PH, P;
    
             printf("Ingrese la cantidad de horas trabajadas (HT) y el pago por hora (PH):\n");
            scanf("%f %f", &HT, &PH);
    
             if (HT <= 40) {
                P = HT * PH;
            } else if (HT <= 45) {
                P = (40 * PH) + ((HT - 40) * 2 * PH);
            } else if (HT <= 50) {
                P = (40 * PH) + (5 * 2 * PH) + ((HT - 45) * 3 * PH);
            } else {
                printf("No es posible que un trabajador trabaje más de 50 horas.\n");
                return 0;
            }
    
    printf("El total a pagar a los trabajadores es %.2f\n", P);
    
    return 0;
    }

## Pregunta Final
Yo creo que me falta mejorar y aprender más el uso de caracteres y que tipo de variable es la que debo declarar.
    


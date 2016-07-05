# Juego-De-Memoria-Coursera
Programa un playground que evalúe un rango de números en base a 4 reglas de impresión.

//: Playground - Rango de numeros en base a 4 reglas de impresion

import UIKit

//Se aplica la regla: “Si el número es divisible entre 5, imprime: # el número  + “Bingo!!!”
for num in 0...100 {
    if num % 5 == 0 {
        print ("\(num) Bingo!!!")
    }
    
//Se aplica la regla: “Si el número es par, imprime: # el número + “par"
    if num % 2 == 0 {
        print ("\(num) par!!!")
        
//Se aplica la regla: “Si el número es impar, imprime: # el número + “impar"
    }else {
        print ("\(num) impar!!!")
    }
    
//Se aplica la regla: “Si el número se encuentra dentro de un rango del 30 al 40, imprime: # el número +  “Viva Swift!!!”
    if num >= 30 && num <= 40 {
        print ("\(num) Viva Swift!!!")
    }
}

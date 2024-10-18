## Lenguajes de Programación
### Evaluación Semanal 8

#### 📝 Instrucciones

- El semanal podrá resolverse **en equipos de 3**.
- Se deberá entregar por medio de GitHub Classroom a más tardar a las **23:59:59 del martes 22 de octubre de 2024**. **No habrán prórrogas**. En caso de requerir más tiempo, se descontará un punto por cada día de entrega tardío.
- Cualquier duda podrá extenarse en la clase, por correo o por medio de Telegram en un horario de 8:00 a 18:00.
- Deberá entregarse en formato LaTeX.
- No es necesario que vuelvan a escribir los ejercicios completos, basta con que los numeren y entreguen **en orden**.

#### 🚀 Ejercicios

Modifica cada una de las siguientes funciones de forma que usen el estilo de paso de continuaciones (*Continuation Passing Style*).

1. ```haskell
   potencia :: Int -> Int -> Int
   potencia n 0 = 1
   potencia n m = n * (potencia n (m - 1))
   ```

2. ```haskell
   sumaDigitos :: Int -> Int
   sumaDigitos n
   | n < 10 = n
   | otherwise = (mod n 10) + (sumaDigitos (n / 10))
   ```

3. ```haskell
   cuadrados :: [Int] -> [Int]
   cuadrados [] = []
   cuadrados (x:xs) = (x^2):(cuadrados xs)
   ```

4. ```haskell
   reversa :: [a] -> [a]
   reversa [] = []
   reversa (x:xs) = reversa xs ++ [x]
   ```
   

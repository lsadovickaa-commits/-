# Вариант 4
1. Вывести рекуррентное соотношение для предложенной матрицы.
   
2. Составить и решить характеристическое уравнение.
   
3. Вывести формулу общего решения.
   
4. Рассчитать на основе полученной формулы значение определителя матрицы порядка *n*. 
---
$$    
A =     
 \begin{pmatrix}    
  3 & 2 & 0 & \cdots & 0 & 0 \\    
  1 & 3 & 2 & \cdots & 0 & 0 \\    
  0 & 1 & 3 & \cdots & 0 & 0 \\    
  \vdots  & \vdots & \vdots & \ddots & \vdots & \vdots  \\    
  0 & 0 & 0 & \cdots & 3 & 2 \\    
  0 & 0 & 0 & \cdots & 1 & 3     
 \end{pmatrix}    
$$
---

1. Разложим определитель матрицы по 1 строке
   $$   
 \begin{vmatrix}    
  3 & 2 & 0 & \cdots & 0 & 0 \\    
  1 & 3 & 2 & \cdots & 0 & 0 \\    
  0 & 1 & 3 & \cdots & 0 & 0 \\    
  \vdots  & \vdots & \vdots & \ddots & \vdots & \vdots  \\    
  0 & 0 & 0 & \cdots & 3 & 2 \\    
  0 & 0 & 0 & \cdots & 1 & 3     
 \end{vmatrix}    
 3 \cdot  
 \begin{vmatrix}    
  3 & 2 & 0 & \cdots & 0 & 0 \\    
  1 & 3 & 2 & \cdots & 0 & 0 \\    
  0 & 1 & 3 & \cdots & 0 & 0 \\    
  \vdots  & \vdots & \vdots & \ddots & \vdots & \vdots  \\    
  0 & 0 & 0 & \cdots & 3 & 2 \\    
  0 & 0 & 0 & \cdots & 1 & 3     
 \end{vmatrix} -2 \cdot  
 \begin{vmatrix}    
  3 & 0 & 0 & \cdots & 0 & 0 \\    
  1 & 2 & 0 & \cdots & 0 & 0 \\    
  0 & 3 & 2 & \cdots & 0 & 0 \\    
  \vdots  & \vdots & \vdots & \ddots & \vdots & \vdots  \\    
  0 & 0 & 0 & \cdots & 3 & 2 \\    
  0 & 0 & 0 & \cdots & 1 & 3     
 \end{vmatrix}    
$$




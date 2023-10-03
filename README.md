# Select - From:
No debe haber una coma antes del `FROM`

Select permite obtener datos de una o más tablas a manera de consulta.

Select no modifica el contenido de las tablas

* = mostrar todas las columnas, pero tambien se pueden mostrar columnas adicionales repetidas:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/0838aa80-858f-4e13-a104-c158fd7846b2)


código en SQL = Query
-----------
## Si de una tabla solo quiero mostrar nombre, apellido y dni:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/9272cd88-d4f8-44e3-8220-05fe7c8edef3)

## Se pueden exportar tablas:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/332a9a1f-85f0-4764-89a7-f20b681cb0fe)

![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/518b67ee-71ae-479f-8ab4-71710c2c4d6d)

## Juntar Columnas:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/d6084f3d-a2f6-4c84-a636-5c0d95baf755)

## Colocar Alias: 
Recordar que antes del **FROM** debe haber un espacio.
Tambien se puede usar comillas dobles o comillas simples y no poner `as`, sin embargo lo recomendable es usar comillas invertidas ``.

![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/12c2b97a-fbd7-4f7c-9275-8b178df27794)
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/e81d4cd6-7d36-47bd-b736-5b289f0bcadd)

## Algunas funciones:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/b9afd169-852e-4c2b-b6ed-e92df60b0bda)

![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/f5b7f80e-35a2-49ce-9655-0af367ed985b)

## Para fechas:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/352ae971-5787-4d32-b887-1cf79cc624d0)

## Mostrar una columna sin repetir datos:
Solo se puede mostrar una unica columna con está opción
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/da996812-f913-4d95-b32d-97a5924c684e)

## Ordenar columna:
Se puede colocar order by salary desc o 

order by salary asc(este ultimo equivale a no poner nada), ya que por defecto ordena de menor a mayor
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/77f95305-a039-42eb-aa1e-d558d9813af3)

---------------------

Y si hay datos que se repiten(como el salario) y quiero que pase a ordenarse por nombre esos comunes en salario:

En este ejemplo Hazel y Steven tienen el mismo salario pero lo ordenamos tal que por nombre respecto al abecedario
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/62894fc1-e816-40c4-98e7-486c5171045f)

Además, el segundo criterio de orden se puede indicar como asc(default) o desc(descendente):
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/9666c4c3-4d72-40e1-8045-0ee98cc839de)


-----------------

Tambien funciona para VARCHAR. Entre numeros y letras, lo mayor serán las letras y lo menos los numeros:

Menor a Mayor: 1,2,...,9,a,b,c,...,z (asc)

Mayor a Menor: z,...,b,a,9,8,...,2,1 (desc)

![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/0a4b8151-501b-42f1-98d0-33e5dd20e255)

-------

# Where (filtrado):
Mostrar el empleados con salario mayor a 9000:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/22a1cdd8-999a-4e5f-878a-216d4319ce17)

2 o más condiciones:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/7e894f9a-b0d3-4df9-92b8-2788d9cb5b29)
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/b9a02c50-daa6-4e26-a98f-c10a4831dc9d)

Condición de que algo sea no nulo:
Ojo: que sea nulo no significa que sea cero, sino que no existe
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/a928a791-475a-4509-9207-af49cef90db6)

-------------

## Between:
Intervalo cerrado:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/84e76778-25c3-4774-b2fc-175830245a79)

Intervalo abierto(No cuenta los limites señalados como 3000 y 4000 en este caso):
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/615f0f2f-dcf6-4f01-ae2e-d3fe005b0584)

-------------------
## In():
Sin in:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/15460a43-0acb-40e0-aea0-c470dc3ddafd)

Con in:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/3221d065-9d0c-4afe-b7e8-a7edde440a76)

Para excluir:
![image](https://github.com/Pierohc/SELECT-SQL/assets/133154904/67b74c84-cdac-4450-a080-8ecec8e94289)

























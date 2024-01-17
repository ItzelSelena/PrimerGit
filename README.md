#pip install openpyxl

import openpyxl

archivo_excel = 'Libro 2.xlsx'

# Cargar el archivo Excel, 
#el segundo parametro de openpyxl.load_workbook despues de archivo_excel es para eliminar las formulas de la celda, mas bien apra que no aparezcan las formulas y te de el resultado del mismo C: si, eso 
libro = openpyxl.load_workbook(archivo_excel, data_only=True)

print(libro.worksheets)

hoja = libro.worksheets[0]
tabla = hoja.iter_rows()

print(tabla)
tabla = list(tabla)

#se lee de izquierda a derecha y se lee por filas
print(tabla)


for fila in tabla:
    for celda in fila:
        print(celda.value, "|", end="")
    print("") 

# Cerrar el archivo Excel después de usarlo

libro.close()

# Reto3

while True:
  print('MENU'.center(50, '='))

  print("""
   1.- Platos del dia
         2.- Salir
   """)

  opcion: 'srt' = input('Escoge:')
  if opcion in ['1']:
     print('Platos del dia')
     print("""
        1-Trucha marinada con salsa de albahaca con Gaseosa
                     2- Judías verdes con tomate y jamón con limonada de yerbabuena
                     3- Berenjenas agridulces con hamburguesa con jugo natural

        """)


  if opcion in ['2']:
      print('Bebidas')
      print("""
          1.- Agua
          2.- Limonada de coco
          3.- Limonada de yerbabuena
          4.- volver
          """)

      opcion: 'srt' = input('Escoge: ')

      if opcion in ['1', '2', '3']:
          print('Buena eleccion')
      else:
        break
















va1,va2, va3,  va4, va5, va6, = 10, 20, 50, 100, 200, 500









total =('precio de la comida')

#reverse Arrays
menu: list = ['1.Trucha marinada con salsa de albahaca con Gaseosa', '2.Judías verdes con tomate y jamón con limonada de yerbabuena', '3.Berenjenas agridulces con hamburguesa con jugo natural']
menu = menu[::1]

precio: list = ['50€', '65€', '45€']
precio = 'precio' [::1]



# Bucle for

collections = ("50€","60€","45€")

for i in collections:
    print(f"1.Trucha marinada con salsa de albahaca con Gaseosa:{i}")
    print(f"2.Judías verdes con tomate y jamón con limonada de yerbabuena:{i}")
    print(f"3.Berenjenas agridulces con hamburguesa con jugo natural:{i}")

# Diccinarios

diccionario = ("1.Trucha marinada con salsa de albahaca con Gaseosa:50€","2.Judías verdes con tomate y jamón con limonada de yerbabuena:65€","3.Berenjenas agridulces con hamburguesa con jugo natural:45€")

while True:
  print('MENU'.center(50, '='))

  print("""
   1. Trucha marinada con salsa de albahaca con Gaseosa 50€
   2. Judías verdes con tomate y jamón con limonada de yerbabuena 65€
   3. Berenjenas agridulces con hamburguesa con jugo natural 45€
   """)


  opcion: 'srt' = input('Escoge: ')

  if opcion in ['1', '2', '3']:
      print('desea ordenar algo mas')
      print("""
          1.Si
          2.No
          """)

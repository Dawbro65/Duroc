import os
listaN = []

while True:
    print ("""
1- Guardar un nombre
2- Mostrar todos los nombres
3- Buscar un nombre
4- Buscar un nombre por su posicion
5- Salir del programa""")

    try:
        opc = int(input("\nIngrese una opción: "))
        os.system('cls')
    except ValueError:
        os.system('cls')
        print ("ERROR, Ingrese un numero")
        continue

    match opc:

        case 1:
            nombre = input("\nIngrese el nombre a ingresar: ").capitalize()
            os.system('cls')
            print (f"\nNombre '{nombre}' añadido exitosamente")
            listaN.append(nombre)
        
        case 2:
            if len(listaN) > 0:
                os.system('cls')
                print (f"\nLos nombres registrados son: {listaN}")
            else:
                os.system('cls')
                print ("\nNo hay nombres registrados")

        
        case 3:
            if len(listaN) > 0:
                os.system('cls')
                buscar = input("\nQue nombre desea buscar: ").capitalize()
                if buscar in listaN:
                    os.system('cls')
                    print (F"\nEl nombre {buscar} si se encuentra en la lista en la posicion {listaN.index(buscar)}")
                
                else:
                    os.system('cls')
                    print (f"\nEl nombre {buscar} no se encuentra en la lista")
            else:
                os.system('cls')
                print ("\nNo hay nombres registrados")

        
        case 4:
            if len(listaN) > 0:
                try:
                    os.system('cls')
                    buscarP = int(input("\nQue nombre desea buscar por posicion: "))
                    if buscarP in range (len(listaN)):
                        os.system('cls')
                        print (f"\nEn la posicion {buscarP} se encuentra el nombre {listaN[buscarP]}")
                    else:
                        os.system('cls')
                        print (f"\nNo hay nombre en la posicion {buscarP}")
                    

                except ValueError:
                    os.system('cls')
                    print ("\nERROR, Ingrese un numero")
                    continue
            else:
                os.system('cls')
                print ("\nNo hay nombres registrados")

        case 5:
            os.system('cls')
            print ("\nSaliendo del programa")
            break

        case __:
            os.system('cls')
            print ("\nIngrese una opcion valida ")

                

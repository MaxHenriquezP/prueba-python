import funciones as fn

while True:
    print("-------------------------------")
    print("*** Bienvenido a GAXPLOSIVE ***")
    print("-------------------------------")
    print("1.- Registrar pedido. ")
    print("2.- Listar los todos los pedidos. ")
    print("3.- Imprimir hoja de ruta.")
    print("4.- Salir del programa. ")
    
    try:
        opcion= int(input("Seleccione una opcion:"))
    
        if opcion == "1":
            fn.registrar_pedido ()


        elif opcion == "2":
            fn.listar_pedidos()
        
        elif opcion == "3":
            fn.imprimir_ruta()
    
        elif opcion == "4":
            break
    except:
        print("La opcion ingresada es invalida")

        

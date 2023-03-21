# Busqueda_primero_en_anchura
Algoritmo de búsqueda no informada utilizado para recorrer o buscar elementos en un grafo.
#Definición del problema
#Espacio_estados = A, B, C, D, E, F, G, H, I, J
#Estado_inicial = A
#Estado_objetivo = H
#Acciones = M_Iz, M_Cen, M_Der
#Funciones sucesoras [Accion,Estado,Costo]
A= [["M_iz","B",1],["M_Cen","C",1],["M_der","D",1]]
B= [["M_iz","E",1],["M_der","F",1]]
C= [["M_iz","G",1],["M_der","H",1]]
D= [["M_iz","I",1],["M_der","J",1]]

#Función objetivo
#Estado actual == "H" => Objetivo conseguido

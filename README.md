# Trabajo_Autonomo_1

package main

import (
	"fmt" // Libreria que permite presentar datos en pantalla.
)

// ================= FUNCION DRAMA =================

func peliculasDrama() {

	var opcion int

	for {

		fmt.Println("\n========== PELICULAS DRAMA ==========")
		fmt.Println("1. El lobo de Wall Street")
		fmt.Println("2. Joker")
		fmt.Println("3. Forest Gump")
		fmt.Println("4. Yo Antes de Ti")
		fmt.Println("5. En busca de la felicidad")
		fmt.Println("6. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			fmt.Println("\nReproduciendo El lobo de Wall Street...")

		case 2:
			fmt.Println("\nReproduciendo Joker...")

		case 3:
			fmt.Println("\nReproduciendo Forest Gump...")

		case 4:
			fmt.Println("\nReproduciendo Yo Antes de Ti...")

		case 5:
			fmt.Println("\nReproduciendo En busca de la felicidad...")

		case 6:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION ACCION =================

func peliculasAccion() {

	var opcion int

	for {

		fmt.Println("\n========== PELICULAS ACCION ==========")
		fmt.Println("1. Avengers Endgame")
		fmt.Println("2. John Wick")
		fmt.Println("3. Rapidos y Furiosos")
		fmt.Println("4. The Batman")
		fmt.Println("5. Mission Impossible")
		fmt.Println("6. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			fmt.Println("\nReproduciendo Avengers Endgame...")

		case 2:
			fmt.Println("\nReproduciendo John Wick...")

		case 3:
			fmt.Println("\nReproduciendo Rapidos y Furiosos...")

		case 4:
			fmt.Println("\nReproduciendo The Batman...")

		case 5:
			fmt.Println("\nReproduciendo Mission Impossible...")

		case 6:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION TERROR =================

func peliculasTerror() {

	var opcion int

	for {

		fmt.Println("\n========== PELICULAS TERROR ==========")
		fmt.Println("1. El Conjuro")
		fmt.Println("2. Annabelle")
		fmt.Println("3. IT")
		fmt.Println("4. La Monja")
		fmt.Println("5. Halloween")
		fmt.Println("6. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			fmt.Println("\nReproduciendo El Conjuro...")

		case 2:
			fmt.Println("\nReproduciendo Annabelle...")

		case 3:
			fmt.Println("\nReproduciendo IT...")

		case 4:
			fmt.Println("\nReproduciendo La Monja...")

		case 5:
			fmt.Println("\nReproduciendo Halloween...")

		case 6:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION INFANTIL =================

func peliculasInfantiles() {

	var opcion int

	for {

		fmt.Println("\n========== PELICULAS INFANTILES ==========")
		fmt.Println("1. Toy Story")
		fmt.Println("2. Frozen")
		fmt.Println("3. Intensamente")
		fmt.Println("4. Coco")
		fmt.Println("5. Minions")
		fmt.Println("6. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			fmt.Println("\nReproduciendo Toy Story...")

		case 2:
			fmt.Println("\nReproduciendo Frozen...")

		case 3:
			fmt.Println("\nReproduciendo Intensamente...")

		case 4:
			fmt.Println("\nReproduciendo Coco...")

		case 5:
			fmt.Println("\nReproduciendo Minions...")

		case 6:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION CATALOGO =================

func verCatalogo() {

	var opcion int

	for {

		fmt.Println("\n========== CATALOGO STREAMING ==========")
		fmt.Println("1. Peliculas de Drama")
		fmt.Println("2. Peliculas de Accion")
		fmt.Println("3. Peliculas de Terror")
		fmt.Println("4. Peliculas Infantiles")
		fmt.Println("5. Series")
		fmt.Println("6. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			peliculasDrama()

		case 2:
			peliculasAccion()

		case 3:
			peliculasTerror()

		case 4:
			peliculasInfantiles()

		case 5:

			fmt.Println("\n========== SERIES DISPONIBLES ==========")
			fmt.Println("1. Stranger Things")
			fmt.Println("2. Breaking Bad")
			fmt.Println("3. Dark")
			fmt.Println("4. Wednesday")
			fmt.Println("5. The Walking Dead")
			fmt.Println("6. Regresar")
			fmt.Println("0. Salir")

		case 6:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION AGREGAR CONTENIDO =================

func agregarContenido() {

	var opcion int
	var nuevaPelicula string

	for {

		fmt.Println("\n========== AGREGAR CONTENIDO ==========")
		fmt.Println("1. Agregar pelicula o serie")
		fmt.Println("2. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:

			fmt.Print("Ingrese el nombre de la pelicula o serie: ")
			fmt.Scanln(&nuevaPelicula)

			fmt.Println("\nContenido agregado correctamente")
			fmt.Println("Nuevo contenido:", nuevaPelicula)

		case 2:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION USUARIOS =================

func usuariosPremium() {

	var opcion int

	usuarios := map[string]string{
		"Luis":   "Premium",
		"Maria":  "Basico",
		"Carlos": "Estandar",
		"Andrea": "Premium",
	}

	for {

		fmt.Println("\n========== USUARIOS DEL SISTEMA ==========")

		for usuario, plan := range usuarios {
			fmt.Printf("Usuario: %s | Plan: %s\n", usuario, plan)
		}

		fmt.Println("\n1. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION BUSCAR USUARIO =================

func buscarUsuario() {

	var opcion int
	var nombre string

	usuarios := map[string]string{
		"Luis":   "Premium",
		"Maria":  "Basico",
		"Carlos": "Estandar",
	}

	for {

		fmt.Println("\n========== BUSCAR USUARIO ==========")
		fmt.Println("1. Buscar usuario")
		fmt.Println("2. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:

			fmt.Print("Ingrese el nombre del usuario: ")
			fmt.Scanln(&nombre)

			plan, existe := usuarios[nombre]

			if existe {
				fmt.Printf("El usuario %s tiene el plan %s\n", nombre, plan)
			} else {
				fmt.Println("El usuario no existe")
			}

		case 2:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= FUNCION LO MAS DESTACADO =================

func loMasDestacado() {

	var opcion int

	for {

		fmt.Println("\n========== LO MAS DESTACADO ==========")
		fmt.Println("Pelicula recomendada: En busca de la felicidad")
		fmt.Println("Informacion:")
		fmt.Println("Una pelicula inspiradora que enseña")
		fmt.Println("la importancia de nunca rendirse,")
		fmt.Println("luchar por los sueños y valorar la familia.")

		fmt.Println("\n1. Regresar")
		fmt.Println("0. Salir")
		fmt.Print("Seleccione una opcion: ")
		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			return

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

// ================= MENU PRINCIPAL =================

func mostrarMenu() {

	fmt.Println("\n========================================")
	fmt.Println("        STREAMFLIX - PLATAFORMA")
	fmt.Println("========================================")
	fmt.Println("1. Ver catalogo")
	fmt.Println("2. Agregar contenido")
	fmt.Println("3. Ver usuarios")
	fmt.Println("4. Buscar usuario")
	fmt.Println("5. Lo mas destacado")
	fmt.Println("0. Salir")
	fmt.Print("Seleccione una opcion: ")
}

// ================= FUNCION MAIN =================

func main() {

	var opcion int

	for {

		mostrarMenu()

		fmt.Scanln(&opcion)

		switch opcion {

		case 1:
			verCatalogo()

		case 2:
			agregarContenido()

		case 3:
			usuariosPremium()

		case 4:
			buscarUsuario()

		case 5:
			loMasDestacado()

		case 0:
			fmt.Println("\nGracias por usar StreamFlix")
			return

		default:
			fmt.Println("\nOpcion invalida")
		}
	}
}

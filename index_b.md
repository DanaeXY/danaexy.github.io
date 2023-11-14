# MARKDOWM

## Proyectos personales

Página hecha en markdown
- Código Java
  
``` java

public class ejercicio1 {

    public static void main(String[] args) {
        Scanner teclado = new Scanner(System.in);

        int anhoUsuario;
        
        System.out.println("Voy a decirte tu signo en el horóscopo chino");
        System.out.println("¿En qué año naciste? ");
        anhoUsuario = teclado.nextInt();
        int resto = anhoUsuario%12;

        switch (resto) {
            case 0:
                System.out.println("Tu signo es Mono");
                break;
            case 1:
                System.out.println("Tu signo es Gallo");
                break;
            case 2:
                System.out.println("Tu signo es Perro");
                break;
            case 3:
                System.out.println("Tu signo es Cerdo");
                break;
            case 4:
                System.out.println("Tu signo es Rata");
                break;
            case 5:
                System.out.println("Tu signo es Buey");
                break;
            case 6:
                System.out.println("Tu signo es Tigre");
                break;
            case 7:
                System.out.println("Tu signo es Conejo");
                break;
            case 8:
                System.out.println("Tu signo es Dragón");
                break;
            case 9:
                System.out.println("Tu signo es Serpiente");
                break;
            case 10:
                System.out.println("Tu signo es Caballo");
                break;
            case 11:
                System.out.println("Tu signo es Cabra");
                break;
            default:
            System.out.println("No has introducido un número correcto");
                break;
        }

    teclado.close();
    }
}

```

# practica
public class Main {
    public static void main(String[] args) {
        //calcular cant de jugadores de reservas, son los que estan despues de la posicion 11
        seleccion argentina = new seleccion("Argentina");
        argentina.addjugador(new jugador("lionel", "messi", 10,"delantero"));
        argentina.addjugador(new jugador("emiliano", "martinez", 23,"portero"));
        argentina.addjugador(new jugador("geronimo", "rulli", 12,"portero"));
        argentina.addjugador(new jugador("franco", "armani", 1,"portero"));
        argentina.addjugador(new jugador("cristian", "romero", 13,"defensa central"));
        argentina.addjugador(new jugador("lisandro", "martinez", 2,"defensa central"));
        argentina.addjugador(new jugador("facundo", "medina", 19,"defensa central"));
        argentina.addjugador(new jugador("nehuen", "perez", 13,"defensa central"));
        argentina.addjugador(new jugador("german", "pezzella", 7,"defensa central"));
        argentina.addjugador(new jugador("nicolas", "otamendi", 19,"defensa central"));
        argentina.addjugador(new jugador("nicolas", "tagliafico", 3,"lateral izquierdo"));
        argentina.addjugador(new jugador("nahuel", "molina", 21,"lateral derecho"));
        argentina.addjugador(new jugador("gonzalo ", "montiel", 4,"lateral derecho"));
        argentina.addjugador(new jugador("guido ", "rodriguez", 18,"pivote"));
        argentina.addjugador(new jugador("leandro ", "paredes", 5,"pivote"));
        argentina.addjugador(new jugador("alexis ", "mcallister", 15,"mediocentro"));
        argentina.addjugador(new jugador("giovanni ", "lo celso", 20,"mediocentro"));
        argentina.addjugador(new jugador("enzo ", "fernandez", 14,"mediocentro"));
        argentina.addjugador(new jugador("thiago ", "almada", 8,"mediocentro ofensivo"));
        argentina.addjugador(new jugador("papu ", "gomez", 17,"extremo izquierdo"));
        argentina.addjugador(new jugador("rodrigo ", "de paul", 8,"mediocentro"));
        jugador jugador1 = new jugador("rodrigo", "de paul", 8, "mediocentro");
        argentina.addjugador(jugador1);
        jugador jugador2 = new jugador ("juan", "perez", 9,"mediocampista");

        System.out.println("los jugadores en la posicion indicada: "+ argentina.cantjugadoresPosicion("delantero"));
        argentina.cantReserva();
        System.out.println("el nomnbre del jugador es :" + jugador2.getNombre());


# FFTA-USACh-G-OR-BOR
# Diego, lo que voy a enviar son class que no se ejecuta, solamente son sugerencia que debería estar ya que tengo un problema para verificar los parámetro de Java
# Es un fragmento de batalla sin procesar con los indicaciones que debe tener

package Controladores;

/*import static java.util.Collections.list;
import Controladores.Coordenada;
import Controladores.jugador;
import Controladores.escenario;*/
/**
 *
 * @author Martín, parte contructiva
 */
public class Batalla /* imprements jugador and escenario*/{
    private int jugador;
    private int escenario;
    private int turno;
    
    /**
     *
     */
    public Batalla(){
        ataqueCorta();
        ataqueLargo();
        desplazar();
        habilidad();
        terminarTurno();
        terminarBatalla();
        
    }
    public static void main(String[] args) {
        // TODO code application logic here
    }

    public static void terminarTurno() {
        /*ActionListener(clickBatalla)*/
        /*si existe opción de Ataque de Largo o Corta distancia*/
        /*si la int Movimiento del equipo es cero*/
        /*se genera una nueva coordenada para el equipo en el fin del turno 
        list Coordenada[][] = new Coordenada();*/
        /*cambia las estadistica como la vida, mana, energía, inventario, tec.
        si pregunta que, en caso de sobrar movimiwnto, saltar turno por parte
        del uusario*/
    }

    public static void terminarBatalla() {
        /*Si int jugadores de un equipo es 0*/
        /*Si boolean equipo(ya sea del enemigo o de lo nuestro) es false;*/
    }

    private void ataqueCorta() {
        /*la parte de ataque corta se debe por la secuencia dado en la
        secuencia*/
        /*el modo de ataque corta es de método "piedra, papel y tijera"*/
    }

    private void ataqueLargo() {
        /*la parte de ataque larga se debe por la secuencia dado en la
        secuencia*/
        /*Un ataque de distancia como arco gasta munición
        al de un mago gasta maná
        y del ninja, quizas, a ambos*/
    }

    private void desplazar() {
        /*Ahi al cambiar el lugar, debe cambiar la coordenada de
        cada personaje ejecutado por el jugador*/
        /*En el escenario, debe venir importado y extendido los terrenos*/
    }

    private void habilidad() {
        /*se puede elegir a los personaje su habilidad especial en caso de
        cambiar la opción de ataque corta o larga en la batalla*/
    }
    
}


import javax.swing.JOptionPane;

public class RandomGuess {
    public static void main(String[] args) {
        // Solicităm utilizatorului să-și gândească un număr între 1 și 10
        String input = JOptionPane.showInputDialog("Gândește-ți un număr între 1 și 10 și apasă OK.");

        // Generăm un număr aleatoriu între 1 și 10
        int randomNumber = 1 + (int) (Math.random() * 10);

        // Convertim răspunsul utilizatorului într-un număr întreg
        int userGuess = Integer.parseInt(input);

        // Afișăm numărul generat aleatoriu și dacă utilizatorul a ghicit sau nu
        JOptionPane.showMessageDialog(null, "Numărul generat este: " + randomNumber + "\n" +
                (userGuess == randomNumber ? "Ai ghicit! Bravo!" : "Nu ai ghicit. Mai încearcă!"));
    }
}

// PROBLEMA 2

public class CarlysMotto {
    public static void main(String[] args) {
        String motto = "Carly’s makes the food that makes it a party.";
        System.out.println(motto);
    }
}

public class CarlysMotto2 {
    public static void main(String[] args) {
        String motto = "Carly’s makes the food that makes it a party.";
        int length = motto.length();

        // Afișăm un rând de steluțe deasupra și sub motto
        for (int i = 0; i < length + 4; i++) {
            System.out.print("*");
        }
        System.out.println();

        // Afișăm motto-ul înconjurat de steluțe
        System.out.println("* " + motto + " *");

        // Afișăm un rând de steluțe deasupra și sub motto
        for (int i = 0; i < length + 4; i++) {
            System.out.print("*");
        }
        System.out.println();
    }
}

// PROBLEMA 3

public class SammysMotto {
    public static void main(String[] args) {
        String motto = "Sammy’s makes it fun in the sun";
        System.out.println(motto);
    }
}

public class SammysMotto2 {
    public static void main(String[] args) {
        String motto = "Sammy’s makes it fun in the sun";
        int length = motto.length();

        // Afișăm o linie de caractere 'S' deasupra și sub motto
        for (int i = 0; i < length + 4; i++) {
            System.out.print("S");
        }
        System.out.println();

        // Afișăm motto-ul înconjurat de caractere 'S'
        System.out.println("S " + motto + " S");

        // Afișăm o linie de caractere 'S' deasupra și sub motto
        for (int i = 0; i < length + 4; i++) {
            System.out.print("S");
        }
        System.out.println();
    }
}


# fauzi-program-java
file program java ahmad fauzi

package perulangan;

public class do_while {

    void doowhile() {
        int a = 0;
        do {
            int b = 5;
            do {
                System.out.print(" ");
                b--;
            } while (b >= a);
            int c = 0;
            do {
                System.out.print("* ");
                c++;
            } while (c <= a);
            System.out.println();
            a++;
        } while (a <= 4);
    }

}


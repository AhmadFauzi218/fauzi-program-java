# fauzi-program-java
file program java ahmad fauzi

package perulangan;

public class fo_perulang {

    int rows = 5, i = 1, j = 1,t;
    int max_spasi = rows - 1;

    void tampil() {
        while (i <= rows) {
            t = max_spasi;
            while (t >= 0) {
                System.out.print(" ");
                t--;
            }
            while (j <= i) {
                System.out.print("* ");
                j++;
            }

            System.out.println();
            i++;
            j = 1;
            max_spasi--;
        }
    }

}


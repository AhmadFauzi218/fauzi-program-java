# fauzi-program-java
file program java ahmad fauzi

package perulangan;

public class ulang {
     int tinggi = 5;//hitung jumlah bintang dari user
     
    void bin(){
        // menghitung jumlah tinggi pyramid
        for (int i = 1; i <= tinggi; i++){    
             //hitung jumlah spasi perbaris
            for (int j = tinggi; j > i; j--){            
                System.out.print(" ");             
                } 
             //hitug jumlah bintang perbaris
            for (int k = 1; k <=i; k++){               
                System.out.print(k+" ");            
            } 
            //membuat baris baru
            System.out.println();
            }
        }
    } 


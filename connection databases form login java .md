# fauzi-program-java
file program java ahmad fauzi

package latihanjavalks;
import java.sql.*;

public class config {
    private static Connection mysqlconfig;
    public static Connection configDB()throws SQLException{
        try{
            String Url="jdbc:mysql://localhost:3306/mahasiswa";
            String User="root";
            String pass="";
            DriverManager.registerDriver(new com.mysql.jdbc.Driver());
            mysqlconfig=DriverManager.getConnection(Url, User, pass);
        }catch(Exception e){
            System.out.println("koneksi gagal" +e.getMessage());
        }
        return mysqlconfig;
    }
}

# fauzi-program-java
file program java ahmad fauzi


public class ulangan {
    String password,username;
    
   void tampil(){
       
       if(username.isEmpty()){
           System.out.println("error");
       }else if(password.isEmpty()){
           System.out.println("error");
       }else if(!username.equals("fauzi")) {
           System.out.println( "username salah");
       }else if(!password.equals("1234567")){
           System.out.println("password salah");
       }else{
           System.out.println("login berhasil");
       }
   }
}

import java.util.*;
import java.io.BufferedReader;
import java.io.File;
import java.io.FileReader;
import java.io.FileInputStream;
import java.io.InputStreamReader;
import java.io.IOException;

class input_text{
  public static void main(String[] args){

    try{
      File file = new File("input.txt");
      BufferedReader br = new BufferedReader(new InputStreamReader(new FileInputStream(file),"UTF-8"));
      String[] data = new String[10000];
      int data_line = 0;
      //data read and set and output
      while((data[data_line] = br.readLine()) != null){
        System.out.println(data[data_line]);
        data_line++;
      }
      //data_line output
      System.out.println(data_line);
      br.close();
    }catch(IOException e){
      System.out.println("no file");
      return;
    }
  }
}

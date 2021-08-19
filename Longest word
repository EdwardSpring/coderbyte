import java.util.*; 
import java.io.*;

class Main {

  public static String LongestWord(String sen) {
    // code goes here  
    String[] words = sen.split(" ");
		
		
		for (int i = 0; i < words.length - 1; i++) {
			for (int j = 0; j < (words.length - 1) - i; j++) {
				if(words[j].length() < words[j+1].length()) {
					String temp = words[j+1];
					words[j+1] = words[j];
					words[j] = temp;
				}
				
			}
		}
		return words[0];
  }

  public static void main (String[] args) {  
    // keep this function call here     
    Scanner s = new Scanner(System.in);
    System.out.print(LongestWord(s.nextLine())); 
  }

}

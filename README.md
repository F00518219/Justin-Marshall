# Justin-Marshall
Homework 1
public class Main {
  public static void main(String[] args) {
    int count = 0;
    String strBible = "Mark";
    strBible = strBible.toLowerCase();

    for (int i = 0; i < strBible.length(); i++) {
      if (strBible.charAt(i) == 'a' || strBible.charAt(i) == 'e' || strBible.charAt(i) == 'i'
          || strBible.charAt(i) == 'o' || strBible.charAt(i) == 'u') {
        count++;
      }
    }
    System.out.println("There are " + count + " vowels in your New Testament chapter title!");
  }
}

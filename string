def count_occurrences(s, char):
    return s.count(char)


s = "hello world"
char = 'l'
print(count_occurrences(s, char))  # Output: 3




//Reverse String

public class StringOperations {

    public static String reverseString(String s) {
        return new StringBuilder(s).reverse().toString();
    }

    public static void main(String[] args) {
        String s = "hello world";
        System.out.println(reverseString(s));  // Output: "dlrow olleh"
    }
}



//Check if a String is a Palindrome:


public class StringOperations {

    public static boolean isPalindrome(String s) {
        return s.equals(new StringBuilder(s).reverse().toString());
    }

    public static void main(String[] args) {
        String s = "madam";
        System.out.println(isPalindrome(s));  // Output: true
    }
}



// Remove Lowercase Characters from a String:
public class StringOperations {

    public static String removeLowercase(String s) {
        StringBuilder sb = new StringBuilder();
        for (char ch : s.toCharArray()) {
            if (!Character.isLowerCase(ch)) {
                sb.append(ch);
            }
        }
        return sb.toString();
    }

    public static void main(String[] args) {
        String s = "Hello World";
        System.out.println(removeLowercase(s));  // Output: "H W"
    }
}

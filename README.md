   public class SimpleArray {
    public static void main(String[] args) {
        // Create an array of integers with a capacity of 5
        int[] array = new int[5];

        // Add elements to the array
        array[0] = 10;
        array[1] = 20;
        array[2] = 30;
        array[3] = 40;
        array[4] = 50;

       
        System.out.println("Element at index 0: " + array[0]); // Output: Element at index 0: 10
        System.out.println("Element at index 1: " + array[1]); // Output: Element at index 1: 20
        System.out.println("Element at index 2: " + array[2]); // Output: Element at index 2: 30
        System.out.println("Element at index 3: " + array[3]); // Output: Element at index 3: 40
        System.out.println("Element at index 4: " + array[4]); // Output: Element at index 4: 50
    }
}


# Array-Examples-1D-2D-Multi-dimensional-
Array Examples (1D, 2D, Multi-dimensional)

1D Array:

public class OneDArray {
    public static void main(String[] args) {
        int[] arr = {1, 2, 3, 4, 5};
        System.out.println("1D Array Elements:");
        for (int num : arr) {
            System.out.print(num + " ");
        }
    }
}

2D Array:

public class TwoDArray {
    public static void main(String[] args) {
        int[][] arr = {{1, 2}, {3, 4}};
        System.out.println("2D Array Elements:");
        for (int i = 0; i < arr.length; i++) {
            for (int j = 0; j < arr[i].length; j++) {
                System.out.print(arr[i][j] + " ");
            }
            System.out.println();
        }
    }
}

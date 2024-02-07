# Lab 3 Report  
## Part 1 - Bugs  
* ```
  # failure-inducing input
  @Test
  public void testReveresedInPlaceFullArray() {
    int[] input = {1, 2 ,3 ,4};
    ArrayExamples.reverseInPlace(input);
    assertArrayEquals(new int[]{4, 3, 2, 1}, input);
  }
  ```
* ```
  # input that does not induce failure
  @Test 
	public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}
  ```
* 
* ```
  # before code-fix
  static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
  }
  ```
  ```
  # after code-fix
  static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length/2; i += 1) {
      int temp = arr[i];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length - i - 1] = temp;
    }
  }
  ```
  This fixes the code as it creates a temp variable that holds the value of the index where the array is being reversed.
  This allows the for loop to reverse rather than the array being mirrored. Using the temp variable and changing it
  in the same iteration means that the loop only lasts half of the array length.
## Part 2 - Researching Commands  
* __grep__ s


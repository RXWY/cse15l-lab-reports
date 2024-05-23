# Part 1
1. A failure-inducing input for ArrayExamples, JUnit Test -> ArrayTests
```
 @Test
  public void testReversed() {
    int[] input1 = { 1, 2, 4};
    assertArrayEquals(new int[]{ 4, 2, 1 }, ArrayExamples.reversed(input1));
  }
```
2. An input that doesn't induce a failure for ArrayExamples, JUnit Test -> ArrayTests
```
  @Test 
    public void testReverseInPlace() {
    	int[] input1 = { 3 };
   	 ArrayExamples.reverseInPlace(input1);
    	assertArrayEquals(new int[]{ 3 }, input1);
	}
```
3. Error message: The symptom demonstrating one test have passed but another isn't.
![Image](https://rxwy.github.io/cse15l-lab-reports/labreport3/1.png)
4. The segment where the bug is at.
Before modification
```
static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
```
After modification
```
static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    return newArray;
  }
```
5. Explanation
The original code basically returns the original list input. While the revised code would be able to return
the array in reverse sorted order, which have been through the for loop to sort the list in reverse order.
# Part 2



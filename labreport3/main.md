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
4. The segment where the bug is at. \
* Before modification
```
static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
```
* After modification
```
static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    return newArray;
  }
```
5. Explanation:
```
The original code basically returns the original list input. While the revised code would be able to return
the array in reverse sorted order, which have been through the for loop to sort the list in reverse order.
```
# Part 2
1. I found ```less -v``` quite interesting, first of all, it works depending on the system environment, 
some would think it is ```-V``` Which displays the current version of the command, but this command would allow you to open an editor for the current file instead. \
[Work Cited](https://man7.org/linux/man-pages/man1/less.1.html)
2. ```less -B``` is another interesting command, it is the switch for the auto buffer(space allowance) for a file,
and by called up this command, under default conditions, it will disable auto buffering(space filling) and
instead saving some memory allocation to the file as there are less space chars to display. However it will
result in distortion in text or a "text image". \
[Work Cited](https://man7.org/linux/man-pages/man1/less.1.html)
3. ```less -d``` does a very abstract behavior on error messages, specifically on dumb terminals, it limits error messages from displaying, a dumb terminal is a terminal that returns errors in its original forms without any explanation or encodings. \
[Work Cited 1](https://en.wikipedia.org/wiki/Computer_terminal)
[Work Cited 2](https://man7.org/linux/man-pages/man1/less.1.html)

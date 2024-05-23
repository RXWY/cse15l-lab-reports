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
3. d
   
# Part 2

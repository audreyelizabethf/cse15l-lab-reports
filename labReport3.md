# Lab Report 3 - Bugs and Commands

## Part 1
`reverseInPlace(int[] arr)`
#### 1. A failure-inducing input for the buggy program as a **JUnit test**
```
@Test
public void testReverseInPlace1(){
  int[] input = { 1, 2, 3 };
  ArrayExamples.reverseInPlace(input1);
  assertArrayEquals(new int[]{ 3, 2, 1 }, input1);
}
```
#### 2. An input that *doesn't* induce a failure
```
@Test 
	public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}
```

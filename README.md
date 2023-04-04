# string-helper-exercise-template

Write a StringHelper class that contains a method called Reverse that takes a string as input and returns the reversed version of the string. The StringHelper class should also contain a method called IsPalindrome that takes a string as input and returns a boolean value indicating whether the input string is a palindrome or not.

Then, write unit tests to ensure that both methods are working correctly. Your tests should cover a range of scenarios, including:

1. Testing for correct reversal of a simple string.
2. Testing for correct reversal of a longer string with special characters and spaces.
3. Testing for correct handling of null input values in both methods.
4. Testing for correct handling of empty input strings in both methods.
5. Testing for correct identification of a palindrome string.
6. Testing for correct identification of a non-palindrome string.
Here's a sample code structure to get you started:

```
public class StringHelper {
  public string Reverse(string input) {
    // TODO: Implement string reversal
  }

  public bool IsPalindrome(string input) {
    // TODO: Implement palindrome identification
  }
}

[TestFixture]
public class StringHelperTests {
  [Test]
  public void TestReverse() {
    // TODO: Write test for string reversal
  }

  [Test]
  public void TestIsPalindrome() {
    // TODO: Write test for palindrome identification
  }
}

```

Your task is to complete the TODO comments with the appropriate code to implement the Reverse and IsPalindrome methods and write the unit tests to verify their correctness. Good luck!

| **Assertion/Annotation**          | **Simple Reference**                                                                             |
|-----------------------------------|-------------------------------------------------------------------------------------------------|
| `@Test`                           | Marks a method as a test case.                                                                  |
| `@BeforeEach`                     | Runs before each test case.                                                                     |
| `@AfterEach`                      | Runs after each test case.                                                                      |
| `@BeforeAll`                      | Runs once before all test cases in the class.                                                   |
| `@AfterAll`                       | Runs once after all test cases in the class.                                                    |
| `@Disabled`                       | Disables a test method or class.                                                                |
| `assertEquals(expected, actual)`  | Checks if two values are equal.                                                                 |
| `assertNotEquals(expected, actual)` | Checks if two values are not equal.                                                            |
| `assertTrue(condition)`           | Checks if a condition is true.                                                                  |
| `assertFalse(condition)`          | Checks if a condition is false.                                                                 |
| `assertNull(object)`              | Checks if an object is null.                                                                    |
| `assertNotNull(object)`           | Checks if an object is not null.                                                                |
| `assertArrayEquals(expectedArray, actualArray)` | Checks if two arrays are equal.                                                    |
| `assertThrows(exceptionClass, executable)` | Verifies that a block of code throws the specified exception.                          |
| `assertDoesNotThrow(executable)`  | Verifies that a block of code does not throw any exception.                                     |
| `assertTimeout(Duration, executable)` | Ensures that a block of code completes within the specified timeout.                         |
| `assertAll(executables...)`       | Groups multiple assertions into a single test case.                                             |
| `@DisplayName("Custom Name")`     | Sets a custom display name for a test case.                                                     |
| `@Tag("tagName")`                 | Assigns a tag to a test case for filtering.                                                     |
| `@RepeatedTest(value)`            | Runs the test repeatedly for the specified number of times.                                     |
| `@ParameterizedTest`              | Marks a method as a parameterized test case.                                                    |
| `@ValueSource`                    | Provides an array of values for a parameterized test.                                           |
| `@CsvSource`                      | Provides multiple CSV values for a parameterized test.                                          |
| `@CsvFileSource`                  | Provides CSV values from an external file for a parameterized test.                             |
| `@EnumSource`                     | Provides all constants of an enumeration for a parameterized test.                              |
| `@MethodSource`                   | Provides test arguments from a static method or factory method.                                 |
| `@TempDir`                        | Creates and provides a temporary directory for a test case.                                     |
| `@Nested`                         | Groups related test cases in an inner class.                                                    |
| `@ExtendWith`                     | Registers a custom extension to extend test functionality.                                      |
| `@Timeout`                        | Fails a test if it exceeds the specified time limit.                                            |
| `@TestInstance`                   | Controls test instance lifecycle (`PER_CLASS` or `PER_METHOD`).                                 |

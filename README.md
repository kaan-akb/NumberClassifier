# NumberClassifier
# Number Classifier

The **NumberClassifier** class is a Java class that provides a method for classifying numbers into three categories: Positive, Negative, or Zero.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Method](#method)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The `NumberClassifier` class is designed to help you quickly determine the nature of a given number. It employs a basic decision-making process to classify numbers into three categories based on their sign: Positive, Negative, or Zero.

## Usage

To use the `NumberClassifier` class, follow these steps:

1. **Instantiate the `NumberClassifier` class:**

   ```java
   NumberClassifier classifier = new NumberClassifier();
   ```
   
2. **Call the classify method with a number as an argument:**

  ```java 
  int number = 42;
  String classification = classifier.classify(number);
   ```
The classify method will return a String indicating whether the number is Positive, Negative, or Zero.

## Method

```java
classify(int number): String
```

This method takes an integer number as input and returns a String indicating the classification of the number. The possible return values are:

"Positive" if the number is greater than 0.
"Negative" if the number is less than 0.
"Zero" if the number is equal to 0.

Example:

Here's a simple example of using the NumberClassifier class:

```java
NumberClassifier classifier = new NumberClassifier();
int number = 10;
String result = classifier.classify(number);
System.out.println("The number " + number + " is " + result);
```

Output:
```java
The number 10 is Positive
```

## Contributing

We welcome contributions to improve the NumberClassifier project! To contribute:

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them with descriptive commit messages.
5. Push your changes to your GitHub repository.
6. Submit a pull request to the main repository.

For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the Eclipse Public License 2.0. See the LICENSE file for details.




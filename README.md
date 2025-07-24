# CSES Problem Set Solutions

This repository contains a structured folder organization for solving [CSES Problem Set](https://cses.fi/problemset/list/) problems.

## 📁 Structure

The problems are organized into categories matching the CSES website structure:

```
CSES_Problems/
├── Introductory_Problems/
├── Sorting_and_Searching/
├── Dynamic_Programming/
├── Graph_Algorithms/
├── Range_Queries/
├── Tree_Algorithms/
├── Mathematics/
├── String_Algorithms/
├── Geometry/
├── Advanced_Techniques/
├── Sliding_Window_Problems/
├── Interactive_Problems/
├── Bitwise_Operations/
├── Construction_Problems/
├── Advanced_Graph_Problems/
├── Counting_Problems/
├── Additional_Problems_I/
└── Additional_Problems_II/
```

Each category contains individual problem folders, and each problem folder contains a `Solution.java` template file.

## 🚀 Getting Started

1. Navigate to any problem folder:
   ```bash
   cd CSES_Problems/Introductory_Problems/Weird_Algorithm/
   ```

2. Edit the `Solution.java` file to implement your solution using the FastReader class:
   ```java
   import java.io.*;
   import java.util.*;

   public class Solution {
       static class FastReader {
           // FastReader implementation (already included in template)
       }

       public static void main(String[] args) {
           FastReader fr = new FastReader();
           
           // Example usage:
           int n = fr.nextInt();           // Read integer
           long x = fr.nextLong();         // Read long
           double d = fr.nextDouble();     // Read double
           String s = fr.next();           // Read string (token)
           String line = fr.nextLine();    // Read full line
           
           // TODO: Implement solution for [Problem Name]
       }
   }
   ```

3. Compile and run your solution:
   ```bash
   javac Solution.java
   java Solution
   ```

## ⚡ FastReader Class

Each template includes a high-performance `FastReader` class optimized for competitive programming:

### Key Features:
- **Faster Input**: Uses `BufferedReader` instead of `Scanner` for significantly better performance
- **Multiple Data Types**: Support for `int`, `long`, `double`, `String`, and full line reading
- **Tokenization**: Efficient string tokenization using `StringTokenizer`

### Usage Examples:
```java
FastReader fr = new FastReader();

// Reading single values
int n = fr.nextInt();
long bigNumber = fr.nextLong();
double decimal = fr.nextDouble();
String word = fr.next();
String fullLine = fr.nextLine();

// Reading arrays
int[] arr = new int[n];
for (int i = 0; i < n; i++) {
    arr[i] = fr.nextInt();
}

// Reading multiple values in one line
int a = fr.nextInt();
int b = fr.nextInt();
int c = fr.nextInt();
```

## 📊 Statistics

- **Total Problems**: 400
- **Categories**: 19
- **Language**: Java
- **Input Method**: FastReader (optimized for competitive programming)

## 🔗 Links

- [CSES Problem Set](https://cses.fi/problemset/list/)
- [CSES Documentation](https://cses.fi/book/)

## 📝 Notes

- Each `Solution.java` file includes a complete FastReader implementation
- FastReader is significantly faster than Scanner for large inputs
- Problems are organized exactly as they appear on the CSES website
- You can add additional files (input.txt, output.txt, etc.) to each problem folder as needed
- All templates include necessary imports: `java.io.*` and `java.util.*`

## 🛠 Generated with

This structure was automatically generated using a Python web scraper that parses the CSES problem list and creates the corresponding folder structure with optimized Java templates. 
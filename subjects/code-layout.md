---
layout: default
title: Compiler, Setup and Printing
meta: Put extra info here, like if there any subjects required for this subject
---
{% include licence.md %}
---
### 8.1 Code indentation

Note that the commands in the block following the if statement (i.e. the lines after the curly brace, { ) are not written at the same level as the if statement itself. They should be **indented** slightly to the right. Indentation happens when you press the tab key, which is located to the left of q key. When the block ends with the closing curly brace, indentation ends as well. The closing curly brace } should be on the same level as the original `if` statement.

The use of indentation is crucial for the readability of program code. During this course and generally everywhere, you are expected to indent the code properly. IntelliJ helps with the correct indentation. You can easily indent your program by pressing shift, alt, and f simultaneously. It's also possible to select a whole section of code, and press tab to indent this whole section

### 8.2 else

If the truth value of the comparison is false, another optional block can be executed using the `else` command.

```java
int number = 4;

if (number > 5) {
    System.out.println("Your number is greater than five!");
} else {
    System.out.println("Your number is equal to or less than five!");
}
```

```output
Your number is equal to or less than five!
```

{% include week01/exercise/014.md %}
{% include week01/exercise/015.md %}
{% include week01/exercise/016.md %}
{: .exercises }
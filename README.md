# Function-Overloading

<h2>Theory</h2>
    <p>In C++, <strong>function overloading</strong> is a feature that allows you to have more than one function with the same name but different parameters. This is useful when you need to perform similar operations but with different types or numbers of arguments.</p>
    <p>For example, you might have a function that adds two integers and another that adds three integers. Function overloading allows you to use the same function name for both operations.</p>
<h3>Why Use Function Overloading?</h3>
<p>
    Function overloading enhances code readability and maintainability by allowing the same function name to be used for different tasks. This eliminates the need to create multiple function names for similar operations, thereby simplifying the code and making it easier to understand. For example, you might need a function to calculate the sum of two integers, two floating-point numbers, or three integers. Rather than creating separate functions like <code>addInt()</code> or <code>addFloat()</code>, function overloading allows you to use a single function name, such as <code>add()</code>, for all these operations.
</p>
<h3>Key Points to Remember</h3>
<ul>
    <li>Function overloading is resolved at compile-time, meaning that the compiler determines which function to call based on the arguments provided during the function call.</li>
    <li>Return type alone is not sufficient for function overloading. You cannot overload functions based solely on their return type.</li>
    <li>Overloaded functions must have different parameter lists (in terms of number, type, or order of parameters).</li>
</ul>

## Aim
<p>To demonstrate function overloading in C++ by creating multiple `add` functions with different parameters.</p>

 <h2>Algorithm</h2>
    <ol>
        <li>Start the program.</li>
        <li>Define two overloaded functions named <strong>add</strong>:</li>
        <ul>
            <li>The first <strong>add</strong> function takes two integers as arguments and returns their sum.</li>
            <li>The second <strong>add</strong> function takes three integers as arguments and returns their sum.</li>
        </ul>
        <li>In the <strong>main()</strong> function, call the first <strong>add</strong> function with two integers and store the result.</li>
        <li>Call the second <strong>add</strong> function with three integers and store the result.</li>
        <li>Display the results of both function calls.</li>
        <li>End the program.</li>
    </ol>
    
<h2>Aim</h2>
    <p>To demonstrate the concept of operator overloading in C++ by creating a program that adds two complex numbers using the overloaded <code>+</code> operator.</p>

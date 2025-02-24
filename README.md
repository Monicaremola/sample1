#include <iostream>

int main() {
    // Declare integer variables
    int a = 5;
    int b = 10;
    int sum, difference, product, quotient, remainder;

    // Perform arithmetic operations
    sum = a + b;
    difference = a - b;
    product = a * b;
    quotient = b / a;
    remainder = b % a;

    // Output the results
    std::cout << "a = " << a << std::endl;
    std::cout << "b = " << b << std::endl;
    std::cout << "Sum: " << sum << std::endl;
    std::cout << "Difference: " << difference << std::endl;
    std::cout << "Product: " << product << std::endl;
    std::cout << "Quotient: " << quotient << std::endl;
    std::cout << "Remainder: " << remainder << std::endl;

    return 0;
}

#include <iostream>
#include <limits>

int main() {
    // Output the size of short and double
    std::cout << "Size of short: " << sizeof(short) << " bytes" << std::endl;
    std::cout << "Size of double: " << sizeof(double) << " bytes" << std::endl;
    // Output the limits for short
    std::cout << "Limits for short:" << std::endl;
    std::cout << "  Minimum value: " << std::numeric_limits<short>::min() << std::endl;
    std::cout << "  Maximum value: " << std::numeric_limits<short>::max() << std::endl;
    // Output the limits for double
    std::cout << "Limits for double:" << std::endl;
    std::cout << "  Minimum value: " << std::numeric_limits<double>::min() << std::endl;
    std::cout << "  Maximum value: " << std::numeric_limits<double>::max() << std::endl;
    std::cout << "  Epsilon: " << std::numeric_limits<double>::epsilon() << std::endl;
    std::cout << "  Lowest value: " << std::numeric_limits<double>::lowest() << std::endl;
    std::cout << "  Digits: " << std::numeric_limits<double>::digits << std::endl;
    return 0;
}

// Size of short and double are the sizeof operator returns the size of the type in bytes.
//The limits for shorts is valued as std::numeric_limits<short>::min() which provides the minimum value for a short
//and std::numeric_limits<short>::max() provides the maximum value for a short.

//Limits for double is valued for std::numeric_limits<double>::min() provides the smallest positive value (not the minimum value) that a double can represent.
//std::numeric_limits<double>::max() provides the largest value that a double can represent.
//std::numeric_limits<double>::epsilon() provides the difference between 1 and the least value greater than 1 that is representable.
//std::numeric_limits<double>::lowest() provides the lowest finite value for a double.
//std::numeric_limits<double>::digits provides the number of decimal digits that can be represented in the machine.

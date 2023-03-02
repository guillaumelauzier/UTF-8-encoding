# UTF-8-encoding

In this example, we create a string text containing the text we want to convert to binary data. We then create a vector of uint8_t (8-bit unsigned integers) called binary_data. We use the vector constructor to convert the characters in text to their binary representation using UTF-8 encoding.

Finally, we output the binary data in hexadecimal format using a loop that iterates over each byte in the vector. The static_cast<int> is used to convert the uint8_t byte to an int so that it can be printed in hexadecimal format using std::hex.

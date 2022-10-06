# Function prototype of sqrt 
the sqrt()function takes a single argument and returns its square root.
the sqrt() function is defined in math.h header file
To find the square root of int,float or long double data types, you can explicitly convert the type to double using cast operator

int x = 0;
double result;
result = sqrt(double(x));

You can also use the sqrt() function to work specifically with float and sqrtl() to work with long double type.

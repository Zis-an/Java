There can be two types of conversion in Java : Explicit and Implicit.

Suppose, we know byte is small and integer is big. 

Now, if we try to place big integer into small byte it will not be possible.

But the reverse is possible. Means, small byte can be placed into big integer.

IT IS CALLED IMPLICIT CONVERSION.

    byte b = 127;
    int a = 12;
    a = b; --> IMPLICIT CONVERSION (Here byte value is becoming integer)


When conversion type is being typed inside parenthesis during conversion it is called EXPLICIT CONVERSION.


If we try to assign big integer value to small byte variable using EXPLICIT conversion or type casting, it will be counted using modulous.

    byte b = 127;
    int a = 257;
    b= (byte) a; ( 257 % 256 ) ( The remainder/result will be 1 ) ( It will divide the number by the byte range )

    Why 256 ? Because range of byte starts from -128 from 127






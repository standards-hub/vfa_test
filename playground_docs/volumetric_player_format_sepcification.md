## About This Book

This book is the specification for playing volumetric content back on any type of screen/device. This includes gaming consoles, XR headsets, smartphones/tv's and set-top boxes. This book will cover the compression standards, the container standards, and the interactive layer standards.

### Scope

This speciation will cover only how the volumetric audio, video, data, and interactive layer is organized for streaming and playback on a device. This specification doesn't go into standards for processing volumetric data for editing purposes.

### References

**Normative**

**The policy for reference lists is:**

VFA documents listed should have at least one approved version – draft-only docs should not be referenced. An exception exists for documents that will be approved with or after the referenced doc is approved (may be part of the same enabler package). In short – approved docs should not reference unapproved docs.
When a reference is made to a VFA specification, Volumetric Foundation Association with the TM symbol (™) should be used in the description.
The name + version (no date) for VFA specifications is generally sufficient – dates should be used only if there is a specific reason to limit the usage.
References to other affiliate docs should similarly provide sufficient information to uniquely determine the needed document and should provide the appropriate source information.
The URL for VFA material (new VFA and affiliate) should always be [add here].
Models to use: [REFLABEL] "Ref Title", Ref information (source, date, id), URL:http/// [VFADOC] "VFA Document Title",{ Version x.y,} Volumetric Foundation Association, VFA { }, URL:http//www.addhere

**Informative**

Check the version of the Dictionary you are using and update the reference below. Delete the [VFADICT] entry if the Dictionary is not used. In general, use the latest available version unless seeking alignment with an existing set of specifications.

### Terminology and Conventions

This specification will use the following keywords that indicate that a section must be implemented, is optional or is just for information purposes.

**INFORMATIVE**. This word means that the section is for information purposes and isn't meant to be implemented.


## Arithmetic-Operators

This document uses arithmetic operators that are still TBD.

### Numerical-Notation

<dl>
    <dt>Decimal notation</dt>
    <dd>Decimal notation is a way of representing numbers using the decimal numeral system. The decimal numeral system represents integers and non-integers using a base, or radix, of 10 with separate symbols, comprising the numbers "0" through "9", indicating each numerical value. A decimal numeral may also include decimal separators, most frequently the decimal point "." which represents the decimal radix separating the integer component from the fractional component of the number. Another frequently used decimal separator is the comma "," representing groups of digits within a 10^3 range.</dd>
    <dt>Hexadecimal notation</dt>
    <dd>Hexadecimal notation is a way of representing numbers using a hexadecimal numeral system. The hexadecimal numeral system represents numbers using a base, or radix, of 16, and each numeral is presented by 16 different symbols, comprising the 10 numbers from "0" through "9" in addition to 6 letters, upper case "A" through "F", or lower case "a" through "f". The prefix "0x" is frequently used to indicate a hexadecimal number.</dd>
    <dt>Binary notation</dt>
    <dd>Binary notation is a way of representing numbers using a binary numeral system. A binary numeral system represents numbers using a base, or radix, of 2 using the symbols "0" and "1". Each digit is referred to as a "bit". Because of the simplicity of the binary numeral system, it is the preferred system used by nearly all computers and computer-based devices.</dd>
    <dt>Byte</dt>
    <dd>A Byte is a unit of information that refers to a group of 8 bits. Historically the byte was the smallest number of bits to encode a single character of text in a computer, and before standardisation, a byte could represent different numbers of bits dependent on hardware implementation. Now a Byte is standardized to refer to exactly 8 bits and using the power of two encoding to represent 256 separate values of "0" through "255", with its symbol as the upper case letter "B". Due to potential ambiguity with "byte", an 8-bit sequence of bits is now standardized to refer to as an "octet", represented by the lower case "o". Bytes are also frequently grouped together into "words", with most modern architecture using 32bit or 64bit words, comprising 4 or 8 Bytes. 32bit and 64bit words are used to store bit sequences as well as the integer and floating-point values.</dd>
    <dt>"Endianness"</dt> 
    <dd>indicates whether a Byte, or octet, is encoded with the 1st bit in the sequence representing the least significant bit, little-endian, or whether the 1st bit in the sequence represents the most significant bit, big-endian. Little-endian is dominant in most current computing architectures, and big-endian is dominant network protocol architecture, such as Internet Protocol Suite (TCP/IP).</dd>
    <dt>Numerical values</dt>
    <dd>A Numerical Value is a number described by a Numerical System. For example, in Binary Notation, the symbol "0" represents the value 0, and the symbol "1" represents the value 1. In Hexadecimal Notation, the symbol "0x0A" represents the numerical value of 10. In Decimal notation, the symbol "10" represents the numerical value of 10.</dd>
</dl> 

### Definitions
<dl> 
    <dt>2D</dt> 
    <dd>Two-dimentional. Two spacial dimentions.</dd>
    <dt>3D Projection Matrix</dt> 
    <dd>A __Projection matrix__ that describes the transformation of a __3D__ point onto a __2D__ view.</dd>
    <dt>3D</dt>
    <dd>Three-dimentional. Three spacial dimentions.</dd>
    <dt>4D</dt>
    <dd>Four-dimentional. Three spacial dimentions, and one time dimention.</dd>
</dl>

### A

<dl>
    <dt>aac</dt>
    <dd> A file extension for an __AAC__ is an audio coding standard for lossy digital audio compression.</dd>
    <dt>AAC</dt> 
    <dd>Advanced Audio Coding.</dd>
    <dt>AOV</dt> 
    <dd>Angle of View. (See: __FOV__)</dd>
    <dt>Action</dt> 
    <dd>__User's__ response or election to conduct a pre-programmed operation.</dd>
    <dt>Application</dt> 
    <dd>A __Program__, i.e. an executable program, representing data files, and functions that performs a particular task or set of tasks.</dd>
    <dt>Application Management</dt>
    <dd>The direction of Setup functions of an __Application__ and maintenance of resources that enable __Trick Play__.</dd>
</dl>

</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>

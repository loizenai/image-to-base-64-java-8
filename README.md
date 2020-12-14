# Image to Base64 Java using Java 8 Encode Decode

https://loizenai.com/image-to-base64-java-8/

Tutorial: “Convert Image to Base64 Java – Java 8 Encode Decode an Image to Base64 tutorial”


 
With Java 8, Base64 has finally got its due. Java 8 now has inbuilt encoder and decoder for Base64 encoding. For some purpose like transfering an image through RestfulAPI or saving an image to a DataBase, We need Encoder (Decode) the image to Base64. In the tutorial, I will guide you how to use Java 8 for converting.

## Technologies – Java 8 Encode Decode an Image to Base64 tutorial
– Eclipse
– Java 8

Note: Prepare an Image at folder C:\\base64\\image.jpg

## java.util.Base64
This class consists exclusively of static methods for obtaining encoders and decoders for the Base64 encoding scheme. The implementation of this class supports the following types of Base64 as specified in RFC 4648 and RFC 2045:


 
1. Basic
Uses “The Base64 Alphabet” as specified in Table 1 of RFC 4648 and RFC 2045 for encoding and decoding operation. The encoder does not add any line feed (line separator) character. The decoder rejects data that contains characters outside the base64 alphabet.

2. URL and Filename safe
Uses the “URL and Filename safe Base64 Alphabet” as specified in Table 2 of RFC 4648 for encoding and decoding. The encoder does not add any line feed (line separator) character. The decoder rejects data that contains characters outside the base64 alphabet.

3. MIME
Uses the “The Base64 Alphabet” as specified in Table 1 of RFC 2045 for encoding and decoding operation. The encoded output must be represented in lines of no more than 76 characters each and uses a carriage return ‘\r’ followed immediately by a linefeed ‘\n’ as the line separator. No line separator is added to the end of the encoded output. All line separators or other characters not found in the base64 alphabet table are ignored in decoding operation.

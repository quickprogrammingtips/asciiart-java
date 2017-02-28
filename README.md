# ASCII Art Generator for Java

Please see [ASCII Art Generator Library in Java](http://www.quickprogrammingtips.com/java/ascii-art-generator-library-in-java.html) for more details on this library.

## Library Usage

```java
ASCIIArtGenerator artGen = new ASCIIArtGenerator();
artGen.printTextArt("Hello", ASCIIArtGenerator.ART_SIZE_MEDIUM);
```

```java
ASCIIArtGenerator artGen = new ASCIIArtGenerator();
artGen.printTextArt("Love is life!", ASCIIArtGenerator.ART_SIZE_SMALL,ASCIIArtFont.ART_FONT_MONO,"@");
```

## Sample Ouput

```
***     ***              ***   ***             
***     ***              ***   ***             
***     ***              ***   ***             
***     ***     *****    ***   ***     *****   
***     ***    *******   ***   ***    *******  
***********   ****  ***  ***   ***   **** ****
***********   ***   ***  ***   ***   ***   ***
***     ***   *********  ***   ***   ***   ***
***     ***   *********  ***   ***   ***   ***
***     ***   ***        ***   ***   ***   ***
***     ***   ****       ***   ***   **** ****
***     ***    ********  ***   ***    *******  
***     ***     *******  ***   ***     *****   
```
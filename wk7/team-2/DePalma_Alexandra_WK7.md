I've posted a picture of the proposed layout of my page separately. I chose this layout because I personally like the format of sites such as investopedia (econ major's best friend), where all of  information is arranged on the same page, with the option to link directly to certain subtopics.

Below, you will find potential (rough) content for my proposed blocks. The last few blocks can definitely be fleshed out some more and I'll return to them throughout the week based on feedback :) 

## Lempel-Ziv-Welch Compression

### Overview
*******************************************
_Lempel-Ziv-Welch (LZW)_ is a lossless data compression algorithm that was first published by Terry Welch in 1984 as a modification of the LZ77 and LZ78 compression algorithms developed by Jacob Ziv and Abraham Lempel. It is a dictionary based compression algorithm that is relatively simple for developers to implement and is widely used in GIF file formats.

### Exigency
*******************************************
Prior to the development of LZW, the most common form of compression was Huffman Coding. Huffman coding works by assigning probabilities to which letter will appear next in a given text. This has complications, as each text will have a different probability for certain letters. For example: “x” is one of the least common letters in standard texts, but would appear frequently in a math text. Another complication of Huffman’s method is the inherent dependence on both the English language and the probability of similar words occurring in different documents.
In response to these shortcomings, Lempel and Ziv developed a dictionary-based, adaptive compression method. Welch later improved upon this method. 

### How it Works
*******************************************
LZW is a dictionary-based compression method that takes advantage of repetitive patterns. Dictionary-based compression algorithms encode the data through referencing a dictionary. LZW is based on a standard character set dictionary of 256 characters. The data will be scanned and each time the algorithm encounters a substring of characters (ie: “th”, “tr”, “the”…) that substring will be added to the dictionary and encoded with a single number.  To decompress the data, LZW does not require the dictionary assignments that were featured in the compression. This is because both the encoding and the decoding programs utilize the same 256 characters. To decompress, LZW reads an assigned character and “looks up” the character in the dictionary to see what substring it was applied to. This process is repeated until the information is decoded.  

### US Patent Law & LZW
*******************************************
The initial patents for LZW were held by the Sperry Corporation, which later became Unisys Corporation. The first patent in the LZ family was filed in 1981. US patent 4,558,302 was issued to Terry Welch and Sperry Corporation on June 20,1983. 

The LZW method has been referenced in over one hundred additional patents, including ones as recent as 2013. Companies developing patented technologies that employ LZW include Unisys, Hewlett Packard, Apple, Google, Nielsen, Cisco, & Microsoft. 

Include patent examples
Why it was included in the patents
Possibly include why patents expire after 20 years---is that something people would be interested in knowing about?  Pro: could bring in discussion about innovation in technology, Con: could potentially turn this into a analysis of US Patent law


###LZW & The GIF Controversy
*******************************************
Starting in 1993, Unisys began attempting to collect licensing fees for the use of the LZW compression algorithm. 

+why collect fees--- money $$$
+how effective was this enforcement?
+ what was the innovative climate like at the time? was it stagnant (in terms of compression)?
+explain Usenet

Ultimately, a Usenet comp.graphics discussion, Thoughts on a GIF-replacement file format, culminuated int he creation of the Portable Network Grpahics (PNG) file in 1995. Undeterred by patents, the PNG file was expected to replace the GIF.

+discuss how PNG did not replace the GIF

### 2004 to Present
*******************************************
On June 20, 2003, twenty years after it was filed, Unisys's US patent for the LZW compression algorithm expired. Over the next year, patents filed in Canada, Japan, Germany, Italy, France, and the United Kingdom also expired. The GIF was (completely) free at last. 

+talk about use of GIFS in popular culture
+LZW's current applications outside of GIFS
+explore recent patents, the companies that hold them, and what the technologies are used for 


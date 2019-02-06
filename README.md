# LZW-Algorithm
IntroductionThe Lempel–Ziv–Welch  (LZW)  algorithm is  a  lossless  data  compression  algorithm.  LZW  is  an  adaptive  compression  algorithm  that  does  not  assume  prior  knowledge  of  the  input  data  distribution.  This algorithm works well when the input data is sufficiently large and there is redundancy in the data.Two examples  of  commonly used  file  formats  that  use LZW  compression  are  the  GIF  image  format  served  from  websites  and  the  TIFF  image  format.  LZW  compression  is  also  suitable  for  compressing  text files, and is the algorithm in the compress Unix file compression utility. This algorithm has two steps: 1. Encoding/Compressing 2. Decoding/Decompressing The  interesting  thing  is  that  the  encoding  table,  or  dictionary, computed  during  the  encoding  process  does not need to be explicitly transmitted. It can be regenerated from the coded/compressed data.

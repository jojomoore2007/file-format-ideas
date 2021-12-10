# Tree-Switching Huffman
Uses Huffman coding, but with one key difference- it can switch its character code trees.

It does this by prefixing standard character codes with a 0, and prefixing tree-switching control codes with a 1.

An example with "hello, world! this is an example of a huffman tree!":

h.
e.
l...
o..
,.
 .
w.
r.
d.
!.

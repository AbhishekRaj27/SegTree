# SegTree
General purpose segment tree library.

include SegmentTree.h

to construct a segment tree you need to specify the following:
<br /> a. The datatype of array for which the tree is being constructed.
<br />  b. an array or vector for which the tree is to be constructed.
<br />  c. a value that can be used to fill the extra nodes of the tree.
<br />  d. a function combine that specifies how the result of left and right child of a node
     should be used to generate the value of current node.

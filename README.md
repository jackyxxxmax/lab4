A.
B.
(1)1 8
   4 8
   4 8
   8 8
(2)sizeof(變數)，可以獲得變數所占用的位元組大小。
   而sizeof(char)固定為1，sizeof(int)在為4，
   sizeof(float)為4，sizeof(double)為8。
   sizeof(指標)，得到該指標本身的大小，在Win64為8。
   而sizeof(*指標)，得到指標指向的記憶體區塊的第一個
   item的型態大小。

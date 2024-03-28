# 
Logic Design:

In this project we have designed a palindrome detector that can operate on a sequence/string of maximum 3 characters (length = 3). Initially a 5 character sequence was considered and the logic diagram for that, shown in figure 4, was also drafted successfully. Both the logic designs can check a sequence of maximum length as well as sequences with lesser characters.
Each character ‘X’ in this sequence has five bits represented as X1-X5. Considering one bit slice, the 3 character bit slice design (figure 2), one bit from each of these 3 characters is stored in each flip-flop sequentially.
For a 3 character sequence the first bit and last bit are compared in every bit slice, therefore comparing all the bits of the first character with the bits of last character collectively in all the bit slices. If all these bits are the same it essentially means that the first and the last characters are the same, for a 3 character sequence this implies that the sequence is a palindrome. For a two character sequence there would only be a need to check the two bits from each character in each slice, this is done in a similar fashion.
For the outputs it a 3 character sequence is a palindrome we get a zero on Out-3 else a one. For a 2 character sequence we get this output on Out-2.

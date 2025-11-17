# Excel-sheet-column-number
class Solution(object):     def titleToNumber(self, s):         n=0         for c in s:n=n*26+ord(c)-64         return n         

# Reverse-string
class Solution(object):     def reverseString(self, s):         i,j=0,len(s)-1         while i&lt;j:             s[i],s[j]=s[j],s[i]             i+=1             j-=1

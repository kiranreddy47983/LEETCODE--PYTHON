# Reverse-Integer
class Solution(object):     def reverse(self, x):          s = (x > 0) - (x &lt; 0)          r = int(str(abs(x))[::-1]) * s          return r if -2**31 &lt;= r &lt;= 2**31 - 1 else 0

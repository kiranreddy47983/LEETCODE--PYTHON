# Rectangle-area
class Solution(object):     def computeArea(self, ax1, ay1, ax2, ay2, bx1, by1, bx2, by2):         A=(ax2-ax1)*(ay2-ay1)         B=(bx2-bx1)*(by2-by1)         x=max(0,min(ax2,bx2)-max(ax1,bx1))         y=max(0,min(ay2,by2)-max(ay1,by1))         return A+B-x*y

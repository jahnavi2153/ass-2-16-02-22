# ass-2-16-02-22
'''https://www.hackerrank.com/challenges/write-a-function/problem?isFullScreen=true&amp;h_r=next-challenge&amp;h_v=zen'''
def is_leap(year):
    if year%4==0 and year%100!=0 or year%400==0:
        return True
    else:
        return False
year = int(input())
print(is_leap(year))

output:
1990
False
False

#coding=utf-8

def getminsteps(floor,egg):
    if floor < 1 or egg < 1:
        return 0
    #备忘录，存储egg个鸡蛋，floor层楼条件下的最优化尝试次数
    b = [[0 for col in range(floor+1)] for raw in range(egg+1)]
#coding=utf-8

def getminsteps(floor,egg):
    if floor < 1 or egg < 1:
        return 0
    #����¼���洢egg��������floor��¥�����µ����Ż����Դ���
    b = [[0 for col in range(floor+1)] for raw in range(egg+1)]
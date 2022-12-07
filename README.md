# 新语言 OTao 
    中英文代码 语句
    解析计算表达式
    tree-walking  

# ABI TVM
    EN 
    执行
        .\enbitao.exe .\testxen.bl
    代码示例 testxen.bl:
        print 49 + 51 + 100;
        print 49 + 51 - 101;
        print 12345679 * 99999; 
        print 3 && 2;
        print 3 || 4;

    ZH 
    执行
        .\zhbitao.exe .\testxzh.bl
    中文代码示例 testxzh.bl:
        刷 49 加 51;
        刷 149 加 151;
        刷 49 乘 511 减 22 乘 100;
        刷 149 除 51;
        刷 222222222 乘 555555555;
        刷 2 与 2;
        刷 3 或 4;
    
    输出:
        100
		300
		22839
		2
		123456789876543210
		2
		7
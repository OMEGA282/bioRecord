# 在NSP-4后插入一个AID-mND序列

***
## 使用方法及原理
CRISPR/Cas9方法，在基因组上寻找一个位点，在NGG前将链切开，然后可以同源重组
***
## 材料
RNP复合物  
修复模板  
标记物

*如果你认为效率很高那么不用标记物也行*
***
## 步骤
### 设计修复模板
> 具体参照[benching连接](https://benchling.com/omega281/f/lib_lVafahe9-nsp-4/seq_FPKlC5Ez-nsp-4/edit)

要在nsp-4之后插入一段AID-mNG序列，本体就是AID-mNG，这里需要大量扩增，制造一个质粒用来PCR获得片段  
之后根据[这篇文献]( https://academic.oup.com/genetics/article/210/3/781/5931064 )中描述的不对称修复模板的方法进行操作
2. RNP复合物的制作
    1. |    成分    |    浓度    |
       |:--------:|:--------:|
       |  crRNA   | 20 ng/μL |
       | tracrRNA | 20 ng/μL |
        按照如上的表格配置2μL的混合液
   2. 在PCR仪中，从95℃递减到30℃步长5℃，每步保持30s
   3. |       成分       |  加入量  |
      |:--------------:|:-----:|
      |  Cas9 Buffer   | 2.5μL |
      |   61mM Cas9    | 0.5μL |
      | tracrRNA-crRNA |  1μL  |
        按照如上表配置RNP复合物混合液
   4. 22℃维持5分钟
   5. 可以保存在-20℃中一年
3. 制取长短链修复模板
4. 注射
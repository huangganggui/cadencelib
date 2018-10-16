# 说明

本工程用于树上科技硬件部管理封装焊盘

# pad命名规则

##钻孔型焊盘规则

###圆形焊盘 padMMcirNNd

pad:代表padstack
MM:代表焊盘外径
cir:代表焊盘外形为圆形circle
NN:代表焊盘孔径
d:代表钻孔孔壁必须上锡，可以用来导通各个层面

###正方形焊盘 padMMsqNNd

pad:代表padstack
MM：代表焊盘的边长
sq:代表焊盘外形为正方形
NN：代表焊盘孔径
d：代表钻孔孔壁必须上锡，可以用来导通各个层面

##表贴型焊盘规则

###长方形焊盘smdMMxNN

smd：代表它是一个smd的padstack，单一层面没有钻孔
MM:代表宽
x：数字分割符
NN：代表高
注意：一般MM<=NN
示例：宽0.6mm 长1.8mm 的长方形表贴焊盘可表示为：smd0r60x1r80.pad

###圆形焊盘 smdMMcir

smd：代表它是一个smd的padstack，单一层面没有钻孔
MM：代表焊盘的直径
cir代表圆形焊盘
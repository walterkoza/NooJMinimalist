# Transformaciones para convertir un léxico para mgpx y lpx  a nooj

para ítems léxicos ::  lexical items
 = for selection features
Rasgos categoriales: D, N, V
Rasgos de selección: =D, =N, =V...
Rasgos de licenciados o meta: -wh, -focus, -case
Rasgos de licenciadores o sonda: +wh, +focus, +case

:: -> ,


[ver] :: =D, =D, V 
[películas] :: D
[series] :: D
[videos] :: D

.dic
-> ver,V

-> D+V+D


.nog
D = <películas> | <series> | <videos> ;
V = <ver> ;





# Transformaciones para convertir un léxico para mghapx y lhapx a nooj

::  lexical items
 = for selection features
 <= for right incorporation
=> for left incorporation
==> for right affix hop
<== for left affix hop
<< for adjunction
>> for adjunction

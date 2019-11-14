Description:

Insertion Sortのアルゴリズムがj=2〜A.lengthと書かれていましたが、
access[]は0から始まっていると思い、j=1からと書き直しました。

Sort Checkerを足して、
きちんとsort出来ているかを見ています。

self deadlockをavoideするために、
/*growing phase*/ /*shrinking phase*/を少し書き換えています。


Running Example:

(base) kaptop:1101_s2pl kaho$ ./s2pl
Sorting Succeeded
Sorting Succeeded
ERROR: Undefined error: 0
Sorting Succeeded
ERROR: Undefined error: 0
ERROR: Undefined error: 0
123145522053120           lib.cc   44             lock
123145521516544           lib.cc   44             lock
(base) kaptop:1101_s2pl kaho$


質問:
Undefined error: 0
これ^ は、きちんと出来ているということですか？
また、どうして　Sorting Succeeded と　ERROR:〜　が
３回ずつ現れているのか分かりません。これで良いのでしょうか…？
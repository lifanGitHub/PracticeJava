###Full GC  
1.调用System.gc时，系统建议执行Full GC，但是不必然执行  
2.通过Minor GC后进入老年代的平均大小大于老年代的可用内存  

Java堆中的年轻代和老年代采用了不同的回收算法。  
年轻代采用了复制法；而老年代采用了标记-整理法  
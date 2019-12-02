# FlagCigar20191126
Question1-5：BAM FLAG
1.143:128+8+4+2+1 PEread，read比对不上参考序列，它的配对read同样比对不上参考序列，read1。
2.99:64+32+2+1 PEread，read比对不上参考序列，PE测序的另一条配对read反向互补后可以比对到参考序列。
3.516:512+4 read比对不上参考序列，该序列没有通过质量控制，低于过滤阈值。
4.2064:2048+16 read2，该read可能存在嵌合。
5.147:128+16+1 PEread，比对到副链，read2。
Question6-10：BAM CIGAR
6.14M2D31M:开头14bp比对上，然后的2bp序列删除，接着的31bp比对上。
7.3S6M1D5M:开头3bp被跳过，之后的6bp被比对上，然后有1bp序列删除，接着的5bp比对上。
8.6M14N5M:开头的6bp比对上，接着的14bp跳过参考序列，接着的5bp比对上。
9.7M5D8M2I14M:7M5D8M2I14M：开头的7bp比对上，接着的5bp序列删除，接着8bp比对上，接着有2bp序列插入，接着14bp比对上。
10.how long is the read with alignment CIGAR of 7M5D8M2I14M? 29bp。

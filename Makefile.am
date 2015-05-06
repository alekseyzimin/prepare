ACLOCAL_AMFLAGS = -Im4

AM_CPPFLAGS = -Iinc
AM_CFLAGS = -O3 -minline-all-stringops -funsafe-loop-optimizations -fprefetch-loop-arrays -funroll-loops -fomit-frame-pointer -fno-bounds-check -Wall -W
AM_LDFLAGS = -lm -lpthread

bin_PROGRAMS = finalFusion
# SRCS1
bin_finalFusion_SOURCES = searchPath.c scaffold.c check.c seq.c		\
                          bundle.c potential.c loadGraph.c		\
                          mem_manager.c attachPEinfo.c newhash.c	\
                          output_scaffold.c orderContig.c connect.c	\
                          hashFunction.c readseq1by1.c fib.c		\
                          fibHeap.c stack.c kmer.c prepare.c
# SRCS2
bin_finalFusion_SOURCES += prlHashCtg.c prlRead2Ctg.c map.c		\
	                   localAsm.c lib.c darray.c prlReadFillGap.c	\
	                   read2scaf.c
# SRCS3
bin_finalFusion_SOURCES += main.c

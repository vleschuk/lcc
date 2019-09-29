 - Assuming you have LCC_HOME variable set
 - Setup symlinks for your toolchain. Example

 $ ls -l $LCC_HOME/lib/lcc-4.2/gcc
 lrwxrwxrwx 1 del del 77 Sep 29 17:42 /home/del/lcc/lib/lcc-4.2/gcc -> /home/del/x-tools/i686-unknown-linux-gnu/lib/gcc/i686-unknown-linux-gnu/8.3.0
 $ ls -l $LCC_HOME/lib/lcc-4.2/gcc/
 total 5512
 lrwxrwxrwx 1 del del      86 Sep 29 17:50 crt1.o -> /home/del/x-tools/i686-unknown-linux-gnu/i686-unknown-linux-gnu/sysroot/usr/lib/crt1.o
 -r--r--r-- 1 del del    1864 Sep 29 14:11 crtbegin.o
 -r--r--r-- 1 del del    2756 Sep 29 14:11 crtbeginS.o
 -r--r--r-- 1 del del    2264 Sep 29 14:11 crtbeginT.o
 -r--r--r-- 1 del del    1272 Sep 29 14:11 crtend.o
 -r--r--r-- 1 del del    1536 Sep 29 14:11 crtendS.o
 -r--r--r-- 1 del del    4708 Sep 29 14:11 crtfastmath.o
 lrwxrwxrwx 1 del del      86 Sep 29 17:50 crti.o -> /home/del/x-tools/i686-unknown-linux-gnu/i686-unknown-linux-gnu/sysroot/usr/lib/crti.o
 lrwxrwxrwx 1 del del      86 Sep 29 17:52 crtn.o -> /home/del/x-tools/i686-unknown-linux-gnu/i686-unknown-linux-gnu/sysroot/usr/lib/crtn.o
 -r--r--r-- 1 del del    2340 Sep 29 14:11 crtprec32.o
 -r--r--r-- 1 del del    2352 Sep 29 14:11 crtprec64.o
 -r--r--r-- 1 del del    2344 Sep 29 14:11 crtprec80.o
 dr-xr-xr-x 2 del del    4096 Sep 29 14:11 include
 dr-xr-xr-x 2 del del    4096 Sep 29 14:10 include-fixed
 dr-xr-xr-x 3 del del    4096 Sep 29 14:11 install-tools
 -r--r--r-- 1 del del 5118286 Sep 29 14:11 libgcc.a
 -r--r--r-- 1 del del  136286 Sep 29 14:11 libgcc_eh.a
 -r--r--r-- 1 del del  315448 Sep 29 14:11 libgcov.a

 - Build with:

 $ i686-unknown-linux-gnu-gcc TMPDIR=/tmp ./BUILD-LCC.sh --exec-prefix=$LCC_HOME/lcc x86-linux 

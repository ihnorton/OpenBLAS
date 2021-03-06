# Contributions to the OpenBLAS project

## Creator & Maintainer

* Zhang Xianyi <traits.zhang@gmail.com>

## Active Developers

* Wang Qian <traz0824@gmail.com>
  * Optimize BLAS3 on ICT Loongson 3A.
  * Optimize BLAS3 on Intel Sandy Bridge.

* Werner Saar <wernsaar@googlemail.com>
  * [2013-03-04] Optimize AVX and FMA4 DGEMM on AMD Bulldozer
  * [2013-04-27] Optimize AVX and FMA4 TRSM on AMD Bulldozer
  * [2013-06-09] Optimize AVX and FMA4 SGEMM on AMD Bulldozer
  * [2013-06-11] Optimize AVX and FMA4 ZGEMM on AMD Bulldozer
  * [2013-06-12] Optimize AVX and FMA4 CGEMM on AMD Bulldozer
  * [2013-06-16] Optimize dgemv_n kernel on AMD Bulldozer
  * [2013-06-20] Optimize ddot, daxpy kernel on AMD Bulldozer
  * [2013-06-21] Optimize dcopy kernel on AMD Bulldozer
  * Porting and Optimization on ARM Cortex-A9
  * Optimization on AMD Piledriver
  * Optimization on Intel Haswell

## Previous Developers

* Zaheer Chothia <zaheer.chothia@gmail.com>
  * Improve the compatibility about complex number
  * Build LAPACKE: C interface to LAPACK
  * Improve the windows build.

* Chen Shaohu <huhumartinwar@gmail.com>
  * Optimize GEMV on the Loongson 3A processor.

* Luo Wen
  * Intern. Test Level-2 BLAS.

## Contributors

In chronological order:

* pipping <http://page.mi.fu-berlin.de/pipping>
  * [2011-06-11] Make USE_OPENMP=0 disable openmp.

* Stefan Karpinski <stefan@karpinski.org>
  * [2011-12-28] Fix a bug about SystemStubs on Mac OS X.

* Alexander Eberspächer <https://github.com/aeberspaecher>
  * [2012-05-02] Add note on patch for segfaults on Linux kernel 2.6.32.

* Mike Nolta <mike@nolta.net>
  * [2012-05-19] Fix building bug on FreeBSD and NetBSD.

* Sylvestre Ledru <https://github.com/sylvestre>
  * [2012-07-01] Improve the detection of sparc. Fix building bug under
    Hurd and kfreebsd.

* Jameson Nash <https://github.com/vtjnash>
  * [2012-08-20] Provide support for passing CFLAGS, FFLAGS, PFLAGS, FPFLAGS to
    make on the command line.

* Alexander Nasonov <alnsn@yandex.ru>
  * [2012-11-10] Fix NetBSD build.

* Sébastien Villemot <sebastien@debian.org>
  * [2012-11-14] Fix compilation with TARGET=GENERIC. Patch applied to Debian package.
  * [2013-08-28] Avoid failure on qemu guests declaring an Athlon CPU without 3dnow!

* Kang-Che Sung <Explorer09@gmail.com>
  * [2013-05-17] Fix typo in the document. Re-order the architecture list in getarch.c.

* Kenneth Hoste <kenneth.hoste@gmail.com>
  * [2013-05-22] Adjust Makefile about downloading LAPACK source files.

* Lei WANG <https://github.com/wlbksy>
  * [2013-05-22] Fix a bug about wget.

* Dan Luu <http://www.linkedin.com/in/danluu>
  * [2013-06-30] Add Intel Haswell support (using sandybridge optimizations).

* grisuthedragon <https://github.com/grisuthedragon>
  * [2013-07-11] create openblas_get_parallel to retrieve information which parallelization
    model is used by OpenBLAS.

* Elliot Saba <staticfloat@gmail.com>
  * [2013-07-22] Add in return value for `interface/trtri.c`

* Sébastien Fabbro <bicatali@gentoo.org>
  * [2013-07-24] Modify makefile to respect user's LDFLAGS
  * [2013-07-24] Add stack markings for GNU as arch-independent for assembler files

* Viral B. Shah <viral@mayin.org>
  * [2013-08-21] Patch LAPACK XLASD4.f as discussed in JuliaLang/julia#2340

* Lars Buitinck <https://github.com/larsmans>
  * [2013-08-28] get rid of the generated cblas_noconst.h file
  * [2013-08-28] Missing threshold in gemm.c
  * [2013-08-28] fix default prefix handling in makefiles

* yieldthought <https://github.com/yieldthought>
  * [2013-10-08] Remove -Wl,--retain-symbols-file from dynamic link line to fix tool support

* Keno Fischer <https://github.com/loladiro>
  * [2013-10-23] Use FC instead of CC to link the dynamic library on OS X

* Christopher Meng <cickumqt@gmail.com>
  * [2013-12-09] Add DESTDIR support for easier building on RPM based distros.
                 Use install command instead of cp to install files with permissions control.

* Lucas Beyer <lucasb.eyer.be@gmail.com>
  * [2013-12-10] Added support for NO_SHARED in make install.

* carlkl <https://github.com/carlkl>
  * [2013-12-13] Fixed LAPACKE building bug on Windows

* [Your name or handle] <[email or website]>
  * [Date] [Brief summary of your changes]

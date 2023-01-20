---
hide:
    - navigation
---

# Portfolio

Software projects are listed in alphabetical order. Selected contributions are listed in reverse chronological order.

## CP2K

Description: [home page](https://www.cp2k.org/), [Wikipedia page](https://en.wikipedia.org/wiki/CP2K).

Commits listed from [repository on GitHub](https://github.com/cp2k/cp2k):

- commit [`983495517714a4ae559e359a4b24590748e428cb`](https://github.com/cp2k/cp2k/commit/983495517714a4ae559e359a4b24590748e428cb): add support for __ELPA3 (elpa-2015.11.001) (Hans, Vedran).

    ??? note
        svn-origin-rev: 16351

- commit [`f22cda299a7a3f09ff9d1ba3c376621f03b28322`](https://github.com/cp2k/cp2k/commit/f22cda299a7a3f09ff9d1ba3c376621f03b28322): Remove dbcsr_error_type (Vedran Miletic)

    ??? note
        svn-origin-rev: 16153

- commit [`fbfeb0d56fabab995210cb4fc10db8f504b6395a`](https://github.com/cp2k/cp2k/commit/fbfeb0d56fabab995210cb4fc10db8f504b6395a): Remove cp_error_type (Vedran Miletic)

    ??? note
        svn-origin-rev: 15915

- commit [`26055ca92e8341c447efbb8fe9c6367f28505488`](https://github.com/cp2k/cp2k/commit/26055ca92e8341c447efbb8fe9c6367f28505488): NEB: Fix file number padding (Vedran Miletic)

    ??? note
        svn-origin-rev: 15867

- commit [`b075cfc0fbb08bc3806e14e06ac2deb60b3a9335`](https://github.com/cp2k/cp2k/commit/b075cfc0fbb08bc3806e14e06ac2deb60b3a9335): Remove IF(.NOT.failure) pattern (Vedran Miletic)

    ??? note
        svn-origin-rev: 15663

- commit [`34113fad2cbe0c899447f90819581573abc2c966`](https://github.com/cp2k/cp2k/commit/34113fad2cbe0c899447f90819581573abc2c966): Remove pseudo exception handling (Vedran Miletic)

    ??? note
        svn-origin-rev: 15576

- commit [`15117457247a2a20e4241d5ffa1e0a070dfcc0cc`](https://github.com/cp2k/cp2k/commit/15117457247a2a20e4241d5ffa1e0a070dfcc0cc): Input: Remove required flag (Vedran Miletic)

    ??? note
        svn-origin-rev: 15552

- commit [`ed0bd0f8fe85f61e04804caef26946a26e8dc5bf`](https://github.com/cp2k/cp2k/commit/ed0bd0f8fe85f61e04804caef26946a26e8dc5bf): Input Description Change (Vedran Miletic)

    ??? note
        svn-origin-rev: 15378

- commit [`8afc119ec5e8d5af4d0d91ff58468fe610ec3560`](https://github.com/cp2k/cp2k/commit/8afc119ec5e8d5af4d0d91ff58468fe610ec3560): Input Description Change (Vedran Miletić)

    ??? note
        svn-origin-rev: 14234

- commit [`8c939f76055d5175cb42e10fcb92a1f283223dc8`](https://github.com/cp2k/cp2k/commit/8c939f76055d5175cb42e10fcb92a1f283223dc8): more doxygen fixes (Vedran Miletić)

    ??? note
        svn-origin-rev: 14230

- commit [`02f6415aa900f3108880d729920f7e8325602e08`](https://github.com/cp2k/cp2k/commit/02f6415aa900f3108880d729920f7e8325602e08): fix Doxygen errors (Vedran Miletić)

    ??? note
        svn-origin-rev: 14229

## {fmt}

Description: [home page](https://fmt.dev/).

Commits listed from [repository on GitHub](https://github.com/fmtlib/fmt):

- commit [`f7aedc5fc4893fc627a2c0854f78a25b89214c5c`](https://github.com/fmtlib/fmt/commit/f7aedc5fc4893fc627a2c0854f78a25b89214c5c): Fix shared build on Solaris
- commit [`c2e84ee9cced1d969276cf87c1b857a9aabedcd0`](https://github.com/fmtlib/fmt/commit/c2e84ee9cced1d969276cf87c1b857a9aabedcd0): Fix FormatTest.StrError on Solaris

## GROMACS

Description: [home page](https://www.gromacs.org/), [Wikipedia page](https://en.wikipedia.org/wiki/GROMACS).

Commits listed from [repository on GitLab](https://gitlab.com/gromacs/gromacs):

- commit [`24b0f57aafb067abac9a2a2086d4b98b9d23a305`](https://gitlab.com/gromacs/gromacs/-/commit/24b0f57aafb067abac9a2a2086d4b98b9d23a305): Renamed variables that hide variables from outer scope

    ??? note
        Specifically:

        - parameter hides global variable
        - local variable hides global variable
        - loval variable hides parameter

- commit [`ddbea6649b2f2ad278a715f3a438d5c161be7283`](https://gitlab.com/gromacs/gromacs/-/commit/ddbea6649b2f2ad278a715f3a438d5c161be7283): Removed debugging code in pull utilities

- commit [`28acfd1164dd14c5a1ef2aa85f05744ce4a7cd13`](https://gitlab.com/gromacs/gromacs/-/commit/28acfd1164dd14c5a1ef2aa85f05744ce4a7cd13): Fix building on Solaris with GCC

    ??? note
        GROMACS now compiles on Solaris x86, specifically illumos distribution
        openindiana. GCC complained about a missing sqrt() variant which was
        addressed with static_cast and linker complained about missing
        libsocket which was addressed with SunOS-specific entry in
        target_link_libraries.

        Refs #3050

        Change-Id: Ic14a9327fa353270ef0e787b4d2357e86e71da53

- commit [`1333a483d730aed0633c63c782374c3ad6bb10c9`](https://gitlab.com/gromacs/gromacs/-/commit/1333a483d730aed0633c63c782374c3ad6bb10c9): Document matrix_convert function in PBC

    ??? note
        The brief documentation was in place, but the documentation of the
        function parameters was missing. This patch adds it and also fixes
        incorrect Doxygen syntax at pbc_dx_d.

        Change-Id: Ic897911bf4b8866bb7c4dc3aea982493cc03874c

- commit [`32da95724a333b6fb97055bea8de5687f54756f2`](https://gitlab.com/gromacs/gromacs/-/commit/32da95724a333b6fb97055bea8de5687f54756f2): Document t_commrec struct

    ??? note
        Describe the mysim and mygroup MPI communicators and add a note about
        the communicator subsetting.

        Change-Id: I2d39bd6827da59db5b3c38bd33de6903e17d0d06

- commit [`c33d8d64fa8c0fa27f6e429c24bf295c5eff5c61`](https://gitlab.com/gromacs/gromacs/-/commit/c33d8d64fa8c0fa27f6e429c24bf295c5eff5c61): Improve the "files not present" error message

    ??? note
        It's possible to use -deffnm in restarts even if it wasn't used in
        the initial simulation. This can lead to absurd situations such as:

        Expected output files not present or named differently:
          pullx.xvg
          pullf.xvg

        where pullx.xvg and pullf.xvg are present and named exactly as listed,
        but GROMACS expects them to be named as -deffnm requested.

        The improved error message suggest to the user to check for that
        possibility.

        Refs #942 (partial workaround)

        Change-Id: I983a7a2be791a634b877b0cbadb34e56a1ee2f82

- commit [`aee3a691bca8067672e91efa482e2a6a05f9c051`](https://gitlab.com/gromacs/gromacs/-/commit/aee3a691bca8067672e91efa482e2a6a05f9c051): Migrate some of the terminology pages

    ??? note
        Change-Id: I2671535659cc0e62aa44cd5056e3924180b6abba

- commit [`645414bb74b8191404e12f364805cf99e5e5a190`](https://gitlab.com/gromacs/gromacs/-/commit/645414bb74b8191404e12f364805cf99e5e5a190): Migrate the documentation of the run-time errors

    ??? note
        From the wiki, cleaned up and updated with new tool names.

        Change-Id: Ia21e227b660d84b1b3f72f1f6e30cf29e5de9a23

- commit [`ba602c13530a4c922eecd07eda5493f5fd0e55b9`](https://gitlab.com/gromacs/gromacs/-/commit/ba602c13530a4c922eecd07eda5493f5fd0e55b9): Fix formatting of gmx msd Description

    ??? note
        When \[tt\] isn't followed by a space or a punctation symbol, Sphinx will
        generate wrong HTML output (preformated text ending tag will not be
        where it should be). The formulation provided here is also slightly
        more readable.

        Change-Id: I328921b0e724e8f997fd07615e84cc8d87e7153f

- commit [`279eba76f677efc59d7169fb4d3d9fc98bc43f49`](https://gitlab.com/gromacs/gromacs/-/commit/279eba76f677efc59d7169fb4d3d9fc98bc43f49): Document floating-point arithmetic

    ??? note
        From the wiki, expanded with the links to David Goldberg's legendary
        paper and its appendix.

        Change-Id: Idb18ff37d4e8495412847f06872af693283dd747

- commit [`57836e7ead25c694f5a1d684d5aa6918de0fd567`](https://gitlab.com/gromacs/gromacs/-/commit/57836e7ead25c694f5a1d684d5aa6918de0fd567): Expand Performance section of the user guide

    ??? note
        Salvage and clean up the content from the wiki to expand the user
        guide. Minor fixes to the rest of the Performance section.

        Change-Id: I39aba257c4c761a3a1ef428c64424da6fa449158

- commit [`95bdbfae9e38625be04a912b79c72a6f283e3b62`](https://gitlab.com/gromacs/gromacs/-/commit/95bdbfae9e38625be04a912b79c72a6f283e3b62): Standardize use of |Gromacs| in reST docs

    ??? note
        Where possible, replace all occurences of GROMACS with |Gromacs|.

        Change-Id: I4835a148aefb2d8b088ca63b444bb1107520fc52

- commit [`65bf69442b578516a32ca65e046efcbb58a11b8b`](https://gitlab.com/gromacs/gromacs/-/commit/65bf69442b578516a32ca65e046efcbb58a11b8b): Really enable avx512 in fftw only for select compilers

    ??? note
        Commit aa905d6 attempted to enable avx512 on GCC 4.9 or newer and
        Clang 3.9 or newer, but had elseif() in place of else() and resulted
        in no SIMD being enabled.

        This patch really enables avx512 on supported compilers, and takes
        care of all compilers we officially support (MSVC, GCC, Clang, ICC).

        Change-Id: Ia626b4cc6c82a2155d633f1482b99d3b2601fa3a

- commit [`46dc5e12c8a83880c19f0f6343ec4d8e6fad8522`](https://gitlab.com/gromacs/gromacs/-/commit/46dc5e12c8a83880c19f0f6343ec4d8e6fad8522): Document that we now support AMD GCN on Mesa/LLVM

    ??? note
        AMD GPUs using Mesa 17.0+ and LLVM 4.0+ run GROMACS using OpenCL.

        Change-Id: I899c4f1c0581fdb3ea635c1f19f37b66c5dc3411

- commit [`aa905d647e272792f67d93994578d0bb0eeb0f3f`](https://gitlab.com/gromacs/gromacs/-/commit/aa905d647e272792f67d93994578d0bb0eeb0f3f): Enable avx512 in fftw only if compiler supports it

    ??? note
        Enabling avx512 requires GCC 4.9 or newer or Clang 3.9 or newer. Since
        we support compilers older than those, we can not afford to enable
        avx512 in own fftw unconditionally.

        Change-Id: I17dba4e16f3d3566c1f5188497d0467d1d2665a0

- commit [`7d603de9be282beeac7c310d94059632dc93c3c6`](https://gitlab.com/gromacs/gromacs/-/commit/7d603de9be282beeac7c310d94059632dc93c3c6): Document running Clang static analyzer manually

    ??? note
        Change-Id: Ic1a273e9f8fc489d03b59eef70ff71bb426ba720

- commit [`b142605b328bca62930bf7e7229ebe8fb1b663ea`](https://gitlab.com/gromacs/gromacs/-/commit/b142605b328bca62930bf7e7229ebe8fb1b663ea): Improve include sorter error reporting

    ??? note
        Change-Id: I5fe5d1ad6a4001cff6ae8a2b109e831c5e3eb433

- commit [`c35e87d620cd22164a6f0cd0e540e15d4e82eb16`](https://gitlab.com/gromacs/gromacs/-/commit/c35e87d620cd22164a6f0cd0e540e15d4e82eb16): Make editconf B-factor attachment more useful in practice

    ??? note
        B-factor values will be added to residues unless an index is larger
        than the number of residues or an option is specified. Protein residue
        indices can start from any number and, in case they start from a large
        number, there is no way to add B-factor values to residues.

        This patch changes it to add B-factor values to residues unless the
        number of B-factor values is larger than the number of residues.

        Change-Id: Ifa67d6d6b5dc0f31e5b0d270ce255aece5ac7247

- commit [`d97be0dc79bdfedbea575ba3e7808bb4bfce7998`](https://gitlab.com/gromacs/gromacs/-/commit/d97be0dc79bdfedbea575ba3e7808bb4bfce7998): Document wallcycle counters and subcounters

    ??? note
        List the available counters and explain how they are used. For subcounters,
        explain the difference to counters and mention how to enable them.

        Change-Id: Id5ce0e99b37a899f84d10b799840abad27d15c9c

- commit [`c4942a845673a9a60ff69b05f952f3a45a030987`](https://gitlab.com/gromacs/gromacs/-/commit/c4942a845673a9a60ff69b05f952f3a45a030987): Print OpenCL error string instead of error code

    ??? note
        Change-Id: I00871b7f295373d8497a13d0bc3cbd0c0ff99668

- commit [`2defd44a4c438e2fff007d0970316524dcfffe53`](https://gitlab.com/gromacs/gromacs/-/commit/2defd44a4c438e2fff007d0970316524dcfffe53): Use only legal characters in OpenCL cache filename

    ??? note
        The device name from the vendor could contain anything, and we need to
        avoid dot and slash when we try to make a filename from it. To help
        keep it valid for all possible users, we permit only alphanumeric
        characters from the current locale.

        Change-Id: Ie55959a9a2161d0cfc7effa6ab57fffc8160f4e2

- commit [`f7a4354b0a5a9be2b7039483e99a23e5542beb0e`](https://gitlab.com/gromacs/gromacs/-/commit/f7a4354b0a5a9be2b7039483e99a23e5542beb0e): Document gmx_cgsort_t and gmx_domdec_sort_t structs

    ??? note
        Add descriptions to fields of gmx_cgsort_t and gmx_domdec_sort_t
        structs used in domain decomposition code.

        Change-Id: Ie64664ed46413e51ba22504270ab11350c39b84a

- commit [`1726c6263fc21e8d0a8636636c5459c76df270e8`](https://gitlab.com/gromacs/gromacs/-/commit/1726c6263fc21e8d0a8636636c5459c76df270e8): Print working dir before command line

    ??? note
        When running GROMACS via a batch script, it is useful to know which
        working dir is being used for relative paths (file names) in the
        command line.

        Change-Id: Iab6701e09ad3b0386b59c2bdda2c4f908fdc2d0a

- commit [`fbc99c75abe169b792f53ddceecfe1e9226d199f`](https://gitlab.com/gromacs/gromacs/-/commit/fbc99c75abe169b792f53ddceecfe1e9226d199f): Prevent writing to unallocated memory in mk_specbonds

    ??? note
        Stop creating new specbonds after at most nspec bonds have been created
        to prevent writing to unallocated memory.

        Change-Id: I53f9d20059915e7fba8767b92d92fa751e9165e3

- commit [`4b8d53be6aa22aeba77f375c31f65390a619e63b`](https://gitlab.com/gromacs/gromacs/-/commit/4b8d53be6aa22aeba77f375c31f65390a619e63b): Report the filename and the line number on failure

    ??? note
        Extend the call to gmx_fatal in fget_lines() to report the filename and
        the line number where the read failed.

        Change-Id: Ib5ee06c06111cb61be616a5a4d01339da56a5685

- commit [`4c4c385bcbc381f1e7872a2c4176f233895d87c0`](https://gitlab.com/gromacs/gromacs/-/commit/4c4c385bcbc381f1e7872a2c4176f233895d87c0): Write OpenCL build log prior to checking build status

    ??? note
        If building an OpenCL kernel fails, we still want to let the user know
        why the build process failed. Therefore the code has to write the build
        log prior to throwing a build failure exception.

        Change-Id: I2a8881895379da9ce4b13cf34788357347f1050c

- commit [`109138231f8534303949b418e20718a113966c48`](https://gitlab.com/gromacs/gromacs/-/commit/109138231f8534303949b418e20718a113966c48): Remove static function qualifier in OpenCL kernel utils

    ??? note
        Static function qualifiers are supported since OpenCL 1.2. When Mesa 3D
        Gallium Clover state tracker is used on AMD Radeon GCN cards, it only
        provides OpenCL 1.1 support, so static function qualifiers are not
        supoorted.

        Change-Id: I6d7aceabefeb0ce825b698962830201728bc56d7

- commit [`f7a1ddfcf732d682351c99db39298f255c2160ae`](https://gitlab.com/gromacs/gromacs/-/commit/f7a1ddfcf732d682351c99db39298f255c2160ae): Disable CUDA profiler when using OpenCL

    ??? note
        Replacing GPU_FUNC_TERM with CUDA_FUNC_TERM generates correct empty
        implementations and therefore fixes linker errors.

        Change-Id: I6485471eeb22bec9e6f0c3528bff7310593e3be6

- commit [`740b090b658b9a134ffd2f18ea16035e62a6dc9d`](https://gitlab.com/gromacs/gromacs/-/commit/740b090b658b9a134ffd2f18ea16035e62a6dc9d): OpenCL: use new defines (\*_POW2_EXPONENT -> \*_LOG2)

    ??? note
        This fixes 'error: use of undeclared identifier' introduced in
        a86dee3d7d01ceb0b9a74d98010d17c47a7a8359.

        Change-Id: Id61294897a35d5b7bde7b7d7469560b0a39836d7

- commit [`d4d377a2b0e666d4a2674b3d73b79d7c4e154b0e`](https://gitlab.com/gromacs/gromacs/-/commit/d4d377a2b0e666d4a2674b3d73b79d7c4e154b0e): Update explanation of replica exchange output

    ??? note
        We use both ex and x as a shorthand for exchange, and the output
        should mention that.

        Change-Id: Ied7fa5328191098a506279602a0ba67ca2254d0b

- commit [`330c6057a5ee856d3acfd8dee9206d589ac70f1e`](https://gitlab.com/gromacs/gromacs/-/commit/330c6057a5ee856d3acfd8dee9206d589ac70f1e): Document gmx_repl_ex struct

    ??? note
        This patch adds descriptions to fields of gmx_repl_ex struct used
        in replica exchange code.

        Change-Id: I68fccd4d121ab3cf747ea5c61630728d74597260

- commit [`f39f90fab4d4da0c8e17f1fcd9366dd977390e5a`](https://gitlab.com/gromacs/gromacs/-/commit/f39f90fab4d4da0c8e17f1fcd9366dd977390e5a): Fix removal of symlinks created during installation

    ??? note
        Installation of gromacs creates 2 symlinks for libgromacs.so, which become
        broken once library is removed. During uninstall, CMake macro EXISTS will follow
        symlink and conclude files do not have to be removed.

        This patch adds IS_SYMLINK checking in addition to EXISTS.

        Change-Id: Id7ef6768549a6fc09fb017e5be9ac286e4f7a026

- commit [`27e65c7671fd4053603bfa54f17ebdaf466e1f04`](https://gitlab.com/gromacs/gromacs/-/commit/27e65c7671fd4053603bfa54f17ebdaf466e1f04): Use ${CMAKE_INSTALL_LIBDIR} as lib directory for tng_io library

    ??? note
        Directory lib was used as library directory for tng_io library. This
        causes problems on Debian wheezy (and future versions), which expect
        libraries to be installed under lib/&lt;arch&gt;. GROMACS already uses
        ${CMAKE_INSTALL_LIBDIR} for libgromacs.so, and this patch makes
        libtng_io and libtng_compress install in the same location.

        This was also addressed in the TNG repository and this commit
        corresponds to commit e8fa7bf3abfc74acf60a048cdfe1f65fdbc0dc2d in
        the TNG repository.

        This patch also bumps minimum CMake version required for building
        tng_io from 2.8 to 2.8.8 due to inclusion of GNUInstallDirs module.

        Change-Id: I68b2196ab77e3e18c3a50717327e59b3482f2a29

## LLVM

Description: [home page](https://llvm.org/), [Wikipedia page](https://en.wikipedia.org/wiki/LLVM).

Commits listed from [repository on GitHub](https://github.com/llvm/llvm-project):

- commit [`ad21f2687dcca2199a5b2bd9b7f04486008ece16`](https://github.com/llvm/llvm-project/commit/ad21f2687dcca2199a5b2bd9b7f04486008ece16): \[AMDGPU\] Add custom lowering for llvm.log{,10}.{f16,f32} intrinsics

    ??? note
        AMDGPU backend errors with "unsupported call to function" upon
        encountering a call to llvm.log{,10}.{f16,f32} intrinsics. This patch
        adds custom lowering to avoid that error on both R600 and SI.

        Reviewers: arsenm, jvesely

        Subscribers: tstellar

        Differential Revision: <https://reviews.llvm.org/D29942>

        llvm-svn: 319025

- commit [`79b7f4c1250dfe779bbb44259e9c649dba276437`](https://github.com/llvm/llvm-project/commit/79b7f4c1250dfe779bbb44259e9c649dba276437): configure.py: Add gfx900 (Vega, Raven)

    ??? note
        Sort amdgcn-- and amdgcn--amdhsa in a consistent way.

        llvm-svn: 319017

- commit [`9df2b9781c1f963b692defb884cb4fd4e9352c41`](https://github.com/llvm/llvm-project/commit/9df2b9781c1f963b692defb884cb4fd4e9352c41): math: Add native_rsqrt builtin function

    ??? note
        Trivial define to rsqrt.

        Patch by Vedran Miletić <vedran@miletic.net>

        llvm-svn: 294608

- commit [`d8f7ea381f8958b94d3eb82103be427e8a283347`](https://github.com/llvm/llvm-project/commit/d8f7ea381f8958b94d3eb82103be427e8a283347): AMDGPU: Enable FeatureFlatForGlobal on Volcanic Islands

    ??? note
        Accomplishes what r292982 was supposed to, which ended up
        only really making the necessary test changes.

        This should be applied to the 4.0 branch.

        Patch by Vedran Miletić <vedran@miletic.net>

        llvm-svn: 293310

- commit [`88d7da01ca7af18ed6bd446d388999bf9668a3cf`](https://github.com/llvm/llvm-project/commit/88d7da01ca7af18ed6bd446d388999bf9668a3cf): AMDGPU: Handle structs directly in AMDGPUABIInfo

    ??? note
        Structs are currently handled as pointer + byval, which makes AMDGPU
        LLVM backend generate incorrect code when structs are used. This patch
        changes struct argument to be handled directly and without flattening,
        which Clover (Mesa 3D Gallium OpenCL state tracker) will be able to
        handle. Flattening would expand the struct to individual elements and
        pass each as a separate argument, which Clover can not
        handle. Furthermore, such expansion does not fit the OpenCL
        programming model which requires to explicitely specify each argument
        index, size and memory location.

        Patch by Vedran Miletić <vedran@miletic.net>

        llvm-svn: 279463

- commit [`43ab9a00eb165625e07c1bc92afcfb521e926b1d`](https://github.com/llvm/llvm-project/commit/43ab9a00eb165625e07c1bc92afcfb521e926b1d): \[OpenCL\] Output OpenCL version in diagnostics.

    ??? note
        Diagnostics should note version dependent issues by giving
        a hint about current version being compiled for.

        This patch changes diagnostics of static storage class specifier
        and generic type qualifier to specify OpenCL version as well as
        converts other diagnostics to match the style.

        Patch by Vedran Miletic!

        Review: <http://reviews.llvm.org/D19780>

        llvm-svn: 269305

- commit [`c374cb76f467f01a3f60740703f995a0e1f7a89a`](https://github.com/llvm/llvm-project/commit/c374cb76f467f01a3f60740703f995a0e1f7a89a): math: Add erf ported from amd-builtins

    ??? note
        The scalar float/double function bodies are a direct copy/paste,
        aside from the removed (optional) code in float function body that
        requires subnormals.

        reviewers: jvesely

        Patch by: Vedran Miletić <rivanvx@gmail.com>

        llvm-svn: 268766

- commit [`3ec09e61d1c823837fbf442c83865673cbbf59c8`](https://github.com/llvm/llvm-project/commit/3ec09e61d1c823837fbf442c83865673cbbf59c8): AMDGPU: Document address space mapping

    ??? note
        Summary:  
        Address space mapping is described in lib/Target/AMDGPU/AMDGPU.h in
        Doxygen comments. This patch adds the description to user guide for
        AMDGPU back-end.

        Patch By: Vedran Miletić

        Reviewers: tstellarAMD, arsenm

        Subscribers: llvm-commits

        Differential Revision: <http://reviews.llvm.org/D17046>

        llvm-svn: 265500

- commit [`354a43c7bc562a4c67439a02e4bd717fb49a5857`](https://github.com/llvm/llvm-project/commit/354a43c7bc562a4c67439a02e4bd717fb49a5857): AMDGPU: Implement {BUFFER,FLAT}_ATOMIC_CMPSWAP{,_X2}

    ??? note
        Summary:  
        Implement BUFFER_ATOMIC_CMPSWAP{,_X2} instructions on all GCN targets, and FLAT_ATOMIC_CMPSWAP{,_X2} on CI
        +.

        32-bit instruction variants tested manually on Kabini and Bonaire. Tests and parts of code provided by Jan
        Veselý.

        Patch by: Vedran Miletić

        Reviewers: arsenm, tstellarAMD, nhaehnle

        Subscribers: jvesely, scchan, kanarayan, arsenm

        Differential Revision: <http://reviews.llvm.org/D17280>

        llvm-svn: 265170

## Mesa

Description: [home page](https://mesa3d.org/), [Wikipedia page](https://de.wikipedia.org/wiki/Mesa_3D).

Commits listed from [repository on freedesktop.org GitLab](https://gitlab.freedesktop.org/mesa/mesa):

- commit [`d9fef848a651b47520cbeb72c38b93d4fbf842a8`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/d9fef848a651b47520cbeb72c38b93d4fbf842a8): clover: Use Clang's diagnostics

    ??? note
        Presently errors from frontend are handled only if they occur in
        clang::CompilerInvocation::CreateFromArgs(). This patch uses
        clang::DiagnosticsEngine to detect errors such as invalid values for
        Clang frontend arguments.

        Fixes Piglit's cl/program/build/fail/invalid-version-declaration.cl
        test.

        v2: fix inconsistent code formatting

        Signed-off-by: Vedran Miletić <vedran@miletic.net>  
        Reviewed-by: Francisco Jerez <currojerez@riseup.net>  
        Tested-by: Aaron Watry <awatry@gmail.com>

- commit [`95ddb37708ca16ccbd0f607d17a82be2de0d07b6`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/95ddb37708ca16ccbd0f607d17a82be2de0d07b6): clover: Restore support for LLVM <= 3.9.

    ??? note
        The commit 8e430ff8b060b4e8e922bae24b3c57837da6ea77 broke support for
        LLVM 3.9 and older versions in Clover. This patch restores it and
        refactors the support using Clover compatibility layer for LLVM.

        v2: merged #ifdef blocks  
        v3: added support for LLVM 3.6-3.8  
        v4: add missing #ifdef around <memory>  
        v5: simplify using templates and lambda

        Signed-off-by: Vedran Miletić <vedran@miletic.net>  
        Bugzilla: <https://bugs.freedesktop.org/show_bug.cgi?id=98740>  
        Tested-by\[v4\]: Pierre Moreau <pierre.morrow@free.fr>  
        Tested-by: Vinson Lee <vlee@freedesktop.org>  
        Reviewed-by: Francisco Jerez <currojerez@riseup.net>  
        Reviewed-by: Jan Vesely <jan.vesely@rutgers.edu>

- commit [`8e430ff8b060b4e8e922bae24b3c57837da6ea77`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/8e430ff8b060b4e8e922bae24b3c57837da6ea77): clover: adapt to new error API since LLVM r286752

    ??? note
        Tested-by: Dieter Nützel <Dieter@nuetzel-hh.de>

- commit [`2fba72046da09dd28f54df02794b358773899d13`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/2fba72046da09dd28f54df02794b358773899d13): clover: Introduce CLOVER_EXTRA_\*_OPTIONS environment variables

    ??? note
        The options specified in the CLOVER_EXTRA_BUILD_OPTIONS shell
        variable are appended to the options specified by the OpenCL program
        in the clBuildProgram function call, if any.
        Analogously, the options specified in the CLOVER_EXTRA_COMPILE_OPTIONS
        and CLOVER_EXTRA_LINK_OPTIONS variables are appended to the options
        specified in clCompileProgram and clLinkProgram function calls,
        respectively.

        v2:

        * rename to CLOVER_EXTRA_COMPILER_OPTIONS
        * use debug_get_option
        * append to linker options as well

        v3: code cleanups

        v4: separate CLOVER_EXTRA_LINKER_OPTIONS options

        v5:

        * fix documentation typo
        * use CLOVER_EXTRA_COMPILER_OPTIONS in link stage

        v6:

        * separate in CLOVER_EXTRA_{BUILD,COMPILE,LINK}_OPTIONS
        * append options in cl{Build,Compile,Link}Program

        Signed-off-by: Vedran Miletić <vedran@miletic.net>  
        Reviewed-by\[v1\]: Edward O'Callaghan <funfunctor@folklore1984.net>

        v7 \[Francisco Jerez\]: Slight simplification.

        Reviewed-by: Francisco Jerez <currojerez@riseup.net>

- commit [`e3272865c216933168e6c08766d266a33d0e1497`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/e3272865c216933168e6c08766d266a33d0e1497): clover: Pass unquoted compiler arguments to Clang

    ??? note
        OpenCL apps can quote arguments they pass to the OpenCL compiler, most
        commonly include paths containing spaces.

        If the Clang OpenCL compiler was called via a shell, the shell would
        split the arguments with respect to to quotes and then remove quotes
        before passing the arguments to the compiler. Since we call Clang as a
        library, we have to split the argument with respect to quotes and then
        remove quotes before passing the arguments.

        v2: move to tokenize(), remove throwing of CL_INVALID_COMPILER_OPTIONS

        v3: simplify parsing logic, use more C++11

        v4: restore error throwing, clarify a comment

        Signed-off-by: Vedran Miletić <vedran@miletic.net>  
        Reviewed-by: Francisco Jerez <currojerez@riseup.net>

- commit [`7b9a0f4e38b6b64a91ed0e674410af962b390120`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/7b9a0f4e38b6b64a91ed0e674410af962b390120): mesa: standardize naming Mesa3D, MESA -> Mesa

    ??? note
        Signed-off-by: Vedran Miletić <vedran@miletic.net>  
        Reviewed-by: Edward O'Callaghan <funfunctor@folklore1984.net>

- commit [`82e0bbd01abfb2073519941d9893fa6ac05fb58c`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/82e0bbd01abfb2073519941d9893fa6ac05fb58c): clover: Fix build against clang SVN >= r273191

    ??? note
        setLangDefaults() now requires PreprocessorOptions as an argument.

        Reviewed-and-Tested-by: Michel Dänzer <michel.daenzer@amd.com>

- commit [`4825264f75c83576f251290547f121f066b46a70`](https://gitlab.freedesktop.org/mesa/mesa/-/commit/4825264f75c83576f251290547f121f066b46a70): clover: Update OpenCL version string to match OpenGL

    ??? note
        Change MESA into Mesa in CL_PLATFORM_VERSION and CL_DEVICE_VERSION. For
        both, always append git version suffix from git_sha1.h.

        v5: move semicolon to same line as MESA_GIT_SHA1.  
        v4: drop #ifdef guards.  
        v3: add missing include.  
        v2: change CL_DEVICE_VERSION as well.

        Cc: <mesa-stable@lists.freedesktop.org>  
        Reviewed-by: Francisco Jerez <currojerez@riseup.net>

## ns-3

Description: [home page](https://www.nsnam.org/), [Wikipedia page](https://en.wikipedia.org/wiki/Ns_(simulator)).

Commits listed from [repository on GitLab](https://gitlab.com/nsnam/ns-3-dev):

- commit [`37afc2b958acad3227a8149fddc1bbb733641781`](https://gitlab.com/nsnam/ns-3-dev/-/commit/37afc2b958acad3227a8149fddc1bbb733641781): Add missing include in LTE test
- commit [`422a3fca7fb209aceade1992798acfc4cb92db22`](https://gitlab.com/nsnam/ns-3-dev/-/commit/422a3fca7fb209aceade1992798acfc4cb92db22): Fix building with Clang in optimized mode
- commit [`c5cb7eb89679383e3d6c42eab94e33bf0510d96c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/c5cb7eb89679383e3d6c42eab94e33bf0510d96c): spectrum: actually remove the define
- commit [`26ed7563e1b983f1b4ffb378fc2171264e817647`](https://gitlab.com/nsnam/ns-3-dev/-/commit/26ed7563e1b983f1b4ffb378fc2171264e817647): spectrum: replace #define private public with friend class

    ??? note
        ns-3 declares test classes as friend classes elsewhere, and this is the
        only use of #define private public. Removing this #define also fixes
        building with GCC 6.

- commit [`62aa377d4f1a5f281330f763cef0ff1f40ba950c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/62aa377d4f1a5f281330f763cef0ff1f40ba950c): Upgrade Waf to 1.8.19
- commit [`038fdd2c8357c95cef8797d91806731828f989a8`](https://gitlab.com/nsnam/ns-3-dev/-/commit/038fdd2c8357c95cef8797d91806731828f989a8): Replace comparison of this to null with NS_LOG macro
- commit [`bbe892572705ad59dd02626fab0932b9e93a2db3`](https://gitlab.com/nsnam/ns-3-dev/-/commit/bbe892572705ad59dd02626fab0932b9e93a2db3): Fix building with Clang 3.7 (use delete\[\] instead of delete)
- commit [`dc841819ccea7b3ba6222c4b3807da9514701eb5`](https://gitlab.com/nsnam/ns-3-dev/-/commit/dc841819ccea7b3ba6222c4b3807da9514701eb5): Upgrade Waf to 1.8.16
- commit [`397d34fb5822b2c783350056015dd1e889475bec`](https://gitlab.com/nsnam/ns-3-dev/-/commit/397d34fb5822b2c783350056015dd1e889475bec): Update Waf to 1.8.13
- commit [`3a690bd07146c0b878640d9b363aa2e453a8717f`](https://gitlab.com/nsnam/ns-3-dev/-/commit/3a690bd07146c0b878640d9b363aa2e453a8717f): Detect gccxml using CastXML wrapper in waf configure
- commit [`f1a1922cc0b736030616b29f76684b2b1ef3af6b`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f1a1922cc0b736030616b29f76684b2b1ef3af6b): Silence Clang 3.6+ -Wno-potentially-evaluated-expression warning

    ??? note
        Clang 3.6+ warns about "expression with side effects will be evaluated
        despite being used as an operand to 'typeid'" if Ptr&lt;&gt; is used as an
        argument to typeid(). This changes the code to use raw pointers
        instead of Ptr&lt;&gt;.

- commit [`a944617f27362e6d0947daca13fe16cdb44389be`](https://gitlab.com/nsnam/ns-3-dev/-/commit/a944617f27362e6d0947daca13fe16cdb44389be): Use proper environment when checking for supported compiler flags
- commit [`6cb06ce56067b5dc54ca79506f91b56abec0be67`](https://gitlab.com/nsnam/ns-3-dev/-/commit/6cb06ce56067b5dc54ca79506f91b56abec0be67): Handle the case where scratch or examples directory is missing
- commit [`46297abcda6450aa7f2352717f4de421555ccfdd`](https://gitlab.com/nsnam/ns-3-dev/-/commit/46297abcda6450aa7f2352717f4de421555ccfdd): Remove unused EXAMPLE_DIRECTORIES environment variable
- commit [`9f10edb6658c8e68f6923789d73ff792908cee69`](https://gitlab.com/nsnam/ns-3-dev/-/commit/9f10edb6658c8e68f6923789d73ff792908cee69): Update waf to 1.8.12
- commit [`4146d77eaf569ca438ad695fd62097fcabfafc33`](https://gitlab.com/nsnam/ns-3-dev/-/commit/4146d77eaf569ca438ad695fd62097fcabfafc33): Fix printing of gccxml version (Waf 1.8 API change)
- commit [`2006e41baa5488de6e961893f2c03d033f2904f1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/2006e41baa5488de6e961893f2c03d033f2904f1): Fix Python bindings wscript and waf-tools for Waf 1.8
- commit [`d4e9a7968e2a95ac08bad1e47f7e3203c8f14602`](https://gitlab.com/nsnam/ns-3-dev/-/commit/d4e9a7968e2a95ac08bad1e47f7e3203c8f14602): Print correct output directory
- commit [`203a80dd7346968b70d74b766c839c12c7e5d42a`](https://gitlab.com/nsnam/ns-3-dev/-/commit/203a80dd7346968b70d74b766c839c12c7e5d42a): Handle broken versions of Clang better

    ??? note
        Clang packages in Debian are sometimes broken. In that case, compiler fails
        with "fatal error: 'bits/c++config.h' file not found". We should detect that
        better. This patch updates boost.py to latest waf version which works, and also
        handles empty apsican variable.

- commit [`7967235960d4bb2a1e6e719e867b1e397995219c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/7967235960d4bb2a1e6e719e867b1e397995219c): Fix building with clang 3.5 (abs->std::abs, unused vars)
- commit [`3edd12c1911407d051bad549bbd5bd0f5c4559af`](https://gitlab.com/nsnam/ns-3-dev/-/commit/3edd12c1911407d051bad549bbd5bd0f5c4559af): Fix building with GCC 5 and subsequently clean up sgi-hashmap.h
- commit [`e5024de5b32b7ee9f525de5d9a0ed36a54648024`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e5024de5b32b7ee9f525de5d9a0ed36a54648024): Fix compilation with GCC 4.2.1 on FreeBSD 9

    ??? note
        Thanks to Domagoj Stolfa <shrinkd@gmail.com> for his aid in debugging this.

- commit [`dba84a150e655b1db441ecdcd7f263c8cae271c0`](https://gitlab.com/nsnam/ns-3-dev/-/commit/dba84a150e655b1db441ecdcd7f263c8cae271c0): Fix building with Clang 3.5
- commit [`e22f7b5958d1df8366cc333d20317405962df0ff`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e22f7b5958d1df8366cc333d20317405962df0ff): Make ordering of member variables in NSC TCP socket implementation header/source consistent
- commit [`6acf41814ea7378d559093ffbc18c4f84f15d20e`](https://gitlab.com/nsnam/ns-3-dev/-/commit/6acf41814ea7378d559093ffbc18c4f84f15d20e): Move tests outside ns3 namespace
- commit [`df005f262e7873c0d1836a28c65bc5415e79bc69`](https://gitlab.com/nsnam/ns-3-dev/-/commit/df005f262e7873c0d1836a28c65bc5415e79bc69): Introduce additional Time units (Year, Day, Hour, Minute)
- commit [`f1f6d270912c778865c688ffac1c845d345e4322`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f1f6d270912c778865c688ffac1c845d345e4322): Fix doxygen errors in src/network, excluding 'is not documented' missing documentation
- commit [`a3e7cb04e671083fcea9170c2dae70fd9385362e`](https://gitlab.com/nsnam/ns-3-dev/-/commit/a3e7cb04e671083fcea9170c2dae70fd9385362e): Remove unused consts to fix building with Clang 3.4 pre-release versions
- commit [`ad96327325c9a29c30b7e57d841af2504e57d6ad`](https://gitlab.com/nsnam/ns-3-dev/-/commit/ad96327325c9a29c30b7e57d841af2504e57d6ad): Fix optimized build with Clang 3.2+ (remove unused variables from tests)
- commit [`32b19bd983348884dbf69ca5d7a2bffc660f72c3`](https://gitlab.com/nsnam/ns-3-dev/-/commit/32b19bd983348884dbf69ca5d7a2bffc660f72c3): Bug 1779 - NS_UNUSED_GLOBAL not working in attribute test class declaration
- commit [`f781366d2e484edbad34c52f74d48482ad0e2f32`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f781366d2e484edbad34c52f74d48482ad0e2f32): Fix compilation with Clang 3.2 and newer versions, including Apple Clang 5.0

    ??? note
        Clang 3.2 requires all class members to be used in the code; this patch either removes class members that are not used or adds NS_UNUSED/NS_UNUSED_GLOBAL around them. Thanks to Andrey Mazo and Tommaso Pecorella for review.

- commit [`f9f3110086e5507c35dd3474327c7bb9e4d23046`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f9f3110086e5507c35dd3474327c7bb9e4d23046): Remove unused wifiMode variable, fix build
- commit [`e1f1e9a1adcbc686ae26784a42f1c0999d937650`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e1f1e9a1adcbc686ae26784a42f1c0999d937650): Revert 097891ca7dea (Change upper-bounded TimeChecker to actually do what documentation says) and fix documentation instead
- commit [`19c09725a96b8956d2d8f4ea4c57d68bde7ca11b`](https://gitlab.com/nsnam/ns-3-dev/-/commit/19c09725a96b8956d2d8f4ea4c57d68bde7ca11b): Change upper-bounded TimeChecker to actually do what documentation says
- commit [`17b897750cec08a40b4f7b364d15b0ad66ed2832`](https://gitlab.com/nsnam/ns-3-dev/-/commit/17b897750cec08a40b4f7b364d15b0ad66ed2832): Add Makefile wrapper for waf, to ease configuration in NetBeans, Eclipse and QtCreator
- commit [`b5891dce4141bb4cb3138323cb2216f899050012`](https://gitlab.com/nsnam/ns-3-dev/-/commit/b5891dce4141bb4cb3138323cb2216f899050012): Replace &lt;limits.h&gt; include by &lt;climits&gt;
- commit [`f97431bf10607f60bda3c8bbd59fee5716503dae`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f97431bf10607f60bda3c8bbd59fee5716503dae): Clean up core module for building with Clang

    ??? note
        This means removing unused private variables in random-variable-stream.{cc,h} and system-thread.h and fixing removing bad static_casts in calendar-scheduler.cc.

- commit [`80098cdd1cc25819630e2ef67e1c7809772e908d`](https://gitlab.com/nsnam/ns-3-dev/-/commit/80098cdd1cc25819630e2ef67e1c7809772e908d): Upgrade waf to 1.7.11.
- commit [`9659c4528e63ed7fa7f87c57ad1c7487f4ff31b6`](https://gitlab.com/nsnam/ns-3-dev/-/commit/9659c4528e63ed7fa7f87c57ad1c7487f4ff31b6): Fix building with Clang 3.0 without extra CXXFLAGS

    ??? note
        Clang identifies as GCC 4.2 to compilers which check for GCC version. This patch adds further check for clang and undefines __DEPRECATED macro in case Clang is detected. Newer versions of Clang are much stricter and still require CXXFLAGS for other warnings.

- commit [`b47d4aac23e237ea957992a886933f6ab534087a`](https://gitlab.com/nsnam/ns-3-dev/-/commit/b47d4aac23e237ea957992a886933f6ab534087a): Add missing limits.h include to nstime.h and print-introspected-doxygen.cc
- commit [`172e7aff8f1ec2b8d9f37aa3885791300f2700b1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/172e7aff8f1ec2b8d9f37aa3885791300f2700b1): Check for &lt;net/ethernet.h&gt; include before enabling fd-net-device module
- commit [`c0e64dac61cdee1c991743267c406b4379caec83`](https://gitlab.com/nsnam/ns-3-dev/-/commit/c0e64dac61cdee1c991743267c406b4379caec83): Fix Bug 1669 - ns-3 should support binding two and three (possibly more) arguments
- commit [`5b6db3ec128d9992317634e439d507b25b644361`](https://gitlab.com/nsnam/ns-3-dev/-/commit/5b6db3ec128d9992317634e439d507b25b644361): Update manual with Start/DoStart to Initialize/DoInitialize change
- commit [`59d75a4686f66e9516b383f26ab6a70387f2de3c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/59d75a4686f66e9516b383f26ab6a70387f2de3c): Update tutorial with Start/DoStart to Initialize/DoInitialize change
- commit [`53ec6a479e1d9dfc4875110171ae8f48b96f847d`](https://gitlab.com/nsnam/ns-3-dev/-/commit/53ec6a479e1d9dfc4875110171ae8f48b96f847d): Rename Start and DoStart methods to Initialize and DoInitialize

    ??? note
        The goal of this patch is to allows us to differentiate the Start/Stop
        functionality present in some classes from Initialize/Dispose functionality.

- commit [`6919cef0b3a3b136b31dc6b7b2ad3eb3813897e1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/6919cef0b3a3b136b31dc6b7b2ad3eb3813897e1): Backed out changeset e1e45baa7046, adding comment to log.cc to prevent confusion
- commit [`e5cd4dbd4e13a355987f267f95aead1856f156d9`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e5cd4dbd4e13a355987f267f95aead1856f156d9): Remove extra whitespace in some LogLevel labels
- commit [`44e8b40ac91c35f4c139d7f73c95a5b864ac7d60`](https://gitlab.com/nsnam/ns-3-dev/-/commit/44e8b40ac91c35f4c139d7f73c95a5b864ac7d60): Rename SequenceNumber TestSuite to sequence-number for consistency
- commit [`41cc7abc1e94eecdb9b1a61f7971236fdd335ab1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/41cc7abc1e94eecdb9b1a61f7971236fdd335ab1): Update release notes about Waf and create-module.py changes
- commit [`b656a0cab7ef7e631f671bc867f14e1c428b2872`](https://gitlab.com/nsnam/ns-3-dev/-/commit/b656a0cab7ef7e631f671bc867f14e1c428b2872): Introduce compound name for static TestSuite declaration and be stricter about allowed module name
- commit [`f90477b2033e219b135f406389693a357d8ed599`](https://gitlab.com/nsnam/ns-3-dev/-/commit/f90477b2033e219b135f406389693a357d8ed599): Fix INCLUDE_GUARD for helper in create-module.py
- commit [`ec787b2d61d88a395199f1c2cfb5a15dce080e3f`](https://gitlab.com/nsnam/ns-3-dev/-/commit/ec787b2d61d88a395199f1c2cfb5a15dce080e3f): Fix capitalize in create-module.py for module name containing dash
- commit [`4acc107d9742975de26894ba5da9c35fc3994f60`](https://gitlab.com/nsnam/ns-3-dev/-/commit/4acc107d9742975de26894ba5da9c35fc3994f60): Clean up function logging of energy module.
- commit [`3f41bbf326fac4e1abf2a9b00b4dabc4d85a4783`](https://gitlab.com/nsnam/ns-3-dev/-/commit/3f41bbf326fac4e1abf2a9b00b4dabc4d85a4783): Add proper license header to simple-device-energy-model.{h,cc}
- commit [`bbdb4231b38a68e4ce76e9fd9932766209e7420c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/bbdb4231b38a68e4ce76e9fd9932766209e7420c): Upgrade waf to 1.7.10 and fix included wscripts

    ??? note
        This is a massive upgrade removing almost all pre-waf 1.6 script code. In addition, this does away with custom pkgconfig.py script for making .pc files and replaces it with waf's builtin mechanism.

        Massive thanks to Alex Afanasyev for ideas and bugfixing, to Alina Quereilhac for bugfixing and testing, and to Tom Henderson for thorough testing.

- commit [`df67c9c116939aa52ca2deb5ea09e3f52b4fd8e4`](https://gitlab.com/nsnam/ns-3-dev/-/commit/df67c9c116939aa52ca2deb5ea09e3f52b4fd8e4): Improve logging of InetTopologyReader
- commit [`c9152825c264601d02a62ef3f4e15f40ff72f078`](https://gitlab.com/nsnam/ns-3-dev/-/commit/c9152825c264601d02a62ef3f4e15f40ff72f078): Fix INCLUDE_GUARD in create-module.py

    ??? note
        This patch fixes two separate issues: first, it replaces "-" by "_" in addition to capitalizing module name when creating include guards, second, it names it consistently with the rest of ns-3.

- commit [`80fe6e05ba323986ceb67313fe9794734e388d6d`](https://gitlab.com/nsnam/ns-3-dev/-/commit/80fe6e05ba323986ceb67313fe9794734e388d6d): Remove C headers and replace them by C++ headers if actually used
- commit [`d9f638d21176c15ffe211f08e24e1ce6906bb859`](https://gitlab.com/nsnam/ns-3-dev/-/commit/d9f638d21176c15ffe211f08e24e1ce6906bb859): Simplify topology-read example code a bit
- commit [`343c15bfd35ba58e349bd6b7a5dc669093bb56ff`](https://gitlab.com/nsnam/ns-3-dev/-/commit/343c15bfd35ba58e349bd6b7a5dc669093bb56ff): Fix encoding in wimax-iipv4.cc example
- commit [`e99b43d230c7f9046d4a404f613f1c667531527c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e99b43d230c7f9046d4a404f613f1c667531527c): Minor fixes and improvements to logging chapter in manual.
- commit [`ac157ff4ba211b4a8a5de612fd208b08a13c3f51`](https://gitlab.com/nsnam/ns-3-dev/-/commit/ac157ff4ba211b4a8a5de612fd208b08a13c3f51): Fix indentation in comment in ILP32 Python bindings.
- commit [`928431b698d6fa4f8a5a6e2d1ea0414981d94270`](https://gitlab.com/nsnam/ns-3-dev/-/commit/928431b698d6fa4f8a5a6e2d1ea0414981d94270): Do not install LTE scheduler test headers in ns3/ directory.
- commit [`062ca6a15353762c8633858d5b6130ec2ab72d7e`](https://gitlab.com/nsnam/ns-3-dev/-/commit/062ca6a15353762c8633858d5b6130ec2ab72d7e): Add newline at the end of file to silence gcc on FreeBSD 9.
- commit [`dab91377b386e028a0667b9d370c2da6a200ad3d`](https://gitlab.com/nsnam/ns-3-dev/-/commit/dab91377b386e028a0667b9d370c2da6a200ad3d): Remove NS_LOG_FUNCTION stuff from ::GetTypeId() functions.
- commit [`621e6ca2a6c8900d0568c696415bf8a5b36d0757`](https://gitlab.com/nsnam/ns-3-dev/-/commit/621e6ca2a6c8900d0568c696415bf8a5b36d0757): Allow using CXX='distcc g++' with ./waf configure.
- commit [`e640ed81af3d55bf9d51bf8e120d38aa1f7cd3b4`](https://gitlab.com/nsnam/ns-3-dev/-/commit/e640ed81af3d55bf9d51bf8e120d38aa1f7cd3b4): Clean up function logging of applications module.
- commit [`a476a9085fe31767bba4c2dbd9cdace9de9d29b1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/a476a9085fe31767bba4c2dbd9cdace9de9d29b1): Clean up OnOffApplication logging and connection notification, remove unused function declaration.
- commit [`0622524b8ea8f7373c304a19e1b194ffd523fe81`](https://gitlab.com/nsnam/ns-3-dev/-/commit/0622524b8ea8f7373c304a19e1b194ffd523fe81): Change to C++-style includes in log.cc.
- commit [`182aa787938f10e0d454b107edf22f2fa277992a`](https://gitlab.com/nsnam/ns-3-dev/-/commit/182aa787938f10e0d454b107edf22f2fa277992a): Document building with distcc in tutorial, add it to RELEASE_NOTES and CHANGES.html.
- commit [`a6836218f4463d46427158c64d281ce44588ba00`](https://gitlab.com/nsnam/ns-3-dev/-/commit/a6836218f4463d46427158c64d281ce44588ba00): Minor fixes and corrections to tutorial formatting.
- commit [`070eeaa39a9af206212552e8e8da688a65f8a36a`](https://gitlab.com/nsnam/ns-3-dev/-/commit/070eeaa39a9af206212552e8e8da688a65f8a36a): Minor fixes and corrections to manual formatting.
- commit [`5d88bed78fce81febee4a7ebfdb1dca994137209`](https://gitlab.com/nsnam/ns-3-dev/-/commit/5d88bed78fce81febee4a7ebfdb1dca994137209): Fix bug introduced by changeset 9137:822abb428976 Allow using CXX='distcc g++' with ./waf configure.
- commit [`c3b411ac94b51f9b8221e18d6e80c866c22e6f71`](https://gitlab.com/nsnam/ns-3-dev/-/commit/c3b411ac94b51f9b8221e18d6e80c866c22e6f71): Improve logging part in tutorial, and make clear distinction between logging level and logging macro.
- commit [`dd61b3dced47834b18adbc6f0bf92d020df5d848`](https://gitlab.com/nsnam/ns-3-dev/-/commit/dd61b3dced47834b18adbc6f0bf92d020df5d848): Add logging to default-simulator-impl.cc and fix some outdated documentation.
- commit [`aa554e051d66a4b14aa50eb3aa4c9423859d8ae8`](https://gitlab.com/nsnam/ns-3-dev/-/commit/aa554e051d66a4b14aa50eb3aa4c9423859d8ae8): Clean up core, network, internet, point-to-point tests that don't access private class attributes and methods in accordance to sample-test-suite.cc.
- commit [`fd0ca6f1b164b3b09a0e4b6d85f422af39c9a5c9`](https://gitlab.com/nsnam/ns-3-dev/-/commit/fd0ca6f1b164b3b09a0e4b6d85f422af39c9a5c9): Really fix bug 1345 - ns-3 should build with clang >= 3.0 (requires -Wno-deprecated due to sgi-hashmap.h)
- commit [`ed72cae14b68e71b994f93a7bdadd2268c7d0ee3`](https://gitlab.com/nsnam/ns-3-dev/-/commit/ed72cae14b68e71b994f93a7bdadd2268c7d0ee3): Fix MPI build (bug 1237 regression).
- commit [`71e380b55eeb23165282a9156306e2f97bcf6df4`](https://gitlab.com/nsnam/ns-3-dev/-/commit/71e380b55eeb23165282a9156306e2f97bcf6df4): Bug 1237 - code cleanups related to includes
- commit [`205780173c2ec9738629411852a7266387eee5b8`](https://gitlab.com/nsnam/ns-3-dev/-/commit/205780173c2ec9738629411852a7266387eee5b8): Fix logging in Ipv4L3Protocol::AddInterface and Ipv4L3Protocol::Receive.
- commit [`c56854fced523972f8ed3935365b54a28e2f3145`](https://gitlab.com/nsnam/ns-3-dev/-/commit/c56854fced523972f8ed3935365b54a28e2f3145): Cosmetic changes to NS_LOG_INFO log output of OnOffApplication and PacketSink for consistency with UdpEchoClient/UdpEchoServer
- commit [`7a16b3523695ea7e1554caf3e381fd2b582ba6c1`](https://gitlab.com/nsnam/ns-3-dev/-/commit/7a16b3523695ea7e1554caf3e381fd2b582ba6c1): Update CHANGES.html and RELEASE_NOTES for QueueMode and ErrorUnit.
- commit [`b5cac1da2405311bf83c90b3bb23bbe4d8c06b33`](https://gitlab.com/nsnam/ns-3-dev/-/commit/b5cac1da2405311bf83c90b3bb23bbe4d8c06b33): Use longer names for QueueMode and ErrorUnit enums and move them to Queue and RateErrorModel classes respectively.
- commit [`9d5db73acb2bb7de2177fb4c2b449b0b967b2da2`](https://gitlab.com/nsnam/ns-3-dev/-/commit/9d5db73acb2bb7de2177fb4c2b449b0b967b2da2): Add time to UdpEchoClient and UdpEchoServer NS_LOG_INFO output.
- commit [`5f350bece70598d47b917845fb4d8c25a99ddbfd`](https://gitlab.com/nsnam/ns-3-dev/-/commit/5f350bece70598d47b917845fb4d8c25a99ddbfd): UdpEcho NS_LOG_INFO bugfix (wrong address type) and cosmetic changes to log output
- commit [`33f5232a85d5d73b89e7524f44fa4db20ebb44c5`](https://gitlab.com/nsnam/ns-3-dev/-/commit/33f5232a85d5d73b89e7524f44fa4db20ebb44c5): Bug 1388 - LTE module doesn't build in optimized mode with GCC 4.7
- commit [`0083b436d06c683663983e6b2f8421d3ec710ec4`](https://gitlab.com/nsnam/ns-3-dev/-/commit/0083b436d06c683663983e6b2f8421d3ec710ec4): Additional static casts needed for gcc-4.7 compilation
- commit [`4dc22f07af788227f51f43e26ca3125358ca813e`](https://gitlab.com/nsnam/ns-3-dev/-/commit/4dc22f07af788227f51f43e26ca3125358ca813e): Still Bug 1327: disable VNUM in libraries, fix the .pc file deps
- commit [`ff86ca198decfc685f20b74c7223a15f690bc194`](https://gitlab.com/nsnam/ns-3-dev/-/commit/ff86ca198decfc685f20b74c7223a15f690bc194): Bug 1327 - Version installed ns-3 files
- commit [`2e6646f91984a698c1a5d00d5afeb64bd29b345c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/2e6646f91984a698c1a5d00d5afeb64bd29b345c): Bug 1332 - Generated .pc files have blank line above and below the text
- commit [`39d338dbeb44f6bb18dae22a35057e3330c3b246`](https://gitlab.com/nsnam/ns-3-dev/-/commit/39d338dbeb44f6bb18dae22a35057e3330c3b246): fix various doxygen errors
- commit [`9a9585a8df111a6d2f0d00db5aeb01611cef5cb7`](https://gitlab.com/nsnam/ns-3-dev/-/commit/9a9585a8df111a6d2f0d00db5aeb01611cef5cb7): Small typo in documentation in generic-phy.h
- commit [`0538e655aa664a1332aec043418f218da5e8fef9`](https://gitlab.com/nsnam/ns-3-dev/-/commit/0538e655aa664a1332aec043418f218da5e8fef9): standardize ns-3 namespace declaration format
- commit [`fe0667def860d0f07938aaa27eecd611a5631657`](https://gitlab.com/nsnam/ns-3-dev/-/commit/fe0667def860d0f07938aaa27eecd611a5631657): standardize emacs c++ mode comments
- commit [`7271e9fa6f6f7e994961568ff46fa0f0639c523c`](https://gitlab.com/nsnam/ns-3-dev/-/commit/7271e9fa6f6f7e994961568ff46fa0f0639c523c): bug 1203: Inconsistently named ifndef/define macros in ns-3 headers
- commit [`8a5d58bedae56e147f24bb732aaef1be9050a1e6`](https://gitlab.com/nsnam/ns-3-dev/-/commit/8a5d58bedae56e147f24bb732aaef1be9050a1e6): Clean up function logging for non-DCF part of stats module
- commit [`0d2da59558866bd02403429a9ec57084d5de0ab5`](https://gitlab.com/nsnam/ns-3-dev/-/commit/0d2da59558866bd02403429a9ec57084d5de0ab5): some tutorial index.rst fixes
- commit [`cc69b4f83f7eab27df7ca1c36c1232da8464f292`](https://gitlab.com/nsnam/ns-3-dev/-/commit/cc69b4f83f7eab27df7ca1c36c1232da8464f292): documentation file name fix
- commit [`1edd47a75152da15d20104787ded82fc1116e813`](https://gitlab.com/nsnam/ns-3-dev/-/commit/1edd47a75152da15d20104787ded82fc1116e813): fix TeX formulas after doxygen change

## RxDock

Description: [home page](https://rxdock.gitlab.io/), [Wikipedia page](https://en.wikipedia.org/wiki/RxDock).

Commits listed from [repository on GitLab](https://gitlab.com/rxdock/rxdock):

- commit [`d559761b4b23a32d7660a81b0cd4b5fdc1ffe53f`](https://gitlab.com/rxdock/rxdock/-/commit/d559761b4b23a32d7660a81b0cd4b5fdc1ffe53f): Dereferenced pointer for logging
- commit [`dca87a1b93ce6f09cf4d3c178524b981918ba36f`](https://gitlab.com/rxdock/rxdock/-/commit/dca87a1b93ce6f09cf4d3c178524b981918ba36f): Removed extra closing bracket
- commit [`1de35a6220109c5a01b17236bd701e0ba8102c3d`](https://gitlab.com/rxdock/rxdock/-/commit/1de35a6220109c5a01b17236bd701e0ba8102c3d): Updated website URL in source code
- commit [`2e15a612491fe5dc71816f6d42d1a175ed8fc928`](https://gitlab.com/rxdock/rxdock/-/commit/2e15a612491fe5dc71816f6d42d1a175ed8fc928): Added rationale for using Meson to Build system docs
- commit [`9500b8fa593bb519961d9bdbf7e1a1b26b3f559c`](https://gitlab.com/rxdock/rxdock/-/commit/9500b8fa593bb519961d9bdbf7e1a1b26b3f559c): Replaced custom configuration format with JSON-based
- commit [`f7feb0a1d99dda5f214a16a152d986fc31fef955`](https://gitlab.com/rxdock/rxdock/-/commit/f7feb0a1d99dda5f214a16a152d986fc31fef955): Added simple multiprocessing wrapper for rxcmd
- commit [`cd935d0b3f1fd3bc90b0a6f522f64d32a49be48b`](https://gitlab.com/rxdock/rxdock/-/commit/cd935d0b3f1fd3bc90b0a6f522f64d32a49be48b): Added a wide version of the logo
- commit [`a2ebc98e2276da47ef5f0a39ee536268ee245044`](https://gitlab.com/rxdock/rxdock/-/commit/a2ebc98e2276da47ef5f0a39ee536268ee245044): Added an assert to avoid null pointer dereference in Restart test
- commit [`dd0d541a16c5ae3312555f95b946ea7abe2500f2`](https://gitlab.com/rxdock/rxdock/-/commit/dd0d541a16c5ae3312555f95b946ea7abe2500f2): Replaced boolean asserts in tests with more informative ones
- commit [`c45b76b1499419416b7f210ff51a8f152220e732`](https://gitlab.com/rxdock/rxdock/-/commit/c45b76b1499419416b7f210ff51a8f152220e732): Const'd all static std::strings
- commit [`6f7ee056750803f5fc81ede1d066dcf1d8905f30`](https://gitlab.com/rxdock/rxdock/-/commit/6f7ee056750803f5fc81ede1d066dcf1d8905f30): Converted data/Elements.dat to a JSON-formatted file
- commit [`c6ed5c76e88cf729f92753ad1ed30526cae89b90`](https://gitlab.com/rxdock/rxdock/-/commit/c6ed5c76e88cf729f92753ad1ed30526cae89b90): Added .gitignore
- commit [`e0fc773fa184daedb4747dd3f27b2811e348b2bf`](https://gitlab.com/rxdock/rxdock/-/commit/e0fc773fa184daedb4747dd3f27b2811e348b2bf): Prefixed with rxdock. and lowercased scoring function names
- commit [`34107f2637b46f6b0aff9696c4c29a2b2d36280b`](https://gitlab.com/rxdock/rxdock/-/commit/34107f2637b46f6b0aff9696c4c29a2b2d36280b): Replaced rbcavity and rbdock with equivalent rxcmd commands
- commit [`569f2fe6df5401ce9b8d6780a487e570030e9a2a`](https://gitlab.com/rxdock/rxdock/-/commit/569f2fe6df5401ce9b8d6780a487e570030e9a2a): Introduced public API and started developing CLI using it

    ??? note
        Added Tabularize command for easy conversion to CSV using CLI.

        Added Transform command that replaces a number of Perl scripts used
        for sorting, naming, and filtering with the goal to eventually replace
        all presently bundled Perl and Python scripts.

        The public API should be considered work in progress at this point. At
        the time of the stable release, the public API will support a number
        of operations and will remain stable over time as the internal program
        structure continues to change.

- commit [`15b7f584f1a875ad71e55fc1f7a4e21ba599c928`](https://gitlab.com/rxdock/rxdock/-/commit/15b7f584f1a875ad71e55fc1f7a4e21ba599c928): Added quote printing function, will be used by future CLI
- commit [`9b74cdae73a0ca1bac97b0c41b2c3d38a8b7d296`](https://gitlab.com/rxdock/rxdock/-/commit/9b74cdae73a0ca1bac97b0c41b2c3d38a8b7d296): Moved symbol export macros from Rbt.h into a separate header

    ??? note
        Also removed unused headers from Rbt.h and related Config.h.

- commit [`73dd2cdebc179f32dbaf185b7ad4d6d49fc29af9`](https://gitlab.com/rxdock/rxdock/-/commit/73dd2cdebc179f32dbaf185b7ad4d6d49fc29af9): Added generation of the pkg-config file for librxdock
- commit [`8ed0f00d95e7b6a119cb18a244136c09712d104e`](https://gitlab.com/rxdock/rxdock/-/commit/8ed0f00d95e7b6a119cb18a244136c09712d104e): Enabled header installation
- commit [`8a637b96588dc0186284be77f1507b3c8dd20e09`](https://gitlab.com/rxdock/rxdock/-/commit/8a637b96588dc0186284be77f1507b3c8dd20e09): Updated include directives to use full header path
- commit [`64796a7e75ed92e4266b1ca191894e2cc0e491c9`](https://gitlab.com/rxdock/rxdock/-/commit/64796a7e75ed92e4266b1ca191894e2cc0e491c9): Removed obsolete build and documentation files
- commit [`371f9c79a592b8c939648f8a02ed430080734585`](https://gitlab.com/rxdock/rxdock/-/commit/371f9c79a592b8c939648f8a02ed430080734585): Moved files around

    ??? note
        Headers are now in include/rxdock/, implementations in lib/, executables
        in tools/, and tests are in tests/ with data in tests/data/.

- commit [`a63c9ab602be1bcba7005cf12b7cdf2cfc4eba83`](https://gitlab.com/rxdock/rxdock/-/commit/a63c9ab602be1bcba7005cf12b7cdf2cfc4eba83): Replaced logging cout statements with Loguru macros

    ??? note
        Removed BaseObject::{Get,Set}Trace functions and TRACE configuration
        directives from parameter files.

        Also added wraps for Loguru and {fmt}.

        Partial credit goes to Luka Vretenar <luka.vretenar@gmail.com> for
        helping with the grunt work of the conversion.

- commit [`e5c4841229072ad04933e9fb19f5aafd1da41f76`](https://gitlab.com/rxdock/rxdock/-/commit/e5c4841229072ad04933e9fb19f5aafd1da41f76): Added building and installation instructions

    ??? note
        Also removed obsolete building and installation instructions.

- commit [`b87e82de1e3e20510e3262d07557da54cb3e5f8a`](https://gitlab.com/rxdock/rxdock/-/commit/b87e82de1e3e20510e3262d07557da54cb3e5f8a): Replaced custom binary (de)serialization with JSON-based

    ??? note
        Used nlohmann_json for JSON input and output.

- commit [`3f48f3959703927bd35944a34740974980bbb281`](https://gitlab.com/rxdock/rxdock/-/commit/3f48f3959703927bd35944a34740974980bbb281): Introduced rxdock prefix for some Model data values

    ??? note
        Specifically, chrom, program, ri, and tethered_atoms are now lowercase
        fields prefixed with rxdock. (e.g. rxdock.ri, rxdock.chrom.0).

- commit [`61d33ab1e7fdd5e504cdd43e55916a2cdc512cfa`](https://gitlab.com/rxdock/rxdock/-/commit/61d33ab1e7fdd5e504cdd43e55916a2cdc512cfa): Changed rxdock::Error to inherit from std::exception
- commit [`cafe20ebb056a218b05428997ef370c533a39b20`](https://gitlab.com/rxdock/rxdock/-/commit/cafe20ebb056a218b05428997ef370c533a39b20): Removed Rbt prefix from class, function and type names

    ??? note
        Updated data files accordingly and renamed functions and methods as
        necessary where conflicts occured.

- commit [`37ceea592e076722f459277d6e31a20397ac6e03`](https://gitlab.com/rxdock/rxdock/-/commit/37ceea592e076722f459277d6e31a20397ac6e03): Renamed namespace Rbt to rxdock and moved everything under it

    ??? note
        Renamed functions where conflicts occured and added out of class
        declarations for some operators that were previously declared only as
        friends in classes to silence GCC warnings and fix MSVC errors. In
        particular, renamed rxdock::GetVersion() to rxdock::GetProgramVersion()
        to avoid conflicts with Win32 API function from &lt;sysinfoapi.h&gt; header.

- commit [`c0c3a3a05e59ab2804cb883866da809652841fa6`](https://gitlab.com/rxdock/rxdock/-/commit/c0c3a3a05e59ab2804cb883866da809652841fa6): Fixed MSVC error C3016

    ??? note
        Index variable 'i' in OpenMP 'for' statement in RbtDockingSite must
        have signed integral type.

- commit [`f1ea257c8d07c4795292c7592aa8351b638572d8`](https://gitlab.com/rxdock/rxdock/-/commit/f1ea257c8d07c4795292c7592aa8351b638572d8): Replaced the old binders and adaptors deprecated in C++11

    ??? note
        In particular, replaced std::unary_function, std::binary_function, and
        std::ptr_fun with std::function, std::bind2nd with std::bind, and
        std::mem_fun_ref with std::mem_fn.

- commit [`6bea1fa87995fd7364f922e43ce6fdc45bf652cc`](https://gitlab.com/rxdock/rxdock/-/commit/6bea1fa87995fd7364f922e43ce6fdc45bf652cc): Specified that rDock was developed at RiboTargets

    ??? note
        That occurence of rDock was wrongly generalized to |Dock| (so it can be
        rDock or RxDock depending on the value of the replacement text).

        Thanks to Sergio Ruiz Carmona <Sergio.RuizCarmona@baker.edu.au> for
        spotting this mistake and reporting it.

        Also changed one wrong occurence of rDock in the User guide to |Dock|,
        where we link to download links for RxDock.

- commit [`8e230b0f9a552fb27b41489c1d91e8f582621940`](https://gitlab.com/rxdock/rxdock/-/commit/8e230b0f9a552fb27b41489c1d91e8f582621940): Enabled building of code documentation using Doxygen
- commit [`d23b667c930242e0b0376b5cf4fe2bf0b8f6564e`](https://gitlab.com/rxdock/rxdock/-/commit/d23b667c930242e0b0376b5cf4fe2bf0b8f6564e): Created figures for cavity mapping methods section

    ??? note
        Partial credit goes to Patrik Nikolić <patrik.nikolic@rxtx.tech> for
        the composition of some figures.

- commit [`a64eb9af37625a7c6f1af8ab80e88c27435c8393`](https://gitlab.com/rxdock/rxdock/-/commit/a64eb9af37625a7c6f1af8ab80e88c27435c8393): Made rblist use MDL title in output if available
- commit [`036b9571cc23223e5b1ecf1f826445cfe5dd673e`](https://gitlab.com/rxdock/rxdock/-/commit/036b9571cc23223e5b1ecf1f826445cfe5dd673e): Added comma-separated values (CSV) file sink
- commit [`a9006f7be170c8dd7f3d12924f836eb18513ebca`](https://gitlab.com/rxdock/rxdock/-/commit/a9006f7be170c8dd7f3d12924f836eb18513ebca): Fixed compiler warnings reported with -Wextra

    ??? note
        - Initialized base class RbtContext in the copy constructor of the
        derived class RbtStringContext
        - \[-Wdeprecated-copy\] explicitely declared operator=(const &) for
        RbtCell and RbtVble

- commit [`a66699877b813e47493f52f5e7d64ba69ec23fbe`](https://gitlab.com/rxdock/rxdock/-/commit/a66699877b813e47493f52f5e7d64ba69ec23fbe): Added a warning in rbdock if there are unnamed ligands
- commit [`ea96f3f4df97aa06f105b5885873a16e50d8327e`](https://gitlab.com/rxdock/rxdock/-/commit/ea96f3f4df97aa06f105b5885873a16e50d8327e): Rebranded from rDock to RxDock

    ??? note
        Updated logos and documentation accordingly. Versioning changes:

        - Removed EXEVERSION which was wrong anyway since we haven't used
           CVS $Id$ values since forking.
        - Removed IDS_BUILD which we didn't use and it ain't going to work in
            the future if we want to support reproducible builds.
        - Restarted versioning from 0.1.0 since the plan is to use semantic
            versioning from now on. Removed separate include/VERSION and
            integrated into RbtResources.h which will eventually be generated
            by Meson at build time.

- commit [`50effa882a811e004683fe0b3f33263d1354e5d9`](https://gitlab.com/rxdock/rxdock/-/commit/50effa882a811e004683fe0b3f33263d1354e5d9): Uniformized program name in MDL title, added timestamp
- commit [`7105c061c478585b7f586cd127acca2a3cdb9707`](https://gitlab.com/rxdock/rxdock/-/commit/7105c061c478585b7f586cd127acca2a3cdb9707): Made rbdock skip ligand after more than 10 errors
- commit [`1b756fee2d73212875c717994cb13694bc4591c5`](https://gitlab.com/rxdock/rxdock/-/commit/1b756fee2d73212875c717994cb13694bc4591c5): Ported sdrmsd and sdtether to Python 3 and Open Babel 3

    ??? note
        Cleaned up inconsistent use of tabs and spaces and replaced old style
        string formatting (%) with new style (.format()). Used autopep8 for
        further PEP 8-compliant style fixes.

        Open Babel 3 puts pybabel module inside openbabel, so import has been
        changed to try that first and fall back to 2.x style import if the first
        import fails.

- commit [`566b230f1d2b5d17fc4e920e2efeffe323714230`](https://gitlab.com/rxdock/rxdock/-/commit/566b230f1d2b5d17fc4e920e2efeffe323714230): Changed Perl script header to make them portable

    ??? note
        In addition, ran perltidy on the scripts and removed a duplicate of the
        header in sdmodify.

- commit [`7bb61dc5c008cea417768bc599c1e802452e9bd4`](https://gitlab.com/rxdock/rxdock/-/commit/7bb61dc5c008cea417768bc599c1e802452e9bd4): Added estimation of remaining number of ligands and time
- commit [`710bb15503f794791ba3b3fee9051f566bb556be`](https://gitlab.com/rxdock/rxdock/-/commit/710bb15503f794791ba3b3fee9051f566bb556be): Added measuring and printing of docking time per ligand
- commit [`0cf7f6c1f1f9dad882aeb85cd803bb78c64a47d0`](https://gitlab.com/rxdock/rxdock/-/commit/0cf7f6c1f1f9dad882aeb85cd803bb78c64a47d0): Implemented the real grid using Eigen Tensor

    ??? note
        To make the change less distruptive, RowMajor order is still used, but
        the array indexing is now from 0 instead of 1, which simplifies the
        code quite a bit. Built-in Eigen functions are used where possible.

- commit [`5506d9531cef068cbcfb28c5cb7bd43eaf9105e5`](https://gitlab.com/rxdock/rxdock/-/commit/5506d9531cef068cbcfb28c5cb7bd43eaf9105e5): Replaced Nelder-Mead implemenation

    ??? note
        Nelder-Mead implementation used previously was previously built on top
        of TNT. Since the usage of TNT was replaced by Eigen, it's reasonable
        to use Eigen for Nelder-Mead as well. Thanks for the implementation
        guidance go to Matthieu Brucher: <http://blog.audio-tk.com/>

        Partial credit goes to Dominik Kinkela <dominikkinkela@gmail.com> for
        the experimentation regarding the implementation approach.

- commit [`ee6d3b47c6bddb36ce4e6cd8189849c7804fa483`](https://gitlab.com/rxdock/rxdock/-/commit/ee6d3b47c6bddb36ce4e6cd8189849c7804fa483): Check for CRLF line endings in RbtMdlFileSource
- commit [`fcf17c380cf9cb9e20ecd55cbe24b59ec6df49be`](https://gitlab.com/rxdock/rxdock/-/commit/fcf17c380cf9cb9e20ecd55cbe24b59ec6df49be): Made HTML documentation responsive on smaller screens

    ??? note
        Reduced CSS min-width from 450px to 240px.

- commit [`6263e4165564ad5de1efcddbb0b9fe062d81b0ea`](https://gitlab.com/rxdock/rxdock/-/commit/6263e4165564ad5de1efcddbb0b9fe062d81b0ea): Fix some alerts reported by LGTM

    ??? note
        - missing include guards
        - new without delete
        - declared variable hides function parameter
        - unsigned comparison with zero
        - dangerous/obsolete function asctime replaced with std::put_time

- commit [`b9cb3ac8a1985d748a8f6389e087e9d390f3d003`](https://gitlab.com/rxdock/rxdock/-/commit/b9cb3ac8a1985d748a8f6389e087e9d390f3d003): Enabled installation of binaries, library, and data

    ??? note
        Fixed wrong (missing or extra) executable permission on data files.

- commit [`a0ef7fa815b2bc596cf75fed21a8a1dece4d2d6f`](https://gitlab.com/rxdock/rxdock/-/commit/a0ef7fa815b2bc596cf75fed21a8a1dece4d2d6f): Used cxxopts instead of getopt for CLI

    ??? note
        Removed support in rbdock command for -t option without -C so -t now
        has a unique meaning. Previous meaning of -t without -C (filter file
        name) is provided via the newly added -f option. Now there is no need
        to distinguish during runtime which variant of -t has been requested,
        which simplifies the code and makes it more robust.

- commit [`b0bd7575abaa12b00e7a1ee9ae05ff737b956e99`](https://gitlab.com/rxdock/rxdock/-/commit/b0bd7575abaa12b00e7a1ee9ae05ff737b956e99): Replaced TNT with Eigen

    ??? note
        EIGEN_DONT_VECTORIZE define is required with the PGI C++ compiler, as
        otherwise the code doesn't compile due to a multiply defined function.

        More details are on the PGI User Forums topic "Error compiling with
        Eigen library": https://www.pgroup.com/userforum/viewtopic.php?t=6690

- commit [`33b8674a2add039d925d6544a72c2fdb8500ec7a`](https://gitlab.com/rxdock/rxdock/-/commit/33b8674a2add039d925d6544a72c2fdb8500ec7a): Added tronkko-dirent as fallback on Windows

    ??? note
        Normally this should only be used for MSVC as MinGW provides dirent.h,
        but it turns out that the provided dirent.h is not sufficient for our
        usage.

- commit [`b1a68b47744a567776a1a5c9a81a066985b31a6f`](https://gitlab.com/rxdock/rxdock/-/commit/b1a68b47744a567776a1a5c9a81a066985b31a6f): Added printing of a list of references at the end of run
- commit [`4d949c37c4ccba7da14db7e2df85dc3987258125`](https://gitlab.com/rxdock/rxdock/-/commit/4d949c37c4ccba7da14db7e2df85dc3987258125): Used standard C++11 RNG on Solaris and Windows/MSVC

    ??? note
        PCG fails to build on Solaris and Windows/MSVC. Use instead whatever the
        compiler and the standard library provide as the default C++11 RNG.

        Issues on GitHub:

        - Solaris: https://github.com/imneme/pcg-cpp/issues/42
        - Windows/MSVC: https://github.com/imneme/pcg-cpp/issues/11

- commit [`a17870831cd92307ee3f60354925f132996f7555`](https://gitlab.com/rxdock/rxdock/-/commit/a17870831cd92307ee3f60354925f132996f7555): Replaced custom Bjarne-inspired RNG with PCG

    ??? note
        PCG (pcg-random.org) is a family of simple fast space-efficient
        statistically good algorithms for random number generation. Unlike many
        general-purpose RNGs, they are also hard to predict.

        The C++ implementation follows the conventions of other C++11-style
        generators (WG21 N3551) and is available under the Apache License
        version 2.0.

- commit [`dd23f2c17310f325156d721c3c45bd9c46daa244`](https://gitlab.com/rxdock/rxdock/-/commit/dd23f2c17310f325156d721c3c45bd9c46daa244): Fixed memory leaks in OccupancyTest
- commit [`27539c4a125ec6941f1104f3e9c5e848cb46dc89`](https://gitlab.com/rxdock/rxdock/-/commit/27539c4a125ec6941f1104f3e9c5e848cb46dc89): Fixed memory leak in RbtRealGrid
- commit [`88116cb6a4134944cf593d1ffdb0833d9898c90b`](https://gitlab.com/rxdock/rxdock/-/commit/88116cb6a4134944cf593d1ffdb0833d9898c90b): Used standard C++ containers instead of Rbt typedefs and removed RbtContainers.h
- commit [`eb296f7f4392fb35a25518b450fc3092d4c8130b`](https://gitlab.com/rxdock/rxdock/-/commit/eb296f7f4392fb35a25518b450fc3092d4c8130b): Uniformized the help text of all rb* commands
- commit [`b78d72bb2f4f645a43f17ac676f8774b74957fa9`](https://gitlab.com/rxdock/rxdock/-/commit/b78d72bb2f4f645a43f17ac676f8774b74957fa9): Fixed linking of rb* commands with MSVC
- commit [`a6ac7a6e473c1f842d0f6a83dc89c35639f5938d`](https://gitlab.com/rxdock/rxdock/-/commit/a6ac7a6e473c1f842d0f6a83dc89c35639f5938d): Increased the fine threshold so MSVC passes the tests

    ??? note
        Changed 1E-10 to 1E-7, i.e. reduced by three orders of magnitude. 1E-4
        is used by default so 1E-7 is still finer than that.

        Unlike MSVC, GCC and Clang pass the tests with threshold down to 1E-14.

- commit [`83f4f033570f1d0b02ef6fb7155d28027b979de9`](https://gitlab.com/rxdock/rxdock/-/commit/83f4f033570f1d0b02ef6fb7155d28027b979de9): Fixed numerical type conversion warnings reported by MSVC
- commit [`686d9ec7a7c58063bd85b01774a05aa85c4003b0`](https://gitlab.com/rxdock/rxdock/-/commit/686d9ec7a7c58063bd85b01774a05aa85c4003b0): Added getters for accessing static member variables

    ??? note
        MSVC doesn't export static member variables as symbols. Replaced access
        to these variables with getters returning a (const) reference.

- commit [`afe5f41ee03a823a8b2d2b66995e2f2c5854e24b`](https://gitlab.com/rxdock/rxdock/-/commit/afe5f41ee03a823a8b2d2b66995e2f2c5854e24b): Fixed linking on Windows with MSVC

    ??? note
        Introduced a macro for __declspec(dllexport) and added where necessary.

- commit [`6d519ade49a9efc5d0bc8bd272de72a27d54d4d8`](https://gitlab.com/rxdock/rxdock/-/commit/6d519ade49a9efc5d0bc8bd272de72a27d54d4d8): Added GoogleTest fallback from Wrap DB
- commit [`428411e5ab41cbe886e11e2de2c208e12a2db339`](https://gitlab.com/rxdock/rxdock/-/commit/428411e5ab41cbe886e11e2de2c208e12a2db339): Changed testing to run rbcavity before unit tests

    ??? note
        This solution is suboptimal as it polutes the source directory with the
        generated .as files, but it is still far more convenient than having to
        manually run rbcavity before running the tests.

- commit [`db7745e496f7897d42a11949cbca898a8db88b55`](https://gitlab.com/rxdock/rxdock/-/commit/db7745e496f7897d42a11949cbca898a8db88b55): Changed testing to run rbdock after unit tests

    ??? note
        Cleaned up test checker Python script and made it compatible with
        Python 3, but decided not to use it because the results (that depend
        on a random number generator) weren't similar enough.

- commit [`592f18a91e952bb6bd3e31f1ed08ca13c6a22adc`](https://gitlab.com/rxdock/rxdock/-/commit/592f18a91e952bb6bd3e31f1ed08ca13c6a22adc): Fixed compiling on Windows with MSVC

    ??? note
        Defined M_PI where needed, added include &lt;iterator&gt; and &lt;functional&gt;
        where they are missing, replaced static variable size array allocation
        with dynamic allocation, and avoided using macro names from winbase.h
        (and possibly others):

        - max -> fintmax
        - FindAtom -> FindAtomInList
        - GetAtomName -> GetName
        - GetCurrentDirectory -> GetCurrentWorkingDirectory

- commit [`eca8b29eedda2cfd101db462fc5304499102acb8`](https://gitlab.com/rxdock/rxdock/-/commit/eca8b29eedda2cfd101db462fc5304499102acb8): Removed using std::type statements for containers
- commit [`6c7f6fd9373ea114b331c2a0abf40dd973921eb5`](https://gitlab.com/rxdock/rxdock/-/commit/6c7f6fd9373ea114b331c2a0abf40dd973921eb5): Fixed building on Solaris (_P is a system macro)
- commit [`1787ad6a78edab58d15581c1a53faeee68b01e7a`](https://gitlab.com/rxdock/rxdock/-/commit/1787ad6a78edab58d15581c1a53faeee68b01e7a): Renamed Tutorials to User guide

    ??? note
        Also added Docking strategies section to Tutorials, moved and retitled
        from Reference guide's Common use cases section.

- commit [`1e3d91a201054d2114816f40036ed5f6decd3665`](https://gitlab.com/rxdock/rxdock/-/commit/1e3d91a201054d2114816f40036ed5f6decd3665): Updated Sphinx-generated HTML documentation style

    ??? note
        - changed the document font to Bitter ht
        - changed the colors to match the logo purple and blue

- commit [`86c5d1d5b7fe2f8b552ad452a534041d694c77ee`](https://gitlab.com/rxdock/rxdock/-/commit/86c5d1d5b7fe2f8b552ad452a534041d694c77ee): Designed new modern style logo (inspired by original rDock logo)
- commit [`c4ed50bb646f78316ea8daed324934df9122ca3c`](https://gitlab.com/rxdock/rxdock/-/commit/c4ed50bb646f78316ea8daed324934df9122ca3c): Removed, commented out, or used nearly all unused variables
- commit [`4d1a083aad235eeb70f4a0f789696e1c13816356`](https://gitlab.com/rxdock/rxdock/-/commit/4d1a083aad235eeb70f4a0f789696e1c13816356): Added return statements in functions returning non-void
- commit [`4602c90b62efbb413dfe68530c713a47a085ff48`](https://gitlab.com/rxdock/rxdock/-/commit/4602c90b62efbb413dfe68530c713a47a085ff48): Adopted both No Code of Conduct and Code of Merit
- commit [`a6f5d0f54fcb7ece134a676579e2b01733fd7238`](https://gitlab.com/rxdock/rxdock/-/commit/a6f5d0f54fcb7ece134a676579e2b01733fd7238): Removed (and replaced) obsolete headers malloc.h and sys/dir.h
- commit [`d3246604dc3a4a25fdfcac14e96ea96f78f5e9c1`](https://gitlab.com/rxdock/rxdock/-/commit/d3246604dc3a4a25fdfcac14e96ea96f78f5e9c1): Replaced deprecated headers with cheader equivalents
- commit [`f965de764e377d960199aeab39543e2427ab8e72`](https://gitlab.com/rxdock/rxdock/-/commit/f965de764e377d960199aeab39543e2427ab8e72): Replaced NULL with nullptr (recommended in C++11)
- commit [`c1b1264a8c5ebd72a43ec8af4a05ea1369a7337c`](https://gitlab.com/rxdock/rxdock/-/commit/c1b1264a8c5ebd72a43ec8af4a05ea1369a7337c): Removed throw() from function defs (deprecated in C++11)
- commit [`5d26263d4e8858b27e8b8b2274c50dd3403e45a6`](https://gitlab.com/rxdock/rxdock/-/commit/5d26263d4e8858b27e8b8b2274c50dd3403e45a6): Removed usage of using (namespace) std(::) except for containers
- commit [`b41666acc8e8118c892a80ee05ea35f965f9d567`](https://gitlab.com/rxdock/rxdock/-/commit/b41666acc8e8118c892a80ee05ea35f965f9d567): Changed void main() to int main()
- commit [`39935e2324184c00e7e40914a615839025394b19`](https://gitlab.com/rxdock/rxdock/-/commit/39935e2324184c00e7e40914a615839025394b19): Used standard C++ types instead of Rbt* typedefs and removed RbtTypes.h
- commit [`bdf10247ff757e192706969e7d8d71b69d281e5a`](https://gitlab.com/rxdock/rxdock/-/commit/bdf10247ff757e192706969e7d8d71b69d281e5a): Replaced RbtString with std::string
- commit [`4fe4d88cf296f4efcfa6fe3e4aa541faac34ec46`](https://gitlab.com/rxdock/rxdock/-/commit/4fe4d88cf296f4efcfa6fe3e4aa541faac34ec46): De-GNUify: std::_Ios_Openmode -> std::ios_base::openmode
- commit [`ee7dd4b1de5e8aa57c88e88e531b1a4822151ffe`](https://gitlab.com/rxdock/rxdock/-/commit/ee7dd4b1de5e8aa57c88e88e531b1a4822151ffe): Adopted the LLVM coding style

    ??? note
        For now, just ran clang-format on the existing code without changing
        variable and function names and documented the new coding standards
        (LLVM coding standards with our additions).

- commit [`6a04065d4bd47104eba123a28f2837d925a4c5d6`](https://gitlab.com/rxdock/rxdock/-/commit/6a04065d4bd47104eba123a28f2837d925a4c5d6): Removed ISO/IEC 8859 characters from RbtSmarts.cxx
- commit [`f8ccd3fe06b3e84697a5a2449855406806920ac9`](https://gitlab.com/rxdock/rxdock/-/commit/f8ccd3fe06b3e84697a5a2449855406806920ac9): Replaced no-break space (\xC2\xA0) with space (\x20)
- commit [`d3a8630bdcf5bef6609870fe9a17fb0433d7b366`](https://gitlab.com/rxdock/rxdock/-/commit/d3a8630bdcf5bef6609870fe9a17fb0433d7b366): Removed extra semicolon after member function definition

    ??? note
        Also cleaned up two instances of extra semicolon after namespace
        definition.

- commit [`3b9c7185b022399cb760219cded5a71c2a344ff4`](https://gitlab.com/rxdock/rxdock/-/commit/3b9c7185b022399cb760219cded5a71c2a344ff4): Started writing Developer guide

    ??? note
        Covered target platforms, build system, documentation, and versioning.

- commit [`99b686d3bc4955951c628975d235781cebd9ec7a`](https://gitlab.com/rxdock/rxdock/-/commit/99b686d3bc4955951c628975d235781cebd9ec7a): Cleaned up reStructuredText of Reference guide
- commit [`2e8c4a63af686ac57291969fb93db76773614288`](https://gitlab.com/rxdock/rxdock/-/commit/2e8c4a63af686ac57291969fb93db76773614288): Used getopt() in place of popt and removed popt dependency
- commit [`5411733bcfcdc2cc43fbbdd98d928b2975c58eea`](https://gitlab.com/rxdock/rxdock/-/commit/5411733bcfcdc2cc43fbbdd98d928b2975c58eea): Added README file in markdown format
- commit [`ea41c6f43f4d4e8d20a5d04fe3c6514315595c90`](https://gitlab.com/rxdock/rxdock/-/commit/ea41c6f43f4d4e8d20a5d04fe3c6514315595c90): Assimilated the content from rdock.sourceforge.net
- commit [`9b0e8a9dc5d854381b2ae8add8f6a50ee804793f`](https://gitlab.com/rxdock/rxdock/-/commit/9b0e8a9dc5d854381b2ae8add8f6a50ee804793f): Removed duplicate license plain text files and added markdown
- commit [`9830775ada180ac28182567db854f97725042e74`](https://gitlab.com/rxdock/rxdock/-/commit/9830775ada180ac28182567db854f97725042e74): Cleaned up reStructuredText of Getting started guide
- commit [`34201cb4635145d4382a9f1c645ebd8221ca44a4`](https://gitlab.com/rxdock/rxdock/-/commit/34201cb4635145d4382a9f1c645ebd8221ca44a4): Introduced placeholder for reStructuredText documentation
- commit [`828d5e4149c4f541ebcbe653d93bc9d75a22c777`](https://gitlab.com/rxdock/rxdock/-/commit/828d5e4149c4f541ebcbe653d93bc9d75a22c777): Replaced PDF docs with newer versions from SourceForge
- commit [`55b7bdd413176b94bd76715b74bbfaefa9f38713`](https://gitlab.com/rxdock/rxdock/-/commit/55b7bdd413176b94bd76715b74bbfaefa9f38713): Replaced tmake with Meson build system

    ??? note
        The program builds with GCC as C++11 and C++11 will make future changes
        far easier so this will be the required version from now on.

- commit [`5d420d3190664db2c17722e9bd608d0b205dcc92`](https://gitlab.com/rxdock/rxdock/-/commit/5d420d3190664db2c17722e9bd608d0b205dcc92): Added workaround for empty parameter strings
- commit [`8c7bd8363d8e8db51608480430cb12df6a8ef53c`](https://gitlab.com/rxdock/rxdock/-/commit/8c7bd8363d8e8db51608480430cb12df6a8ef53c): Fixed compilation of tests
- commit [`8933bcfc584591dc9461dc0d1e382de23a9128d2`](https://gitlab.com/rxdock/rxdock/-/commit/8933bcfc584591dc9461dc0d1e382de23a9128d2): Fixed compilation of executable programs and library

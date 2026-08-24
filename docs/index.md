---
hide:
    - navigation
---

# RxTx

![Logo](images/rxtx-logo.svg)

My name is Vedran Miletic and I obtained my PhD in computer science in 2015 from [FER](https://www.fer.unizg.hr/). Afterwards, I completed a postdoc in computational biophysics at [HITS](https://www.h-its.org/) and served as the [principal investigator](https://group.miletic.net/en/people/principal-investigator/) of [GASERI](https://group.miletic.net/en/), a research group working in the fields of computational biochemistry and high-performance computing.

Presently, I am with [MPCDF](https://www.mpcdf.mpg.de/), but I kept this page up for historical reasons.

![Vedran Miletic](https://vedran.miletic.net/images/vm.jpg)

Based on the knowledge and experience I gathered in my group's [research](https://group.miletic.net/en/projects/) [work](https://group.miletic.net/en/publications/), I offer consulting services for scientific software, including [development](#development-and-maintenance), [testing](#testing-and-documentation-writing), [porting](#cross-platform-porting), and [deployment](#integration-and-deployment-scientific-workflow-design-and-automation) for academic and industrial needs.

## My portfolio of prior work

While I contributed to dozens of projects over time, I would like to highlight two:

- [GROMACS](https://www.gromacs.org/), the open-source molecular dynamics simulation software used by my group, which I [develop on an ongoing basis to serve our research requirements](https://group.miletic.net/en/people/principal-investigator/#gromacs), and
- [LLVM](https://llvm.org/), the collection of modular and reusable compiler and toolchain technologies, which I [patched to improve AMD Radeon Graphics Processing Unit and Instinct Accelerator support](https://group.miletic.net/en/people/principal-investigator/#llvm).

For more details and other projects, see the complete listing of [contributions to open-source software](https://group.miletic.net/en/people/principal-investigator/#open-source-software-contributions).

## The services I offer

<div class="grid cards" markdown>

- ### Development and maintenance

    ---

    I offer development and maintenance services for open-source or in-house developed scientific software. The services I offer include, but are not limited to:

    - adding a new feature, for example, developing a new module that implements a particular method,
    - improving existing functionality or fixing a known issue, for example, changing the software to remove limitations for solving a particular problem,
    - refactoring and modernizing the source code, for example, evolving from C++98 with dependency on legacy libraries and build systems to [C++](https://isocpp.org/std/status)[17](https://en.cppreference.com/w/cpp/17)/[20](https://en.cppreference.com/w/cpp/20)/[23](https://en.cppreference.com/w/cpp/23) with modern [open-source libraries](https://en.cppreference.com/w/cpp/links/libs) and [build](https://cmake.org/) [systems](https://mesonbuild.com/),
    - extending the application programming interface (API) for your particular requirements.

- ### Testing and documentation writing

    ---

    I offer to write new and improve existing unit, system, regression, and mutation tests for existing scientific software. I also offer build matrix and testing pipeline design for various software as a service (SaaS) and self-hosted continuous integration (CI) tools.

    I offer writing user- or developer-oriented documentation for existing scientific software, including the documentation of application programming interfaces (APIs). I also offer a setup of the documentation build process for producing printable and web-friendly output from the common source, with the style that matches your taste.

    For a portfolio of prior technical writings, see my posts on [GASERI blog](https://group.miletic.net/en/blog/). For an example of a produced (API) documentation, see [RxDock documentation](https://rxdock.gitlab.io/documentation/devel/html/) and [its API documentation](https://rxdock.gitlab.io/api-documentation/devel/html/).

- ### Cross-platform porting

    ---

    I offer software porting of existing scientific applications and libraries from and to Linux, [FreeBSD](https://www.freebsd.org/)/[NetBSD](https://www.netbsd.org/), Solaris/[illumos](https://illumos.org/), macOS, and Windows, including [MSVC](https://visualstudio.microsoft.com/vs/features/cplusplus/), [Cygwin](https://www.cygwin.com/), [MSYS2](https://www.msys2.org/)/[Mingw-w64](https://www.mingw-w64.org/), and [WSL](https://apps.microsoft.com/store/detail/windows-subsystem-for-linux/9P9TQF7MRM4R). For example, [my portfolio](#my-portfolio-of-prior-work) contains fixes to numerous issues related to porting GNU/Linux- and x86/AMD64-focused open-source scientific software such as [GROMACS](https://www.gromacs.org/), [ns-3](https://www.nsnam.org/), and [RxDock](https://rxdock.gitlab.io/) to various other operating systems, compilers, and platforms.

- ### Integration and deployment; scientific workflow design and automation

    ---

    I offer integration of existing open-source applications and libraries into your workflow, including deployment of server-side software on your on-premise or cloud infrastructure.

    I also offer assistance in choosing specific open-source software for your scientific workflow as well as workflow design and its automation using, for example, frameworks like [Snakemake](https://snakemake.github.io/) and [Nextflow](https://nextflow.io/).

</div>

## How to contact me

If you are an academic or industrial subject that is interested in my services, please get in touch with me. You can reach me by sending an e-mail to <info@miletic.net> or via the following contact form and I will get back to you as soon as possible.

<form action="https://formspree.io/f/xdovkkwr" method="POST">
    <p>
        <label for="name">Name</label><br>
        <input type="text" name="name" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="email">Email</label><br>
        <input type="email" name="email" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="subject">Subject</label><br>
        <input type="text" name="subject" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color)" required>
    </p>
    <p>
        <label for="message">Message</label><br>
        <textarea name="message" class="md-input md-input--stretch" style="color: var(--md-default-fg-color); background-color: var(--md-default-bg-color); height: 7rem; outline: none; resize: none" required></textarea>
    </p>
    <input type="text" name="_gotcha" style="display: none">
    <button type="submit" class="md-button md-button--primary">Send</button>
</form>

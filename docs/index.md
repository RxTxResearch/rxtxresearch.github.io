---
hide:
    - navigation
---

# Introduction

![Logo](images/rxtx-logo.svg)

> RxTx offers consulting services for scientific software, including development, testing, documentation writing, and deployment.

## Consulting services

Here at RxTx, we offer services for (open-source or in-house developed) scientific software that will help you accelerate your industrial drug discovery or academic basic research. See [our portfolio](portfolio.md) for details on previous contributions to open-source software. Visit [RxTx Research](research.md) for details on projects, publications, and talks.

### Scientific software development and maintenance

We offer software development based on customer or partner needs. For example, [RxDock](https://rxdock.gitlab.io/), the open-source molecular docking software we [modernized](research.md#modernization-modularization-and-active-maintenance-of-rxdock-a-fast-versatile-and-open-source-program-for-docking-ligands-to-proteins-and-nucleic-acids-april-2019-march-2022), and [GROMACS](https://www.gromacs.org/), the open-source molecular dynamics simulation software we use and customize, can also be extended to fit your needs. The software development services we offer include, but are not limited to:

- adding a new feature, for example, developing a new module that implements a particular method,
- improving existing functionality, for example, customizing the existing code for solving a particular problem,
- refactoring and modernizing code, for example, evolving from C++98 with dependency on legacy libraries and build systems to C++17 with modern [open-source libraries](https://en.cppreference.com/w/cpp/links/libs) and build systems,
- extending the application programming interface (API) for your particular requirements, and
- fixing a particular issue as soon as possible.

### Scientific software testing and documentation writing

We offer writing new and improving existing unit and system tests for existing scientific software. We also offer testing pipeline design for various software as a service (SaaS) and self-hosted continuous integration (CI) tools.

We offer writing user- or developer-oriented documentation for existing scientific software, including the documentation of application programming interfaces (APIs). We also offer setup of the documentation build process for producing printable and web-friendly output from the common source.

### Scientific software cross-platform porting

We offer software porting of existing scientific applications and libraries from and to Linux, [FreeBSD](https://www.freebsd.org/)/[DragonFly BSD](https://www.dragonflybsd.org/), Solaris/[illumos](https://illumos.org/), macOS, and Windows, including [MSVC](https://visualstudio.microsoft.com/vs/features/cplusplus/), [Cygwin](https://www.cygwin.com/), [MinGW](https://osdn.net/projects/mingw/)/[Mingw-w64](https://www.mingw-w64.org/), and [WSL](https://apps.microsoft.com/store/detail/windows-subsystem-for-linux/9P9TQF7MRM4R). For example, we fixed numerous issues related to porting GNU/Linux- and x86/AMD64-focused open-source scientific software such as [RxDock](https://rxdock.gitlab.io/) and [GROMACS](https://www.gromacs.org/) to various other operating systems, compilers, and platforms.

### Scientific software integration and deployment; workflow design and automation

We offer integration of existing open-source applications and libraries into your workflow, including deployment of server-side software on your on-premise or cloud infrastructure. We also assist in choosing specific open-source software for your scientific workflow and workflow design and automation.

## Contact us

For inquiries please reach out to us by e-mail at <info@rxtx.tech> or via the contact form below.

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

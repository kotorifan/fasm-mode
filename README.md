# fasm-mode
 `fasm-mode` is a major mode for editing [FASM][fasm] x86 assembly
 programs. It includes syntax highlighting, automatic indentation, and
 imenu integration. Unlike Emacs' generic `asm-mode`, it understands
 FASM-specific syntax. Requires Emacs 24.3 or higher.

 The keyword lists are up to date as of FASM 1.73.32.

# Installing with Quelpa
 If you prefer to use a package manager, you can use [quelpa-use-package].

 ```elisp
 ;; Install FASM
 (use-package fasm-mode
   :quelpa (fasm-mode :fetcher github :repo "GabrielFrigo4/fasm-mode"))
 ```

# Installing with Elpaca
 If you prefer to use a package manager, you can use [elpaca-use-package].

 ```elisp
 ;; Install FASM
 (use-package fasm-mode
   :ensure (:type git :host github :repo "GabrielFrigo4/fasm-mode"))
 ```

# Inspired by [nasm-mode]
 This mode was completely inspired by the [nasm-mode]

[fasm]: https://flatassembler.net/
[nasm-mode]: https://github.com/GabrielFrigo4/nasm-mode
[quelpa-use-package]: https://github.com/quelpa/quelpa-use-package
[elpaca-use-package]: https://github.com/progfolio/elpaca
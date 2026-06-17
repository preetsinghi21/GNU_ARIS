## Open Source Contributions
**Merged Pull Request:** PR #28

**Repository:** https://github.com/kovzol/aris

**Contribution Summary**

* Removed a redundant null terminator (`\0`) from a format string in `sexpr-process.c`.
* Fixed an infinite loop issue in `sexpr_quant_infer`.
* Submitted fixes through a pull request that was reviewed and merged into the official upstream repository.

**Technical Impact**

* Prevented silent output truncation caused by an embedded null terminator.
* Improved code correctness and maintainability.
* Resolved an edge case that could cause infinite execution during logical expression processing.

**Pull Request**

* https://github.com/kovzol/aris/pull/28

**Commits**

* `983a5fa` — Remove redundant null terminator in `sexpr-process.c` format string.
* `95f0b57` — Fix infinite loop in `sexpr_quant_infer` when `elim_sen` is not parenthesized.

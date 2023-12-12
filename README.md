# Asynchronous-Transfer-Mode-SystemVerilog-Module-with-Formal-Verification-SVA-on-OneSpin

In this project a SystemVerilog Assertion (sva) file was formulated to assert Specification of the Design that were provided with the sv files to ensure proper functionality of the project.

Specification of the design:
1. A cell is never corrected and dismissed at the same time.
2. An error-free cell is neither corrected nor dismissed.
3. All cells with multiple-bit errors are dismissed.
4. A first erroneous cell coming in is corrected if the error is a single-bit error and not a multiple-bit error.
5. A second erroneous cell is always dismissed.

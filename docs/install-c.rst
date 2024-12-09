C Installation Instructions
===========================

Assuming you have already completed the `base installation Instructions
<install.rst>`_, the rest of the C installation instructions is fairly simple:

1. change into the correct directory:

   .. code:: console

      $ cd path/to/qiskit-fermions

2. compile the `cext` crate:

   .. code:: console

      $ make cext

3. verify that everything worked by running the C API tests:

   .. code:: console

      $ make testc


You should now find these relevant files:

- `dist/c/lib/libqiskit_fermions.so` (the suffix can vary from OS to OS)
- `dist/c/include/qiskit_fermions.h`

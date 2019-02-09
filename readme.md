# stub-format
A python utility script for generating c or c++ function stubs and other simple formatting jobs.

- generate stub functions
- convert snake case to camel case
- convert camel case to snake case
- tabs to spaces
- remove comments
- align characters on consecutive lines
- insert a disclaimer at the top of each file
- replace #ifndef header guard with #pragma once

Usage:

```bash
python stub_format.py -stub -i test.h -p
```

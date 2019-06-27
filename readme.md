# stub-format
A python utility script for generating c or c++ function stubs and performing other simple formatting and code gen jobs.

- generate stub functions
- inject code to generate c++ tests
- convert snake case to camel case
- convert camel case to snake case
- tabs to spaces
- remove comments
- align characters on consecutive lines
- insert a disclaimer at the top of each file
- replace #ifndef header guard with #pragma once

Usage:

```bash
stub-format -stub -i test.h -p
```

***For best results add stub-format to your path, so you can call it from anywhere.***




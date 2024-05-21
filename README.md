# Makefile Template

A template Makefile that works under the following conditions:

1. All source files are under a folder named `src`
2. All header files are under a folder named `include`
3. All test files are under a folder named `test`

Sample directory structure:

```
.
├── Makefile
├── README.md
├── include
│   ├── main.h
│   ├── sll.h
│   └── thpool.h
├── src
│   ├── main.c
│   └── subfolder
│       ├── sll.c
│       └── thpool.c
└── test
    ├── test_sll.c
    ├── test_threadpool.c
    └── unity
        ├── unity.c
        ├── unity.h
        └── unity_internals.h
```
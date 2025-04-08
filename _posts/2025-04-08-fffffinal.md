---
layout: post
title:  "실습 글"
date:   2025-04-08 23:59:58 +0900
categories: test
---

# 간단한 C 코드

- argv.c

```powershell
#include <stdio.h>

int main(int argc, char *argv[]) {
    printf("hello world!\n");
    printf("argc is %d\n", argc);

    for (int i = 0; i < argc; i++) { 
        printf("argv[%d] is %s\n", i, argv[i]); 
    }

    return 0;
}

```

# 끝!

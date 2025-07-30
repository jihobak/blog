---
authors:
  - Joe
categories:
  - MCP
comments: true
date: 2025-07-29
description: Azure document Intelligence 를 기반으로한 pdf 파싱 MCP 를 만듭니다. 
draft: true
slug: mcp-server-building
tags:
  - llm
  - rag
---

# PDF parsing MCP 만들기

미리보기 테스트

<!-- more -->

## Azure Document Intelligence

azure parsing 제작기

### The Implementation


```python
def parsing(file_path):
    """parsing"""
    contents = di.parsing(file_path)
    return contents
```

#### thoughts
- hello from Korea.

---

_PDF parsing using Microsoft Azure DI_
## FIFO
### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 0
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              0 |
|                 1 |              - |

> Page 0 is allocated at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 0 at page frame 0 for execution.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 1
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              1 |
|                 1 |              - |

> Page 1 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 1 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 3
Execution Order: 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 3
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              3 |
|                 1 |              - |

> Page 3 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 3 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 0
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              0 |
|                 1 |              - |

> Page 0 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 0 at page frame 0 for execution.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4
FIFO: <- 1
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              1 |
|                 1 |              - |

> Page 1 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 1 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4
FIFO: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 3
Execution Order: 3 > 4
FIFO: <- 3
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              3 |
|                 1 |              - |

> Page 3 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4
FIFO: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 3 at page frame 0 for execution.

## LRU
### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 0
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              0 |
|                 1 |              - |

> Page 0 is allocated at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 0 at page frame 0 for execution.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 1
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              1 |
|                 1 |              - |

> Page 1 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 1 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 3
Execution Order: 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 3
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              3 |
|                 1 |              - |

> Page 3 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 3 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 0
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              0 |
|                 1 |              - |

> Page 0 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 0 at page frame 0 for execution.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4
LRU: <- 1
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              1 |
|                 1 |              - |

> Page 1 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 1 at page frame 0 for execution.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4
LRU: <- 2
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              2 |
|                 1 |              - |

> Page 2 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 2 at page frame 0 for execution.

### Executing: 3
Execution Order: 3 > 4
LRU: <- 3
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              3 |
|                 1 |              - |

> Page 3 replaced page 4 at page frame 0 for execution.

### Executing: 4
Execution Order: 4
LRU: <- 4
| Page Frame Number | Allocated Page |
| ----------------- | -------------- |
|                 0 |              4 |
|                 1 |              - |

> Page 4 replaced page 3 at page frame 0 for execution.

## Clock Variation Replacement
### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |             0 |
|                 1 |              - |          0 <- |

> Page 0 is allocated at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |          0 <- |
|                 1 |              4 |             0 |

> Page 4 is allocated at page frame 1 for execution.
> Pointer increased to 0.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |             0 |
|                 1 |              4 |          0 <- |

> Page 1 replaced page 0 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 2 replaced page 1 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 3
Execution Order: 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 3 replaced page 2 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 2 replaced page 3 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 0 replaced page 2 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 1 replaced page 0 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 2 replaced page 1 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 3
Execution Order: 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |             0 |
|                 1 |              4 |          0 <- |

> Reference bit is set to 0 at page frame 1.
> Pointer increased to 0.
> Page 3 replaced page 2 at page frame 0 for execution.
> Pointer increased to 1.

### Executing: 4
Execution Order: 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |             0 |
|                 1 |              4 |          1 <- |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

## Bit Shift Variation Replacement
### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |      10000000 |
|                 1 |              - |      00000000 |

> Page 0 is allocated at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |      01000000 |
|                 1 |              4 |      10000000 |

> Page 4 is allocated at page frame 1 for execution.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |      10000000 |
|                 1 |              4 |      01000000 |

> Page 1 replaced page 0 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |      01000000 |
|                 1 |              4 |      10100000 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      10000000 |
|                 1 |              4 |      01010000 |

> Page 2 replaced page 1 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      01000000 |
|                 1 |              4 |      10101000 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 3
Execution Order: 3 > 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |      10000000 |
|                 1 |              4 |      01010100 |

> Page 3 replaced page 2 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      10000000 |
|                 1 |              4 |      01010101 |

> Page 2 replaced page 3 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 0
Execution Order: 0 > 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |      10000000 |
|                 1 |              4 |      01010101 |

> Page 0 replaced page 2 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              0 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 1
Execution Order: 1 > 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |      10000000 |
|                 1 |              4 |      01010101 |

> Page 1 replaced page 0 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              1 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 2
Execution Order: 2 > 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      10000000 |
|                 1 |              4 |      01010101 |

> Page 2 replaced page 1 at page frame 0 for execution.

### Executing: 4
Execution Order: 4 > 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              2 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.

### Executing: 3
Execution Order: 3 > 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |      10000000 |
|                 1 |              4 |      01010101 |

> Page 3 replaced page 2 at page frame 0 for execution.

### Executing: 4
Execution Order: 4
| Page Frame Number | Allocated Page | Reference Bit |
| ----------------- | -------------- | ------------- |
|                 0 |              3 |      01000000 |
|                 1 |              4 |      10101010 |

> Page 4 is executable at page frame 1. Reference bit is set to 1.


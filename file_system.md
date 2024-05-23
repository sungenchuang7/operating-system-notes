# File System

# Disk Space Allocation
* Goals:
  * Fast sequential access
  * Fast random access
  * Ability to dyniamically grow
  * Minimize fragmentation
  
## Allocation Schemes

### Contiguous Allocation
*Each file occupies a contiguous region of blocks*

Pros:
* Fast random access (only one seek needed)
* CD-ROMs/DVD-ROMs

Cons:
* Inflexible (deletions might cause fragmentation)

### Linked List Allocation
*Each block of a file points to the next block of a file*

Pros: 
* No external fragmentation
  
Cons: 
* Random access is slow

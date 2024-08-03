# LRU Cache Implementation in Go

This repository contains a basic implementation of an LRU (Least Recently Used) Cache in Go. The cache has a fixed size, and it uses a combination of a doubly linked list and a hash map to efficiently manage the cache entries. 

## Overview

The cache keeps track of the most recently used items and removes the least recently used items when the cache reaches its capacity. The implementation includes:

- A `Node` struct representing each item in the cache.
- A `Queue` struct representing the doubly linked list.
- A `Cache` struct representing the LRU cache.
- A `Hash` map to quickly access the nodes in the cache.
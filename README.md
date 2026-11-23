# Design Patterns in Go

[简体中文](README.zh-CN.md)

A collection of 22 standalone Go exercises for creational, structural, and behavioral design patterns. Each numbered directory contains a `main.go` that demonstrates the pattern in a small example.

| Example | What to look for |
| --- | --- |
| [Factory](1_factory) | Create a concrete car through a shared interface. |
| [Proxy](9_proxy) | Put request checks and rate limiting in front of a sample handler. |
| [Strategy](14_strategy) | Swap LRU, FIFO, and LFU eviction strategies through the same cache interface. |
| [Observer](17_observe) | Notify registered observers when the subject changes. |

Run an example from the repository root in a shell that supports globbing. Each directory is a separate program.

```sh
go run ./14_strategy/*.go
```

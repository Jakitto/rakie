# Rakie

> Rakie is lucky and cakie~

## Intro

Rakie is a high performance event-driven server and client framework.

It works at any platform and simple delpoyment.

## Requirements

* Ruby 2.5+
* Linux 3.x+ / macOS 10.10+

## Perfomance

* System: `macOS 11.2.3`
* Protocol: `HTTP`
* Testing tool: `siege`

| Threads | Trans | Elap Time | Data Trans | Resp Time | Trans Rate | Throughput | Concurrent | OKAY | Failed |
| 1 single thread | 200000 | 24.51 | 7 | 0.02 | 8159.93 | 0.29 | 199.70 | 200000 | 0 |
| Multithread (4) | 200000 | 15.67 | 7 | 0.02 | 12763.24 | 0.45 | 198.55 | 200000 | 0 |
| Multithread (8) | 200000 | 13.88 | 7 | 0.01 | 14409.22 | 0.50 | 196.85 | 200000 | 0 |

## Notice

Project is under construction.

Debug log info is muted by default.

Setting `Rakie::Log.level` to change log level.

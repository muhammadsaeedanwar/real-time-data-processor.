# Real-Time Data Processing in C++

This project is a **real-time data stream processor** written in C++17.  
It simulates ingesting data streams, processing them with lightweight algorithms,  
and monitoring throughput — useful for demonstrating low-latency systems.

## Features
- Multithreading (std::thread, std::mutex)
- Streaming queue implementation
- Custom signal handling for clean shutdown
- Performance monitoring (records per second)

## Build Instructions

### Linux / macOS
```bash
g++ -std=c++17 -O2 -pthread -o realtime realtime_data_processing.cpp
./realtime

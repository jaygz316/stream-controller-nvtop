# GPU Monitor (nvtop) Plugin for StreamController

A StreamController plugin to monitor GPU information (percentages, clock speeds, memory usage, temperatures, and wattage) using `nvtop` on Linux. It features both text and graph views toggleable via button presses.

## Features
- **Comprehensive Monitoring:** Displays GPU usage, memory consumption, clock speeds, temperature, and power consumption.
- **Interactive Views:** Cycle between text summary, graph, and detailed views via key presses.
- **Robust Parsing:** Automatic GPU discovery and parsing of `nvtop` outputs.

## Requirements
- **OS:** Linux
- **Dependency:** [nvtop](https://github.com/Syllo/nvtop) (must be installed and available in your system PATH).

## Installation
Clone this repository into your StreamController plugins directory:
```bash
git clone https://github.com/jaygz316/stream-controller-nvtop.git
```

## Author
Created by [jaygz316](https://github.com/jaygz316).

## License
This project is licensed under the MIT License - see the [LICENSE](file:///home/jay/projects/streamController-nvtop-plugin/LICENSE) file for details.

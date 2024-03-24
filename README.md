# Cache Simulator

This repository contains a simple cache simulator implemented in C. The simulator consists of a memory subsystem with cache and memory modules. The cache is designed as a direct-mapped cache with a write-allocate policy.

## Features

- **Cache Simulation**: Simulates a direct-mapped cache with read and write operations.
- **Memory Module**: Emulates a memory subsystem with random data generation.
- **Cache Miss and Hit Handling**: Demonstrates cache hit and miss scenarios and performs appropriate actions.

## Implementation Details

- The cache is implemented with a fixed size and block size defined by constants.
- Memory is represented as a 2D array.
- Cache lines are implemented as structs containing validity, tag, and data fields.
- Cache is initialized and managed in memory-efficient ways.

## Usage

To run the cache simulator:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/cachesimulator.git
    ```

2. Navigate to the cloned directory:

    ```bash
    cd cachesimulator
    ```

3. Compile the source code:

    ```bash
    gcc -o cache cache.c
    ```

4. Run the executable:

    ```bash
    ./cache
    ```

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

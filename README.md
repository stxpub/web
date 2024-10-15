# Stacks Hub

This repo contains the front-end for hub.stx.pub. It's just a bunch of static HTML files.

## Features

- Miner power statistics for the last 144 blocks
- Visualization of block commits on the Stacks chain
- Mempool size tracking over time
- Mempool transaction analysis (popular contracts, fee distribution, size distribution, age distribution)
- Transaction decoding utility

## Technology Stack

- Frontend: HTML, CSS (Bulma), JavaScript (Alpine.js, Chart.js)
- Backend API: Go, go-chi, SQLite (not included in this repository)
- Additional libraries: HPCC WASM Graphviz

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [Unlicense](LICENSE).

## Acknowledgments

- Initial inspiration from [obycode's miner-vis](https://github.com/obycode/miner-sim/tree/miner-vis)
- Additional inspiration from [jcnelson's status.sh](https://github.com/jcnelson/status.sh/blob/main/status.sh)

## Contact

For any questions or feedback, please open an issue on this repository.

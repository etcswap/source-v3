# Uniswap V3 Optimism

[![Lint](https://github.com/Uniswap/uniswap-v3-core-optimism/actions/workflows/lint.yml/badge.svg)](https://github.com/Uniswap/uniswap-v3-core-optimism/actions/workflows/lint.yml)
[![Tests](https://github.com/Uniswap/uniswap-v3-core-optimism/actions/workflows/tests.yml/badge.svg)](https://github.com/Uniswap/uniswap-v3-core-optimism/actions/workflows/tests.yml)
[![npm version](https://img.shields.io/npm/v/@uniswap/v3-core-optimism/latest.svg)](https://www.npmjs.com/package/@uniswap/v3-core-optimism/v/latest)

This repository contains the core smart contracts for the Uniswap V3 Protocol forked for Optimism.
For higher level contracts, see the [uniswap-v3-periphery-optimism](https://github.com/Uniswap/uniswap-v3-periphery-optimism)
repository.

## Licensing

The primary license for Uniswap V3 Core is the Business Source License 1.1 (`BUSL-1.1`), see [`LICENSE`](./LICENSE).

### Exceptions

- All files in `contracts/interfaces/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/interfaces/LICENSE`](./contracts/interfaces/LICENSE)
- Several files in `contracts/libraries/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/libraries/LICENSE_GPL`](contracts/libraries/LICENSE_GPL)
- `contracts/libraries/FullMath.sol` is licensed under `MIT` (as indicated in its SPDX header), see [`contracts/libraries/LICENSE_MIT`](contracts/libraries/LICENSE_MIT)
- All files in `contracts/test` remain unlicensed.

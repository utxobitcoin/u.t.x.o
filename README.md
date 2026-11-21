# u.t.x.o

A dark crypto charting workbench built around [LuxAlgo Vela](https://github.com/LuxAlgo/Vela), Binance market data and the Vela PineTS scripting addon.

## Stack
- React + TypeScript + Vite
- `@luxalgo/vela` chart engine and Binance provider
- `@luxalgo/vela-pinets` + `pinets` Pine Script runtime
- Monaco Editor for the script workspace

## Run locally
```bash
npm install
npm run dev
```

## Initial market universe
BTCUSDT, ETHUSDT, SOLUSDT, HYPEUSDT, XMRUSDT.

## Licensing note
Vela core is Apache-2.0. The PineTS addon/runtime has separate AGPL-3.0 licensing obligations. Review both licenses before distributing a hosted or commercial deployment, and retain Vela attribution as required by its NOTICE.

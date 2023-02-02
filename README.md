# Mises Stationarity Index

The code to run [msindex.net](https://www.msindex.net).

## Run Locally
You will need a FRED API key to get Z1 data. Go [here](https://fred.stlouisfed.org/docs/api/api_key.html) for more info. You'll need to create an account.

Install [bun](https://github.com/oven-sh/bun#install).

Then run
```
git clone github.com/ckrowland/msindex
cd msindex
export FRED_KEY=<your_fred_key>
bun install
bun run main.ts
```

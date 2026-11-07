# ess-instrument-nightly

Nightly results of the [ESS instrument models](https://git.esss.dk/dmsc-instrumentmodels)
built and run with McStas from [McCode](https://github.com/mccode-dev/McCode) `main`:
<https://mccode.org/ess-instrument-nightly/>

The tests run in McCode's `mcstas-ess-instruments` workflow (one column per
instrument), which dispatches this repository's `nightly-site` workflow to
publish the site (McCode's reusable `nightly-site.yml`). `history/` holds the
per-night summaries; the `releases` hold the raw output per instrument for 14 nights.

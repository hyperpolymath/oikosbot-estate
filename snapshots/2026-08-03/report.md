# Estate Economics Report

## Frontier (theta_ccr = 1.0)

| repo | theta_ccr |
|---|---|
| hyperpolymath/awesome-idris2 | 1.0000 |
| hyperpolymath/haec | 1.0000 |
| hyperpolymath/hypatia | 1.0000 |
| hyperpolymath/oikosbot | 1.0000 |
| hyperpolymath/proof-of-work | 1.0000 |
| hyperpolymath/quandledb | 1.0000 |
| hyperpolymath/stateful-artefacts | 1.0000 |
| hyperpolymath/the-metadatastician | 1.0000 |
| metadatastician/enaction-engine | 1.0000 |

## Worst 20 off-frontier (with peers)

| repo | theta_ccr | peers |
|---|---|---|
| hyperpolymath/.github | 0.0000 |  |
| hyperpolymath/Axiology.jl | 0.0000 |  |
| hyperpolymath/JuliaPackage-Reuse-Audit.jl | 0.0000 |  |
| hyperpolymath/KnotTheory.jl | 0.0000 |  |
| hyperpolymath/a2ml-estate-normalizer | 0.0000 |  |
| hyperpolymath/awesome-agda | 0.0000 |  |
| hyperpolymath/awesome-fsharp | 0.0000 |  |
| hyperpolymath/awesome-ipfs | 0.0000 |  |
| hyperpolymath/awesome-ocaml | 0.0000 |  |
| hyperpolymath/awesome-provable | 0.0000 |  |
| hyperpolymath/cargo-zigbuild | 0.0000 |  |
| hyperpolymath/filesoup | 0.0000 |  |
| hyperpolymath/gitbot-fleet | 0.0000 |  |
| hyperpolymath/glyphbase | 0.0000 |  |
| hyperpolymath/hermeneia | 0.0000 |  |
| hyperpolymath/hotchocolabot | 0.0000 |  |
| hyperpolymath/hpm-github-api-rsr | 0.0000 |  |
| hyperpolymath/hpm-http-client-rsr | 0.0000 |  |
| hyperpolymath/hpm-json-rsr | 0.0000 |  |
| hyperpolymath/kitchenspeak | 0.0000 |  |

## X-inefficiency

X-inefficiency here is our own framing (Leibenstein has no software-engineering literature): real input consumed, zero verified output produced.

| repo | wall_minutes |
|---|---|
| hyperpolymath/.github | 15.23 |
| hyperpolymath/Axiology.jl | 3236.60 |
| hyperpolymath/JuliaPackage-Reuse-Audit.jl | 6163.82 |
| hyperpolymath/KnotTheory.jl | 1224.03 |
| hyperpolymath/a2ml-estate-normalizer | 0.05 |
| hyperpolymath/awesome-agda | 89.37 |
| hyperpolymath/awesome-fsharp | 209.22 |
| hyperpolymath/awesome-ipfs | 52.03 |
| hyperpolymath/awesome-ocaml | 89.70 |
| hyperpolymath/awesome-provable | 26.38 |
| hyperpolymath/cargo-zigbuild | 222.18 |
| hyperpolymath/echidna | 7.27 |
| hyperpolymath/filesoup | 1041.87 |
| hyperpolymath/gitbot-fleet | 15.82 |
| hyperpolymath/glyphbase | 1090.80 |
| hyperpolymath/hermeneia | 7.38 |
| hyperpolymath/hotchocolabot | 0.38 |
| hyperpolymath/hpm-github-api-rsr | 0.05 |
| hyperpolymath/hpm-http-client-rsr | 0.05 |
| hyperpolymath/hpm-json-rsr | 0.05 |
| hyperpolymath/kitchenspeak | 0.07 |
| hyperpolymath/lfs-shared | 151.88 |
| hyperpolymath/live-files | 23281.35 |
| hyperpolymath/llm-grace | 3342.65 |
| hyperpolymath/methodologies | 1164.98 |
| hyperpolymath/network-outpost | 24.90 |
| hyperpolymath/nextgen-language-evangeliser | 5917.75 |
| hyperpolymath/nextgen-typing | 1902.23 |
| hyperpolymath/php-aegis | 4100.50 |
| hyperpolymath/preference-injector | 1407.05 |
| hyperpolymath/proof-burrower | 1368.62 |
| hyperpolymath/road-skate | 4456.92 |
| hyperpolymath/scm2a2ml | 103.37 |
| hyperpolymath/self-destructing-git-garbage | 43.23 |
| hyperpolymath/universal-language-server-plugin | 3906.68 |
| hyperpolymath/vscode-a2ml | 1791.93 |
| metadatastician/paint-type | 116.38 |
| metadatastician/progblocks | 20.97 |

## Independence

| pair | pearson r |
|---|---|
| wall_minutes~size_kb | -0.0486 |
| wall_minutes~verified_success_runs | 0.1520 |

## Confidence

| metric | confidence |
|---|---|
| carbon_g | Estimated |
| energy_kwh | Calibrated |
| imputed_cost_usd | Calibrated |
| wall_minutes | Measured |

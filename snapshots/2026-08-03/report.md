# Estate Economics Report

## Frontier (theta_ccr = 1.0)

| repo | theta_ccr |
|---|---|
| hyperpolymath/awesome-idris2 | 1.0000 |
| hyperpolymath/haec | 1.0000 |
| hyperpolymath/hypatia | 1.0000 |
| hyperpolymath/oikosbot | 1.0000 |
| hyperpolymath/proof-of-work | 1.0000 |
| hyperpolymath/the-metadatastician | 1.0000 |
| metadatastician/f117a-stealth-glider | 1.0000 |
| metadatastician/groove | 1.0000 |

## Worst 20 off-frontier (with peers)

| repo | theta_ccr | peers |
|---|---|---|
| hyperpolymath/JuliaPackage-Reuse-Audit.jl | 0.0000 |  |
| hyperpolymath/a2ml-estate-normalizer | 0.0000 |  |
| hyperpolymath/awesome-agda | 0.0000 |  |
| hyperpolymath/awesome-ipfs | 0.0000 |  |
| hyperpolymath/awesome-ocaml | 0.0000 |  |
| hyperpolymath/awesome-provable | 0.0000 |  |
| hyperpolymath/glyphbase | 0.0000 |  |
| hyperpolymath/hotchocolabot | 0.0000 |  |
| hyperpolymath/hpm-github-api-rsr | 0.0000 |  |
| hyperpolymath/hpm-http-client-rsr | 0.0000 |  |
| hyperpolymath/hpm-json-rsr | 0.0000 |  |
| hyperpolymath/kitchenspeak | 0.0000 |  |
| hyperpolymath/live-files | 0.0000 |  |
| hyperpolymath/trope-checker | 0.0000 |  |
| metadatastician/paint-type | 0.0000 |  |
| hyperpolymath/cicd-squabbler | 0.0039 | metadatastician/f117a-stealth-glider (0.024), metadatastician/groove (0.008) |
| hyperpolymath/ambientops | 0.0040 | hyperpolymath/haec (0.123) |
| hyperpolymath/robot-vacuum-cleaner | 0.0048 | hyperpolymath/haec (0.822) |
| hyperpolymath/julia-ecosystem | 0.0050 | hyperpolymath/awesome-idris2 (0.043), metadatastician/groove (0.303) |
| hyperpolymath/llm-grace | 0.0060 | hyperpolymath/awesome-idris2 (0.006), metadatastician/groove (0.006) |

## X-inefficiency

X-inefficiency here is our own framing (Leibenstein has no software-engineering literature): real input consumed, zero verified output produced.

| repo | wall_minutes |
|---|---|
| hyperpolymath/JuliaPackage-Reuse-Audit.jl | 6163.82 |
| hyperpolymath/a2ml-estate-normalizer | 0.05 |
| hyperpolymath/awesome-agda | 89.37 |
| hyperpolymath/awesome-ipfs | 52.03 |
| hyperpolymath/awesome-ocaml | 89.70 |
| hyperpolymath/awesome-provable | 26.38 |
| hyperpolymath/echidna | 7.27 |
| hyperpolymath/glyphbase | 1090.80 |
| hyperpolymath/hotchocolabot | 0.38 |
| hyperpolymath/hpm-github-api-rsr | 0.05 |
| hyperpolymath/hpm-http-client-rsr | 0.05 |
| hyperpolymath/hpm-json-rsr | 0.05 |
| hyperpolymath/kitchenspeak | 0.07 |
| hyperpolymath/live-files | 23281.35 |
| metadatastician/paint-type | 116.38 |

## Independence

| pair | pearson r |
|---|---|
| wall_minutes~size_kb | -0.0486 |
| wall_minutes~verified_success_runs | 0.1060 |

## Confidence

| metric | confidence |
|---|---|
| carbon_g | Estimated |
| energy_kwh | Calibrated |
| imputed_cost_usd | Calibrated |
| wall_minutes | Measured |

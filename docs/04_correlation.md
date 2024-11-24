# Correlation analysis

To perform correlation, you need to use the `correlation_operator`

| `Observation` | `A` | `B` | `C` | `D` | `E`|
| ----------- | - | - | - | - | - |
| `obs1` | 2.2 | 1.0 | 2.3| 5.2 | 0.5 |
| `obs2` | 2.2 | 1.0 | 2.3| 5.2 | 0.5 |
| `obs3` | 2.2 | 1.0 | 2.3| 5.2 | 0.5 |

## One vs. One
e.g. `A` vs. `B`

* Drag `A` to `Y-axis`
* Drag `B` to `X-axis`
* Select the correlation operator
* Run

## One vs. All
e.g., `A` vs. (`A`, `B`, `C`, `D`, `E`)

* Gather `A`, `B`, `C`, `D`, `E`, this creates `gs0.variable` and `gs0.value`
* Drag `A` to `Y-axis`
* Drag `gs0.value` to `X-axis`
* Drag `gs0.vaiable` to `cols`
* Select the correlation operator
* Run

## Many vs. Many
e.g., (`A`, `B`) vs. (`C`, `D`, `E`)

* Gather `A`, `B`, this creates `gs0.variable` and `gs0.value`
* Gather `C`, `D`, `E`, this creates `gs1.variable` and `gs1.value`
* Drag `gs0.value` to `Y-axis`
* Drag `gs0.vaiable` to `rows`
* Drag `gs1.value` to `X-axis`
* Drag `gs1.vaiable` to `cols`
* Select the correlation operator
* Run


## All vs All

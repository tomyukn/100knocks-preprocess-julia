# データサイエンス100本ノック（構造化データ加工編）

## Setup

```text
pkg> activate .
pkg> add Conda
julia> import Conda
julia> Conda.add(["jupyterlab"])
pkg> add CSV, DataFrames, DataFramesMeta, IJulia

julia> import IJulia
julia> IJulia.jupyterlab(dir=pwd(), detached=true)
```

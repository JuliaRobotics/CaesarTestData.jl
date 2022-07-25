# Lidar Data
## ./pandar subfolder

Lidar data in built environment.  Serialized with Julia 1.7 `Serialization.jl` and `Caesar.jl ` at v0.13.
```julia
using Colors, Caesar
using Serialization

data = deserialize("_pandar_PCLPointCloud2.jldat")
```

## ./simpleICP subfolder

Data initially intended for building regression tests of point cloud alignment algorithms in the JuliaRobotics set of packages.

Copied from [pglira](https://github.com/pglira/simpleICP) July 2022.  The data was duplicated here since rework of the pglira location is anticipated, based on independent comments from [Discourse](https://discourse.julialang.org/t/any-packages-for-point-cloud-registration/54679/3)


<a id='Tutorial-1'></a>

# Tutorial


[Documentation](../index.md#Documentation-1)


[Index](../index.md#Index-1)


[Functions](../lib/functions.md#Functions-1)


[`Main.Mod.func(x)`](../lib/functions.md#Mod.func-Tuple{Any})


[`Main.Mod.T`](../lib/functions.md#Mod.T)


```jldoctest
julia> using Base.Meta # `nothing` shouldn't be displayed.

julia> Meta
Base.Meta

julia> a = 1
1

julia> b = 2;

julia> a + b
3
```


```jldoctest
a = 1
b = 2
a + b

# output

3
```




```jldoctest
a = 1
b = 2
a / b

# output

0.5
```


```jldoctest
julia> a = 1;

julia> b = 2
2

julia> a / b
0.5
```


```
               [1m[92m_[0m
   [1m[94m_[0m       [0m_[0m [1m[91m_[1m[92m(_)[1m[95m_[0m     |  A fresh approach to technical computing
  [1m[94m(_)[0m     | [1m[91m(_)[0m [1m[95m(_)[0m    |  Documentation: http://docs.julialang.org
   [0m_ _   _| |_  __ _[0m   |  Type "?help" for help.
  [0m| | | | | | |/ _` |[0m  |
  [0m| | |_| | | | (_| |[0m  |  Version 0.6.0-pre.alpha.150 (2017-03-16 05:46 UTC)
 [0m_/ |\__'_|_|_|\__'_|[0m  |  Commit 102800a543 (0 days old master)
[0m|__/[0m                   |  x86_64-apple-darwin16.4.0

julia>
```


```jldoctest
julia> # First definition.
       function f(x, y)
           x + y
       end
       #
       # Second definition.
       #
       type T
           x
       end

julia> isdefined(:f), isdefined(:T) # Check for both definitions.
(true,true)

julia> import Base

julia> using Base.Meta

julia> r = isexpr(:(using Base.Meta), :using); # Discarded result.

julia> !r
false
```


```jldoctest
julia> for i = 1:5
           println(i)
       end
1
2
3
4
5

julia> println("Printing with semi-comma ending.");
Printing with semi-comma ending.

julia> warn("...");
WARNING: ...

julia> div(1, 0)
ERROR: DivideError: integer division error
[...]

julia> info("...")   # ...
       println("a"); # Semi-colons *not* on the last expression shouldn't suppress output.
       println(1)    # ...
       2             # ...
INFO: ...
a
1
2

julia> info("...")   # ...
       println("a"); # Semi-colons *not* on the last expression shouldn't suppress output.
       println(1)    # ...
       2;            # Only those in the last expression.
INFO: ...
a
1

```


```jldoctest
a = 1
b = 2; # Semi-colons don't affect script doctests.

# output

2
```


```julia
julia> f(x) = (sleep(x); x)
f (generic function with 1 method)

  0.137167 seconds (15.65 k allocations: 768.624 KiB)
julia> @time f(0.1);
```


```julia
julia> f(0.01)
0.01

julia> div(1, 0)
ERROR: DivideError: integer division error
```



<a id='Documentation-1'></a>

# Documentation


<a id='Index-Page-1'></a>

## Index Page

- [Documentation](index.md#Documentation-1)
    - [Index Page](index.md#Index-Page-1)
    - [Functions Contents](index.md#Functions-Contents-1)
    - [Tutorial Contents](index.md#Tutorial-Contents-1)
    - [Index](index.md#Index-1)
        - [Embedded `@ref` links headers: [`ccall`](lib/functions.md#ccall)](index.md#Embedded-@ref-links-headers:-[ccall](@ref)-1)
    - [Raw Blocks](index.md#Raw-Blocks-1)
- [Symbols in doctests](index.md#Symbols-in-doctests-1)
- [Named doctests](index.md#Named-doctests-1)
- [Sanitise module names](index.md#Sanitise-module-names-1)
- [Issue398](index.md#Issue398-1)
- [Issue418](index.md#Issue418-1)


<a id='Functions-Contents-1'></a>

## Functions Contents

- [Function Index](lib/functions.md#Function-Index-1)
- [Functions](lib/functions.md#Functions-1)
- [Foo](lib/functions.md#Foo-1)
    - [Foo](lib/functions.md#Foo-2)
        - [Foo](lib/functions.md#Foo-3)
- [Autodocs](lib/functions.md#Autodocs-1)
    - [AutoDocs Module](lib/functions.md#AutoDocs-Module-1)
    - [Functions, Modules, and Macros](lib/functions.md#Functions,-Modules,-and-Macros-1)
    - [Constants and Types](lib/functions.md#Constants-and-Types-1)
    - [Autodocs by Page](lib/functions.md#Autodocs-by-Page-1)
- [Named docstring `@ref`s](lib/functions.md#Named-docstring-@refs-1)


<a id='Tutorial-Contents-1'></a>

## Tutorial Contents

- [Tutorial](man/tutorial.md#Tutorial-1)


<a id='Index-1'></a>

## Index

- [`AutoDocs`](lib/functions.md#AutoDocs)
- [`AutoDocs.A`](lib/functions.md#AutoDocs.A)
- [`AutoDocs.B`](lib/functions.md#AutoDocs.B)
- [`AutoDocs.A.K`](lib/functions.md#AutoDocs.A.K)
- [`AutoDocs.B.K`](lib/functions.md#AutoDocs.B.K)
- [`AutoDocs.K`](lib/functions.md#AutoDocs.K)
- [`AutoDocs.A.T`](lib/functions.md#AutoDocs.A.T)
- [`AutoDocs.B.T`](lib/functions.md#AutoDocs.B.T)
- [`AutoDocs.Pages.E.T_1`](lib/autodocs.md#AutoDocs.Pages.E.T_1)
- [`AutoDocs.Pages.E.T_2`](lib/autodocs.md#AutoDocs.Pages.E.T_2)
- [`AutoDocs.Pages.T`](lib/functions.md#AutoDocs.Pages.T-Tuple{Any,Any})
- [`AutoDocs.Pages.T`](lib/functions.md#AutoDocs.Pages.T-Tuple{Any})
- [`AutoDocs.Pages.T`](lib/functions.md#AutoDocs.Pages.T)
- [`AutoDocs.T`](lib/functions.md#AutoDocs.T)
- [`Mod.T`](lib/functions.md#Mod.T)
- [`AutoDocs.A.f`](lib/functions.md#AutoDocs.A.f-Tuple{Any})
- [`AutoDocs.B.f`](lib/functions.md#AutoDocs.B.f-Tuple{Any})
- [`AutoDocs.Pages.E.f_1`](lib/autodocs.md#AutoDocs.Pages.E.f_1-Tuple{Any})
- [`AutoDocs.Pages.E.f_2`](lib/autodocs.md#AutoDocs.Pages.E.f_2-Tuple{Any})
- [`AutoDocs.Pages.E.f_3`](lib/autodocs.md#AutoDocs.Pages.E.f_3-Tuple{Any})
- [`AutoDocs.Pages.E.g_1`](lib/autodocs.md#AutoDocs.Pages.E.g_1-Tuple{Any})
- [`AutoDocs.Pages.E.g_2`](lib/autodocs.md#AutoDocs.Pages.E.g_2-Tuple{Any})
- [`AutoDocs.Pages.E.g_3`](lib/autodocs.md#AutoDocs.Pages.E.g_3-Tuple{Any})
- [`AutoDocs.Pages.f`](lib/functions.md#AutoDocs.Pages.f-Tuple{Any})
- [`AutoDocs.Pages.f`](lib/functions.md#AutoDocs.Pages.f-Tuple{Any,Any})
- [`AutoDocs.Pages.f`](lib/functions.md#AutoDocs.Pages.f-Tuple{Any,Any,Any})
- [`AutoDocs.f`](lib/functions.md#AutoDocs.f-Tuple{Any})
- [`Documenter.hide`](hidden/index.md#Documenter.hide)
- [`Mod.func`](lib/functions.md#Mod.func-Tuple{Any})
- [`AutoDocs.@m`](lib/functions.md#AutoDocs.@m-Tuple{})
- [`AutoDocs.A.@m`](lib/functions.md#AutoDocs.A.@m-Tuple{})
- [`AutoDocs.B.@m`](lib/functions.md#AutoDocs.B.@m-Tuple{})
- [`Base.@assert`](lib/functions.md#Base.@assert)
- [`Base.@time`](lib/functions.md#Base.@time)


<a id='Embedded-@ref-links-headers:-[ccall](@ref)-1'></a>

### Embedded `@ref` links headers: [`ccall`](lib/functions.md#ccall)


[#60](https://github.com/JuliaDocs/Documenter.jl/issues/60) [#61](https://github.com/JuliaDocs/Documenter.jl/issues/61)


```julia
julia> zeros(5, 5)
5×5 Array{Float64,2}:
 0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0

julia> zeros(50, 50)
50×50 Array{Float64,2}:
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  …  0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  …  0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 ⋮                        ⋮              ⋱            ⋮
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  …  0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
 0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0     0.0  0.0  0.0  0.0  0.0  0.0  0.0
```




```jldoctest
julia> [1.0, 2.0, 3.0]
3-element Array{Float64,1}:
 1.0
 2.0
 3.0

```


```jldoctest
julia> println(" "^5)

julia> "\nfoo\n\nbar\n\n\nbaz"
"\nfoo\n\nbar\n\n\nbaz"

julia> println(ans)

foo

bar


baz
```


```jldoctest
julia> info("...")
INFO: ...

```


  * `one` two three
  * four `five` six
  * ```
    one
    ```


<a id='Raw-Blocks-1'></a>

## Raw Blocks


<center class="raw-html-block">
    <strong>CENTER</strong>
</center>


<a id='Symbols-in-doctests-1'></a>

# Symbols in doctests


```jldoctest
julia> a = :undefined
:undefined

julia> a
:undefined
```


<a id='Named-doctests-1'></a>

# Named doctests


```jldoctest test-one
julia> a = 1
1
```


```jldoctest test-one
julia> a + 1
2
```


<a id='Sanitise-module-names-1'></a>

# Sanitise module names


```jldoctest
julia> type T end

julia> t = T()
T()

julia> fullname(current_module())
()

julia> fullname(Base.Pkg)
(:Base,:Pkg)

julia> current_module()
Main
```


<a id='Issue398-1'></a>

# Issue398




```jldoctest
julia> @define_show_and_make_object q "abcd"
abcd
```


<a id='Issue418-1'></a>

# Issue418


```jldoctest
julia> f(x::Float64) = x
f (generic function with 1 method)

julia> f("")
ERROR: MethodError: no method matching f(::String)
Closest candidates are:
  f(!Matched::Float64) at none:1
```


```jldoctest
julia> a = 1
1

julia> b = 2
2

julia> ex = :(a + b)
:(a + b)

julia> eval(ex)
3
```


```jldoctest
julia> a = 1
1

julia> ans
1
```


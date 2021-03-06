```@meta
CurrentModule = BlockArrays
```

# Public Documentation

Documentation for `BlockArrays.jl`'s public interface.

See [Internal Documentation](@ref) for internal package docs covering all submodules.


## Contents

```@contents
Pages = ["public.md"]
```

## Index

```@index
Pages = ["public.md"]
```

## AbstractBlockArray interface

This sections defines the functions a subtype of `AbstractBlockArray` should define to be a part of the `AbstractBlockArray` interface. An `AbstractBlockArray{T, N}` is a subtype of `AbstractArray{T,N}` and should therefore also fulfill the [`AbstractArray` interface](http://docs.julialang.org/en/latest/manual/interfaces/#abstract-arrays).

```@docs
AbstractBlockArray
BlockBoundsError
Block
BlockIndex
nblocks
blocksize
getblock
getblock!
setblock!
Array
blockcheckbounds
```

## BlockArray

```@docs
BlockArray
```


## PseudoBlockArray

```@docs
PseudoBlockArray
```

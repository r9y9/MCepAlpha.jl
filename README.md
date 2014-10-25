# MCepAlpha

[![Build Status](https://travis-ci.org/r9y9/MCepAlpha.jl.svg?branch=master)](https://travis-ci.org/r9y9/MCepAlpha.jl)

This is a julia translation of [mcep_alpha_calc](https://bitbucket.org/happyalu/mcep_alpha_calc).

## Usage

```julia
using MCepAlpha
fs = 16000
alpha = mcepalpha(fs)

println(alpha) # 0.41
```

## Installation

```julia
Pkg.clone("https://github.com/r9y9/MCepAlpha.jl")
```

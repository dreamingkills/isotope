# Isotope

![CI Status](https://github.com/Phiriq/isotope/actions/workflows/ci.yml/badge.svg)
![Coverage Status](https://coveralls.io/repos/Phiriq/isotope/badge.svg?branch=master)

Isotope is a library that provides Elixir bindings to the [bracket-noise](https://crates.io/crates/bracket-noise) crate, which is a rust port of [FastNoise Lite](https://github.com/Auburn/FastNoiseLite).

## Installation

The package can be installed by adding `isotope` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:isotope, "~> 0.2.0"}
  ]
end
```
And running `mix deps.get, deps.compile`.

## Usage
Check the documentation [here](https://hexdocs.pm/isotope)

## Examples
You can check and run the examples in the `examples` folder.
```bash
mix run examples/<example>.exs
```

## Images
![Output of the terrain.exs example script](images/terrain.png)
![Output of the visualization.exs example script](images/visualization.png)


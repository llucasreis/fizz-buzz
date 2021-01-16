# FizzBuzz

A simple FizzBuzz application created in Elixir.

It receives an .txt input and return a new list replacing any number divisible
by three with the word `fizz`, any number divisible by five with the word `buzz`
and any number divisible by both with the word `fizz-buzz`

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `fizz_buzz` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:fizz_buzz, "~> 0.1.0"}
  ]
end
```

## Usage
Run this command to open iterative shell:
```
iex -S mix
```

And run the following command:
```
FizzBuzz.build("numbers.txt")
```
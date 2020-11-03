# Koans

A koan are essentially a simple problem where programmer is asked to “fill in the blanks”.

Often, you are presented with tests and you have to edit the code and sometimes write it all so to get all tests to pass.

[Edgecase Ruby Koans](http://rubykoans.com/) were possibly the first ones to introduce the concept.

There is a number of koans ready to be pulled from internet, for pretty much any language.

#### How to write your own

```julia
#!/usr/bin/julia
using Base.Test
x= _
y= _

@testset "Variables Tests" begin
          @test x == 4+4
          @test "Hello, World"=="H$(y)ld"
end
```

### Examples

> Run a search for your favorite language and add Koans to your query

[julia-koans](https://github.com/BlankRain/julia-koans) {julia}

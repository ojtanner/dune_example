# Example Dune Set-up for OCaml Project

Generate new project diretory with Dune:

```shell
dune init proj dune_example
```

Add libraries of your own, reusable code in files inside the ``` dune_example/lib ``` directory.
In this case, ```addition``` and ```substraction```.

These Modules will be available via ```<Name of Library>.UppercaseNameOfFile```.
In this case, ```Dune_example.Addition```.

You may need to execute
```shell
dune build
```
to generate the necesary ```.merlin``` files needed for autocomplete.

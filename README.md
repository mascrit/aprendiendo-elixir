# aprendiendo-elixir

## Simple funcionamiento de una Funcion

```elixir
#!/usr/bin/elixir
#-*- coding: uft-8 -*-

defmodule Hello do
  def sample do
    IO.puts 'Hello!'
  end
end

Hello.sample
```

para ejecutar:

```sh
> elixir hola_mundo.exs
```

Los Archivos *ex* estan destinados para compilación y los archivos *exs para **scripting**.

[Documentación de Elixir](https://hexdocs.pm/elixir/master/Kernel.html)

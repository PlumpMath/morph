# Morph

Morph is a library of Haskell-style morphisms: monoids, functors, and monads.
These constructs are helpful for designing programs that are purely functional
and that encapsulate the boilerplate employed by many programming techniques.

## Features

* Implementation based on Protocols and Types.
* Predefined monoids for common tasks.
* Protocol Functor extended for Clojure concrete types.
* Monads: Identity, Maybe, Either, Reader, Writer, State.
* Library of generic functions for monads.
* Monad Transformers: MaybeT, EitherT, ReaderT, WriterT, StateT.
* Support for curried functions.
* Sample monads in `src/main/resources`.

## Setup

Leiningen:

```clojure
[org.blancas/morph "0.1.0"]
```

Maven:

```xml
<dependency>
  <groupId>org.blancas</groupId>
  <artifactId>morph</artifactId>
  <version>0.1.0</version>
</dependency>
```

## Documentation

Morph is documented in the [Wiki](https://github.com/blancas/morph/wiki).

To generate the API docs (in the `codox` directory):

    lein doc

## License

Copyright © 2013 Armando Blancas.

Licensed under the [Eclipse Public License](http://www.eclipse.org/legal/epl-v10.html).
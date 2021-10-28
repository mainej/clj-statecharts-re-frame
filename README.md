# com.github.mainej/clj-statecharts-re-frame

An integration between clj-statecharts and re-frame that allows fine-grained
control over the machines and states.

## Usage

FIXME: write usage documentation!

Run the project's tests (they'll fail until you edit them):

    $ clojure -T:build test

Run the project's CI pipeline and build a JAR:

    $ clojure -T:build ci

This will produce an updated `pom.xml` file with synchronized dependencies inside the `META-INF`
directory inside `target/classes` and the JAR in `target`.

Install it locally (requires the `ci` task be run first):

    $ clojure -T:build install

Deploy it to Clojars -- needs `CLOJARS_USERNAME` and `CLOJARS_PASSWORD` environment
variables (requires the `ci` task be run first):

    $ clojure -T:build deploy

The library will be deployed to com.github.mainej/clj-statecharts-re-frame on clojars.org.

## License

Copyright © 2021 Jmaine

Distributed under the Eclipse Public License version 1.0.

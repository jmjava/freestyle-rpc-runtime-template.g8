## Note: this is based on https://github.com/frees-io/freestyle-template.g8
This is a Giter8 template for Freestyle RPC Runtime projects.

## Creating New Freestyle RPC Runtime Project

1. Create a new project from Freestyle g8 template:

```scala
sbt new jmjava/freestyle-rpc-runtime-template.g8
```

2. Fill the required information (you can see an example below):

```bash

...

name [Project Name]: freestyle-rpc
projectDescription [Project Description]: RPC with Freestyle
project [project-name]: freestyle-rpc
package [freestyle]:
Skipping existing file: ./freestyle-rpc/.gitignore
Skipping existing file: ./freestyle-rpc/.scalafmt.conf

Template applied in ./freestyle-rpc
```


## Debugging this template

In the case you need to change this plugin, the easiest way to test it locally is:

```
sbt new file:///the/path/to/freestyle-rpc-runtime-template.g8
```



Template license
----------------
Written in 2018 by John Menke

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

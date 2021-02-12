Recreate unix programs
======================

```
$ ./my-cat f1 f2 f3
$ ./my-grep < infile pattern
$ ./my-cp from-file to-file
$ ./my-mv from-file to-file
$ ./my-ls dir
$ ./my-env
$ ./mkdir dirname
$ ./mkdir -p path/to/some/dir # skip for now b/c requires recursion
$ ./touch filename
```

Cheatsheet
----------

shebang:

```ruby
#!/usr/bin/env ruby
```

making executable:

```sh
$ chmod +x filename
```

Ruby stuffs:

```ruby
ARGV
File.read("filename")
File.write("filename", "body")
lines.select { |line| line.match? /pattern/ } # or line.include? "something"
File.write("filename", "body")
Dir["*"] # takes a "glob pattern", the "*" is a wildcard
ENV
```

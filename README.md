# Dummy Ruby app that has a Thorfile

This project represents an example app where you have identified a pattern that you want all your developer friends to adhere to.

In this example app there is pattern we want to be maintained. There are things that have `lib/thing.rb` and `spec/thing_spec.rb`:

```
\
 lib
 |\
 | foo.rb
 spec
  \
   foo_spec.rb
```

To create new things:

```
$ thor :thing bigthing
       exist  
      create  lib/bigthing.rb
      create  spec/bigthing_spec.rb
```
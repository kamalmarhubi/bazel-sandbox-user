Output
------

    $ bazel build :userinfo
    INFO: Found 1 target...
    Target //:userinfo up-to-date:
      bazel-genfiles/userinfo
    INFO: Elapsed time: 1.856s, Critical Path: 0.07s
    $ cat bazel-genfiles/userinfo 
    65534:65534

# Binary FIFO Gateway example

This is an Maxeler DFE networking example project.

## Running

Open the bitstream Java Project.

Open `FIFOGatewayManager.maxj` and execute the `main()` function.

```
$ source config.sh
$ cd runtime
$ cp <path-to-new-max-file> .
$ ./build.py
<...>
$ ./run.py
<...>
```

In a separate terminal window, run the following:

```
$ cd ..
$ source config.sh
$ cd sender
$ ./build.py
$ ./sender
```

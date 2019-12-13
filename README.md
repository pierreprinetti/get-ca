# get-ca

Prints the last certificate in the trust chain sent by an HTTPS server. This usually corresponds to the Certificate Authority that signed the TLS key.

# Use

```shell
./get-ca [-p target_port] target_host
```

* `-p` Specify the port to connect to. Defaults to 443.
* `-h` Print this help

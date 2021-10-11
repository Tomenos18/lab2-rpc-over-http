## lab2-rpc-over-http

Instructions to check, build and execute the server:

* Check the server:

```bash
./gradlew :server:check
```

* Build the server:

```bash
  ./gradlew :server:build
```

* Execute the server:

```bash
  ./gradlew :server:bootRun
```


Instructions to check, build and execute the client:

* Check the client:

```bash
./gradlew :client:check
```

* Build the client:

```bash
  ./gradlew :client:build
```

* Execute the client:

```bash
  ./gradlew :client:bootRun
```

To execute correctly the system, it was needed to implementate the function *translation()* in *Server.kt* file.

After execute the system, we can see in the client the following line:

```bash
Result of translating [Translate me!] is [traduccion]
```
# Demo Client Java
Java Springboot Demo App for testing [SafeDep Gateway](https://github.com/safedep/gateway)

## Usage

* Setup [gateway](https://github.com/safedep/gateway)
* Run build

```bash
./gradlew build --refresh-dependencies
```

To use gateway with demo authentication credentials

```bash
USE_GATEWAY_AUTH=true ./gradlew build --refresh-dependencies
```

## References

* https://safedep.io
* https://github.com/safedep/gateway

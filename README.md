# Demo Client Java
Java Springboot Demo App

## Usage

Build the application

```bash
./gradlew build --refresh-dependencies
```

Run the application

```bash
./gradlew bootRun
```

Generate CycloneDX SBOM

```bash
./gradlew cyclonedxBom
```

> Note: The generate SBOM will be placed in `build/reports/bom.json`

## References

* https://safedep.io
* https://github.com/safedep/gateway

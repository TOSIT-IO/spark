# Spark-3.5.3

## Make a release

```sh
./dev/make-distribution.sh --name tdp --tgz -Phive -Phive-thriftserver -Pyarn
```

The command generates a `.tar.gz` file of the release at `spark-3.5.3-0.0.tgz`.

The command does not install the jar files in .m2. To install the jar files use the command:

```sh
./build/mvn -Phive -Phive-thriftserver -Pyarn -DskipTests clean install
```

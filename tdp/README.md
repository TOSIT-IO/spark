# Spark-3.5.8-SNAPSHOT-dgfip-xss

## Version

This release is based on [apache spark branch-3.5](https://github.com/apache/spark/tree/branch-3.5) at commit `65c3d1cb18c45528d8090ac905d87a8dcd779aa7`.

## Make a release

```sh
./dev/make-distribution.sh --name tdp --tgz -Phive -Phive-thriftserver -Pyarn -Psparkr
```

The command generates a `.tar.gz` file of the release at `spark-3.5.8-SNAPSHOT-dgfip-xss.tgz`.

The command does not install the jar files in .m2. To install the jar files use the command:

```sh
./build/mvn -Phive -Phive-thriftserver -Pyarn -Psparkr -DskipTests clean install
```

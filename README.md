# Flink(1.10.0+)  SQL Client Hive Support 

## Usage

    mvn clean package

copy the `target/io.github.mrzhangboss-1.0-SNAPSHOT-hive2_3_4.jar` to your flink lib dir (like `/opt/flink/lib`) or copy a release version compare with your hive.
It test ok in  `hive-2.3.4` + `hadoop-2.7.2`

PS: If you use high hadoop version, you may meet `java.lang.NoClassDefFoundError`, try copy`$HIVE_HOME/lib/javax.jdo-3.2.0-m3.jar` and `$HIVE_HOME/lib/datanucleus-*` to flink lib .

**For More Version**:

- hive 1.0.0 : `mvn clean package -P1.0.0`
- hive 1.1.0 : `mvn clean package -P1.1.0`
- hive 1.2.1 : `mvn clean package -P1.2.1`
- hive 2.0.0 : `mvn clean package -P2.0.0`
- hive 2.1.0 : `mvn clean package -P2.1.0`
- hive 2.2.0 : `mvn clean package -P2.2.0`
- hive 3.1.0 : `mvn clean package -P3.1.0`


# javacpp

mvn clean install -U


@gre785 ➜ /workspaces/javacpp (main) $ mvn clean install -U
[INFO] Scanning for projects...
[INFO] 
[INFO] --------------------------< com.example:demo >--------------------------
[INFO] Building  0.0.1-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- clean:3.5.0:clean (default-clean) @ demo ---
[INFO] Deleting /workspaces/javacpp/target
[INFO] 
[INFO] --- resources:3.5.0:resources (default-resources) @ demo ---
[INFO] Copying 1 resource from src/main/resources to target/classes
[INFO] Copying 0 resource from src/main/resources to target/classes
[INFO] 
[INFO] --- compiler:3.15.0:compile (default-compile) @ demo ---
[INFO] Recompiling the module because of changed source code.
[INFO] Compiling 1 source file with javac [debug parameters release 17] to target/classes
[INFO] 
[INFO] --- resources:3.5.0:testResources (default-testResources) @ demo ---
[INFO] skip non existing resourceDirectory /workspaces/javacpp/src/test/resources
[INFO] 
[INFO] --- compiler:3.15.0:testCompile (default-testCompile) @ demo ---
[INFO] No sources to compile
[INFO] 
[INFO] --- surefire:3.5.6:test (default-test) @ demo ---
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.6/surefire-api-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.6/surefire-api-3.5.6.pom (3.7 kB at 6.7 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.6/surefire-logger-api-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.6/surefire-logger-api-3.5.6.pom (3.5 kB at 92 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.6/surefire-shared-utils-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.6/surefire-shared-utils-3.5.6.pom (4.0 kB at 107 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.6/surefire-extensions-api-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.6/surefire-extensions-api-3.5.6.pom (3.6 kB at 89 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.6/maven-surefire-common-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.6/maven-surefire-common-3.5.6.pom (7.3 kB at 186 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.6/surefire-booter-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.6/surefire-booter-3.5.6.pom (5.1 kB at 155 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.6/surefire-extensions-spi-3.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.6/surefire-extensions-spi-3.5.6.pom (1.7 kB at 44 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.pom (2.8 kB at 70 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.4.1/maven-resolver-1.4.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.4.1/maven-resolver-1.4.1.pom (18 kB at 535 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom (44 kB at 1.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom (17 kB at 552 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.pom (2.6 kB at 88 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.pom (5.4 kB at 185 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/42/maven-shared-components-42.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/42/maven-shared-components-42.pom (3.8 kB at 118 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/42/maven-parent-42.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/42/maven-parent-42.pom (50 kB at 1.7 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/32/apache-32.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/32/apache-32.pom (24 kB at 733 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.6/surefire-api-3.5.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.6/surefire-api-3.5.6.jar (174 kB at 1.9 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.6/surefire-logger-api-3.5.6.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.6/surefire-shared-utils-3.5.6.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.6/surefire-extensions-api-3.5.6.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.6/surefire-booter-3.5.6.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.6/maven-surefire-common-3.5.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.6/surefire-logger-api-3.5.6.jar (14 kB at 266 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.6/surefire-extensions-spi-3.5.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.6/surefire-extensions-spi-3.5.6.jar (8.2 kB at 109 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.6/surefire-extensions-api-3.5.6.jar (26 kB at 194 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.6/surefire-booter-3.5.6.jar (123 kB at 346 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.jar (149 kB at 446 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.6/maven-surefire-common-3.5.6.jar (317 kB at 843 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.jar (58 kB at 168 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.jar (168 kB at 435 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.6/surefire-shared-utils-3.5.6.jar (3.0 MB at 5.2 MB/s)
[INFO] No tests to run.
[INFO] 
[INFO] --- jar:3.5.1:jar (default-jar) @ demo ---
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.2.0/file-management-3.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.2.0/file-management-3.2.0.pom (4.5 kB at 67 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/44/maven-shared-components-44.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/44/maven-shared-components-44.pom (3.8 kB at 131 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.3/plexus-utils-4.0.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.3/plexus-utils-4.0.3.pom (6.8 kB at 212 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.19.0/commons-io-2.19.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.19.0/commons-io-2.19.0.pom (21 kB at 666 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/81/commons-parent-81.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/81/commons-parent-81.pom (78 kB at 1.9 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.4/junit-bom-5.11.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.4/junit-bom-5.11.4.pom (5.6 kB at 226 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.6/maven-archiver-3.6.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.6/maven-archiver-3.6.6.pom (5.2 kB at 208 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/45/maven-shared-components-45.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/45/maven-shared-components-45.pom (3.8 kB at 152 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/45/maven-parent-45.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/45/maven-parent-45.pom (53 kB at 1.6 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.13.1/junit-bom-5.13.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.13.1/junit-bom-5.13.1.pom (5.6 kB at 217 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.10.4/plexus-archiver-4.10.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.10.4/plexus-archiver-4.10.4.pom (5.6 kB at 166 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.6.0/plexus-io-3.6.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.6.0/plexus-io-3.6.0.pom (3.5 kB at 103 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.20.0/commons-io-2.20.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.20.0/commons-io-2.20.0.pom (20 kB at 569 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/85/commons-parent-85.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/85/commons-parent-85.pom (78 kB at 2.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.28.0/commons-compress-1.28.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.28.0/commons-compress-1.28.0.pom (25 kB at 937 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.19.0/commons-codec-1.19.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.19.0/commons-codec-1.19.0.pom (18 kB at 177 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.18.0/commons-lang3-3.18.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.18.0/commons-lang3-3.18.0.pom (32 kB at 1.0 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/airlift/aircompressor/0.27/aircompressor-0.27.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/airlift/aircompressor/0.27/aircompressor-0.27.pom (5.8 kB at 134 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/airlift/airbase/112/airbase-112.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/airlift/airbase/112/airbase-112.pom (69 kB at 1.8 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.8.0-M1/junit-bom-5.8.0-M1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.8.0-M1/junit-bom-5.8.0-M1.pom (5.7 kB at 227 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.10/xz-1.10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.10/xz-1.10.pom (1.9 kB at 67 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-6/zstd-jni-1.5.7-6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-6/zstd-jni-1.5.7-6.pom (2.0 kB at 54 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.12.0/plexus-archiver-4.12.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.12.0/plexus-archiver-4.12.0.pom (5.6 kB at 182 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.22.0/commons-io-2.22.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.22.0/commons-io-2.22.0.pom (20 kB at 596 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/98/commons-parent-98.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/98/commons-parent-98.pom (80 kB at 2.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.12/xz-1.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.12/xz-1.12.pom (1.9 kB at 48 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-9/zstd-jni-1.5.7-9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-9/zstd-jni-1.5.7-9.pom (2.0 kB at 77 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.2.0/file-management-3.2.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.2.0/file-management-3.2.0.jar (26 kB at 960 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.3/plexus-utils-4.0.3.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.6/maven-archiver-3.6.6.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.12.0/plexus-archiver-4.12.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.6.0/plexus-io-3.6.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.28.0/commons-compress-1.28.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.3/plexus-utils-4.0.3.jar (193 kB at 6.2 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.19.0/commons-codec-1.19.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.6/maven-archiver-3.6.6.jar (28 kB at 644 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.18.0/commons-lang3-3.18.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.12.0/plexus-archiver-4.12.0.jar (227 kB at 4.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.12/xz-1.12.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.6.0/plexus-io-3.6.0.jar (80 kB at 1.4 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-9/zstd-jni-1.5.7-9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.19.0/commons-codec-1.19.0.jar (375 kB at 4.0 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.22.0/commons-io-2.22.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.12/xz-1.12.jar (169 kB at 1.1 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.18.0/commons-lang3-3.18.0.jar (703 kB at 3.5 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.28.0/commons-compress-1.28.0.jar (1.1 MB at 5.5 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.22.0/commons-io-2.22.0.jar (609 kB at 2.6 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.7-9/zstd-jni-1.5.7-9.jar (7.6 MB at 13 MB/s)
[INFO] Building jar: /workspaces/javacpp/target/demo-0.0.1-SNAPSHOT.jar
[INFO] 
[INFO] --- spring-boot:4.1.1:repackage (repackage) @ demo ---
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/4.1.1/spring-boot-buildpack-platform-4.1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/4.1.1/spring-boot-buildpack-platform-4.1.1.pom (3.0 kB at 56 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.17.0/jna-platform-5.17.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.17.0/jna-platform-5.17.0.pom (2.3 kB at 64 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.17.0/jna-5.17.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.17.0/jna-5.17.0.pom (2.0 kB at 46 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.27.1/commons-compress-1.27.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.27.1/commons-compress-1.27.1.pom (23 kB at 698 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/72/commons-parent-72.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/72/commons-parent-72.pom (78 kB at 2.8 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.0-M2/junit-bom-5.11.0-M2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.0-M2/junit-bom-5.11.0-M2.pom (5.7 kB at 238 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.1/commons-codec-1.17.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.1/commons-codec-1.17.1.pom (18 kB at 508 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/71/commons-parent-71.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/71/commons-parent-71.pom (78 kB at 2.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.pom (20 kB at 561 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/69/commons-parent-69.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/69/commons-parent-69.pom (77 kB at 2.0 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/31/apache-31.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/31/apache-31.pom (24 kB at 905 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.16.0/commons-lang3-3.16.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.16.0/commons-lang3-3.16.0.pom (31 kB at 1.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.6.4/httpclient5-5.6.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.6.4/httpclient5-5.6.4.pom (6.7 kB at 182 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5-parent/5.6.4/httpclient5-parent-5.6.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5-parent/5.6.4/httpclient5-parent-5.6.4.pom (20 kB at 684 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-parent/14/httpcomponents-parent-14.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-parent/14/httpcomponents-parent-14.pom (30 kB at 1.0 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/27/apache-27.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/27/apache-27.pom (20 kB at 885 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.13.3/junit-bom-5.13.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.13.3/junit-bom-5.13.3.pom (5.7 kB at 189 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/opentelemetry/opentelemetry-bom/1.49.0/opentelemetry-bom-1.49.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/opentelemetry/opentelemetry-bom/1.49.0/opentelemetry-bom-1.49.0.pom (5.9 kB at 189 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.4.3/httpcore5-5.4.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.4.3/httpcore5-5.4.3.pom (3.9 kB at 158 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-parent/5.4.3/httpcore5-parent-5.4.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-parent/5.4.3/httpcore5-parent-5.4.3.pom (15 kB at 550 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.4.3/httpcore5-h2-5.4.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.4.3/httpcore5-h2-5.4.3.pom (3.6 kB at 181 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/7.0.9/spring-core-7.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/7.0.9/spring-core-7.0.9.pom (2.2 kB at 69 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.3.5/commons-logging-1.3.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.3.5/commons-logging-1.3.5.pom (32 kB at 1.0 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.0/jspecify-1.0.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.0/jspecify-1.0.0.pom (1.5 kB at 54 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom (2.8 kB at 97 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom (3.6 kB at 139 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom (4.4 kB at 210 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom (4.3 kB at 153 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-databind/3.1.5/jackson-databind-3.1.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-databind/3.1.5/jackson-databind-3.1.5.pom (18 kB at 563 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/tools/jackson/jackson-base/3.1.5/jackson-base-3.1.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/tools/jackson/jackson-base/3.1.5/jackson-base-3.1.5.pom (16 kB at 575 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.21/jackson-annotations-2.21.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.21/jackson-annotations-2.21.pom (7.4 kB at 284 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-core/3.1.5/jackson-core-3.1.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-core/3.1.5/jackson-core-3.1.5.pom (12 kB at 431 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/4.1.1/spring-boot-loader-tools-4.1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/4.1.1/spring-boot-loader-tools-4.1.1.pom (2.2 kB at 118 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-context/7.0.9/spring-context-7.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-context/7.0.9/spring-context-7.0.9.pom (2.8 kB at 84 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-aop/7.0.9/spring-aop-7.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-aop/7.0.9/spring-aop-7.0.9.pom (2.2 kB at 57 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-beans/7.0.9/spring-beans-7.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-beans/7.0.9/spring-beans-7.0.9.pom (2.0 kB at 63 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-expression/7.0.9/spring-expression-7.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-expression/7.0.9/spring-expression-7.0.9.pom (2.1 kB at 77 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-observation/1.16.7/micrometer-observation-1.16.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-observation/1.16.7/micrometer-observation-1.16.7.pom (4.0 kB at 149 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.1/jspecify-1.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.1/jspecify-1.0.1.pom (1.9 kB at 77 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-commons/1.16.7/micrometer-commons-1.16.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-commons/1.16.7/micrometer-commons-1.16.7.pom (3.8 kB at 147 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.6.0/maven-shade-plugin-3.6.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.6.0/maven-shade-plugin-3.6.0.pom (12 kB at 447 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/42/maven-plugins-42.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/42/maven-plugins-42.pom (7.7 kB at 296 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.5.1/plexus-utils-3.5.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.5.1/plexus-utils-3.5.1.pom (8.8 kB at 399 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/10/plexus-10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/10/plexus-10.pom (25 kB at 1.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.pom (2.4 kB at 91 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.7/asm-commons-9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.7/asm-commons-9.7.pom (2.8 kB at 127 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.7/asm-tree-9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.7/asm-tree-9.7.pom (2.6 kB at 118 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.pom (4.6 kB at 192 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.2/commons-compress-1.26.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.2/commons-compress-1.26.2.pom (23 kB at 882 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.0/commons-codec-1.17.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.0/commons-codec-1.17.0.pom (18 kB at 638 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.pom (31 kB at 702 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/64/commons-parent-64.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/64/commons-parent-64.pom (78 kB at 2.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/30/apache-30.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/30/apache-30.pom (23 kB at 726 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.10.0/junit-bom-5.10.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.10.0/junit-bom-5.10.0.pom (5.6 kB at 202 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.10/jdependency-2.10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.10/jdependency-2.10.pom (14 kB at 540 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/4.1.1/spring-boot-buildpack-platform-4.1.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/4.1.1/spring-boot-buildpack-platform-4.1.1.jar (333 kB at 8.5 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.17.0/jna-platform-5.17.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.17.0/jna-5.17.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.27.1/commons-compress-1.27.1.jar
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.1/commons-codec-1.17.1.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.16.0/commons-lang3-3.16.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.17.1/commons-codec-1.17.1.jar (373 kB at 6.7 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.6.4/httpclient5-5.6.4.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.16.0/commons-lang3-3.16.0.jar (674 kB at 7.6 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.4.3/httpcore5-5.4.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.27.1/commons-compress-1.27.1.jar (1.1 MB at 10 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.4.3/httpcore5-h2-5.4.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.17.0/jna-platform-5.17.0.jar (1.4 MB at 9.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.17.0/jna-5.17.0.jar (2.0 MB at 12 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.4.3/httpcore5-5.4.3.jar (955 kB at 5.9 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar
Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.4.3/httpcore5-h2-5.4.3.jar (264 kB at 1.6 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.6.4/httpclient5-5.6.4.jar (1.1 MB at 6.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-databind/3.1.5/jackson-databind-3.1.5.jar
Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.21/jackson-annotations-2.21.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar (157 kB at 893 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-core/3.1.5/jackson-core-3.1.5.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar (338 kB at 1.7 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/4.1.1/spring-boot-loader-tools-4.1.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.21/jackson-annotations-2.21.jar (82 kB at 377 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/7.0.9/spring-core-7.0.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar (20 kB at 85 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.3.5/commons-logging-1.3.5.jar
Downloaded from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-core/3.1.5/jackson-core-3.1.5.jar (599 kB at 2.5 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.0/jspecify-1.0.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/tools/jackson/core/jackson-databind/3.1.5/jackson-databind-3.1.5.jar (1.9 MB at 7.1 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/4.1.1/spring-boot-loader-tools-4.1.1.jar (342 kB at 1.2 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-context/7.0.9/spring-context-7.0.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.3.5/commons-logging-1.3.5.jar (74 kB at 265 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-aop/7.0.9/spring-aop-7.0.9.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-beans/7.0.9/spring-beans-7.0.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/jspecify/jspecify/1.0.0/jspecify-1.0.0.jar (3.8 kB at 13 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-expression/7.0.9/spring-expression-7.0.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-aop/7.0.9/spring-aop-7.0.9.jar (426 kB at 1.3 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-observation/1.16.7/micrometer-observation-1.16.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/7.0.9/spring-core-7.0.9.jar (2.0 MB at 6.1 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-commons/1.16.7/micrometer-commons-1.16.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-expression/7.0.9/spring-expression-7.0.9.jar (327 kB at 954 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.6.0/maven-shade-plugin-3.6.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-beans/7.0.9/spring-beans-7.0.9.jar (928 kB at 2.7 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.5.1/plexus-utils-3.5.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-commons/1.16.7/micrometer-commons-1.16.7.jar (52 kB at 144 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/io/micrometer/micrometer-observation/1.16.7/micrometer-observation-1.16.7.jar (84 kB at 231 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.7/asm-commons-9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.6.0/maven-shade-plugin-3.6.0.jar (150 kB at 395 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.7/asm-tree-9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-context/7.0.9/spring-context-7.0.9.jar (1.4 MB at 3.6 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.7/asm-commons-9.7.jar (73 kB at 187 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.5.1/plexus-utils-3.5.1.jar (269 kB at 680 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.jar (125 kB at 316 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.10/jdependency-2.10.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.7/asm-tree-9.7.jar (52 kB at 128 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.jar (328 kB at 737 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.10/jdependency-2.10.jar (416 kB at 933 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.jar (509 kB at 1.1 MB/s)
[INFO] Replacing main artifact /workspaces/javacpp/target/demo-0.0.1-SNAPSHOT.jar with repackaged archive, adding nested dependencies in BOOT-INF/.
[INFO] The original artifact has been renamed to /workspaces/javacpp/target/demo-0.0.1-SNAPSHOT.jar.original
[INFO] 
[INFO] --- install:3.1.4:install (default-install) @ demo ---
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.9.22/maven-resolver-util-1.9.22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.9.22/maven-resolver-util-1.9.22.pom (2.2 kB at 77 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.9.22/maven-resolver-1.9.22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.9.22/maven-resolver-1.9.22.pom (23 kB at 758 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.9.22/maven-resolver-api-1.9.22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.9.22/maven-resolver-api-1.9.22.pom (2.2 kB at 58 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.pom (7.8 kB at 373 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/17/plexus-17.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/17/plexus-17.pom (28 kB at 939 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.9.22/maven-resolver-util-1.9.22.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.9.22/maven-resolver-util-1.9.22.jar (196 kB at 7.5 MB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.9.22/maven-resolver-api-1.9.22.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.9.22/maven-resolver-api-1.9.22.jar (157 kB at 5.6 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.jar (193 kB at 3.3 MB/s)
[INFO] Installing /workspaces/javacpp/pom.xml to /home/codespace/.m2/repository/com/example/demo/0.0.1-SNAPSHOT/demo-0.0.1-SNAPSHOT.pom
[INFO] Installing /workspaces/javacpp/target/demo-0.0.1-SNAPSHOT.jar to /home/codespace/.m2/repository/com/example/demo/0.0.1-SNAPSHOT/demo-0.0.1-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  10.220 s
[INFO] Finished at: 2026-09-15T17:05:11Z
[INFO] ------------------------------------------------------------------------
@gre785 ➜ /workspaces/javacpp (main) $ mvn clean install -U
[INFO] Scanning for projects...
[INFO] 
[INFO] --------------------------< com.example:demo >--------------------------
[INFO] Building  0.0.1-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- clean:3.5.0:clean (default-clean) @ demo ---
[INFO] Deleting /workspaces/javacpp/target
[INFO] 
[INFO] --- resources:3.5.0:resources (default-resources) @ demo ---
[INFO] Copying 1 resource from src/main/resources to target/classes
[INFO] Copying 0 resource from src/main/resources to target/classes
[INFO] 
[INFO] --- compiler:3.15.0:compile (default-compile) @ demo ---
[INFO] Recompiling the module because of changed source code.
[INFO] Compiling 1 source file with javac [debug parameters release 17] to target/classes
[INFO] -------------------------------------------------------------
[ERROR] COMPILATION ERROR : 
[INFO] -------------------------------------------------------------
[ERROR] /workspaces/javacpp/src/main/java/com/example/demo/DemoApplication.java:[3,27] package org.bytedeco.javacv does not exist
[ERROR] /workspaces/javacpp/src/main/java/com/example/demo/DemoApplication.java:[7,1] cannot find symbol
  symbol:   class FFmpegFrameRecorder
  location: class com.example.demo.DemoApplication
[INFO] 2 errors 
[INFO] -------------------------------------------------------------
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  2.307 s
[INFO] Finished at: 2026-09-15T17:06:22Z
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.15.0:compile (default-compile) on project demo: Compilation failure: Compilation failure: 
[ERROR] /workspaces/javacpp/src/main/java/com/example/demo/DemoApplication.java:[3,27] package org.bytedeco.javacv does not exist
[ERROR] /workspaces/javacpp/src/main/java/com/example/demo/DemoApplication.java:[7,1] cannot find symbol
[ERROR]   symbol:   class FFmpegFrameRecorder
[ERROR]   location: class com.example.demo.DemoApplication
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException
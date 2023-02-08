Run Sonatype Sonatype Nexus Repository Manager on AARCH64 and AMD64 hardware.

## Java used

- AARCH64: eclipse-temurin:8-jre-jammy
- AMD64: sycured/graalvm-8:jdk

## Running

```bash
docker run -d -p 8081:8081 --name nexus sycured/nexus
```

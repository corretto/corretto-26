# Change Log for Amazon Corretto 26

The following sections describe the changes for each release of Amazon Corretto 26.

## Corretto version: 26.0.2.11.1
Release Date: August 18, 2026
 
**Target Platforms**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64
 
The following issues above are addressed in 26.0.2.11.1

| Issue Name | Platform | Description | Link |
|------------|----------|-------------|------|
| Import jdk-26.0.2.1+1 | All | Updates Corretto baseline to OpenJDK 26.0.2.1+1 | [jdk-26.0.2.1+1](https://github.com/openjdk/jdk26u/releases/tag/jdk-26.0.2.1+1) |
| JDK-8385390 | All | Update FreeType to 2.14.3 | [d195210](https://github.com/corretto/corretto-25/commit/d195210aef1f2c66e916f7098c3f998cd29614d8) |

The following CVEs are addressed in 26.0.2.11.1

| CVE | CVSS | Component |
|-----|------|-----------|
| CVE-2026-70906 | 7.5 | client-libs/2d |
| CVE-2026-61308 | 6.8 | core-libs/java.net |
| CVE-2026-70907 | 5.3 | security-libs/javax.net.ssl |
| CVE-2026-60589 | 3.7 | security-libs/javax.xml.crypto |

## Corretto version: 26.0.2.10.1
Release Date: July 21, 2026
 
**Target Platforms**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64
 
The following issues above are addressed in 26.0.2.10.1

| Issue Name | Platform | Description | Link |
|------------|----------|-------------|------|
| Import jdk-26.0.2+10 | All | Updates Corretto baseline to OpenJDK 26.0.2+10 | [jdk-26.0.2+10](https://github.com/openjdk/jdk26u/releases/tag/jdk-26.0.2+10) |
| JDK-8386085 | All | Livelock in AbstractQueuedSyncronizer.cleanQueue() when multiple threads do tryAcquire() with a short timeout and no permits available | [#29](https://github.com/corretto/corretto-26/pull/29) |
| Recommend instead of Require dependencies for AL2023 headless | AL2023 | Improve dependencies for AL2023+ headless | [#21](https://github.com/corretto/corretto-26/pull/21) |



The following CVEs are addressed in 26.0.2.10.1

| CVE | CVSS | Component |
|-----|------|-----------|
| CVE-2026-41254 | 7.5 | client-libs/2d |
| CVE-2026-47063 | 7.5 | security-libs/java.security |
| CVE-2026-60147 | 6.5 | security-libs/java.security |
| CVE-2026-46968 | 5.9 | security-libs/javax.net.ssl |
| CVE-2026-47027 | 5.3 | security-libs/java.security |
| CVE-2026-47021 | 5.3 | client-libs/2d |
| CVE-2026-46917 | 5.3 | security-libs/javax.net.ssl |
| CVE-2026-47059 | 3.7 | client-libs/2d |
| CVE-2026-47010 | 3.7 | client-libs/javax.imageio |

## Corretto version: 26.0.1.8.1
Release Date: April 21, 2026

**Target Platforms**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macOS 14.0 and later, x86_64
+ macOS 14.0 and later, aarch64

The following issues are addressed in 26.0.1.8.1

| Issue Name | Platform | Description | Link |
|------------|----------|-------------|------|
| Import jdk-26.0.1+8 | All | Updates Corretto baseline to OpenJDK 26.0.1+8 | [jdk-26.0.1+8](https://github.com/openjdk/jdk26u/releases/tag/jdk-26.0.1+8) |
| JDK-8381670 | All | Revert the changes to GZIPInputStream related to InputStream.available() usage | [#18](https://github.com/corretto/corretto-26/pull/18) |

The following CVEs are addressed in 26.0.1.8.1

| CVE | CVSS | Component |
|-----|------|-----------|
| CVE-2026-22016 | 7.5 | xml/jaxp |
| CVE-2026-34282 | 7.5 | core-libs/java.net |
| CVE-2026-22021 | 5.3 | security-libs/java.security |
| CVE-2026-22013 | 5.3 | security-libs/org.ietf.jgss |
| CVE-2026-23865 | 5.3 | client-libs/2d |
| CVE-2026-22008 | 3.7 | core-libs/java.lang |
| CVE-2026-22018 | 3.7 | core-libs/java.util |
| CVE-2026-22007 | 2.9 | security-libs/java.security |
| CVE-2026-34268 | 2.9 | security-libs/java.security |

## Corretto version: 26.0.0.35.2
Release Date: March 17, 2026

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macOS 14.0 and later, x86_64
+ macOS 14.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 26.0.0.35.2:

| Issue Name       | Platform | Description                                | Link                                                               |
|------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
| Import jdk-26+35 | All      | Updates Corretto baseline to OpenJDK 26+35 | [jdk-26+35](https://github.com/openjdk/jdk/releases/tag/jdk-26+35) |

## Corretto version: 26.0.0.34.1
Release Date: February 5, 2026

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 11 or later, x86_64
+ macOS 14.0 and later, x86_64
+ macOS 14.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 26.0.0.34.1:

| Issue Name       | Platform | Description                                | Link                                                               |
|------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
| Import jdk-26+34 | All      | Updates Corretto baseline to OpenJDK 26+34 | [jdk-26+34](https://github.com/openjdk/jdk/releases/tag/jdk-26+34) |

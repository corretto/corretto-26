# Change Log for Amazon Corretto 26

The following sections describe the changes for each release of Amazon Corretto 26.

## Corretto version: 26.0.1.8.1
Release Date: April 21, 2026

**Target Platforms**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64

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
| CVE-2026-22020 | 7.1 | hotspot/compiler |
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
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64


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
+ macos 14.0 and later, x86_64
+ macos 14.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 26.0.0.34.1:

| Issue Name       | Platform | Description                                | Link                                                               |
|------------------|----------|--------------------------------------------|--------------------------------------------------------------------|
| Import jdk-26+34 | All      | Updates Corretto baseline to OpenJDK 26+34 | [jdk-26+34](https://github.com/openjdk/jdk/releases/tag/jdk-26+34) |

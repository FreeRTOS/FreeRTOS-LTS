## Overview
FreeRTOS offers feature stability with long term support (LTS) releases. FreeRTOS LTS libraries come with security updates and critical bug fixes to the FreeRTOS kernel and IoT libraries listed below for two years, and are maintained by AWS for the benefit of the FreeRTOS community. With FreeRTOS LTS, you get a complete set of libraries needed to build secure connected IoT and embedded products. Long term support helps reduce maintenance and testing costs associated with updating libraries on your devices already in production.

AWS also offers FreeRTOS Extended Maintenance Plan (EMP) that provides you with security patches and critical bug fixes on your chosen FreeRTOS LTS version for up to an additional 10 years. With FreeRTOS EMP, your FreeRTOS-based long-lived devices can rely on a version that has feature stability and receives security updates for years. You receive timely notification of upcoming patches on FreeRTOS libraries, so you can plan the deployment of security patches on your IoT devices. To learn more about FreeRTOS EMP, see the [FreeRTOS Features page](https://aws.amazon.com/freertos/features/).

## FreeRTOS/FreeRTOS Long Term Support

Libraries in this GitHub branch (also listed below) are part of the FreeRTOS 202604-LTS release. Learn more at https://freertos.org/lts-libraries.html.

| Library                     | Version             | LTS Until  | LTS Repo URL                                                                    |
|-------------------------    |---------------------|------------|-------------------------------------------------------------------------------  |
| FreeRTOS Kernel             | 11.3.0              | 04/30/2028 | https://github.com/FreeRTOS/FreeRTOS-Kernel/tree/V11.3.0                        |
| FreeRTOS-Plus-TCP           | 4.4.1               | 04/30/2028 | https://github.com/FreeRTOS/FreeRTOS-Plus-TCP/tree/V4.4.1                       |
| coreMQTT                    | 5.0.2               | 04/30/2028 | https://github.com/FreeRTOS/coreMQTT/tree/v5.0.2                                |
| coreHTTP                    | 3.1.3               | 04/30/2028 | https://github.com/FreeRTOS/coreHTTP/tree/v3.1.3                                |
| corePKCS11                  | 3.6.4               | 04/30/2028 | https://github.com/FreeRTOS/corePKCS11/tree/v3.6.4                              |
| coreJSON                    | 3.3.1               | 04/30/2028 | https://github.com/FreeRTOS/coreJSON/tree/v3.3.1                                |
| coreSNTP                    | 2.0.0               | 04/30/2028 | https://github.com/FreeRTOS/coreSNTP/tree/v2.0.0                                |
| Cellular Interface          | 1.4.2               | 04/30/2028 | https://github.com/FreeRTOS/FreeRTOS-Cellular-Interface/tree/v1.4.2             |
| backoffAlgorithm            | 1.4.2               | 04/30/2028 | https://github.com/FreeRTOS/backoffAlgorithm/tree/v1.4.2                        |
| SigV4                       | 1.3.1               | 04/30/2028 | https://github.com/aws/SigV4-for-AWS-IoT-embedded-sdk/tree/v1.3.1               |
| AWS IoT Device Shadow       | 1.4.2               | 04/30/2028 | https://github.com/aws/Device-Shadow-for-AWS-IoT-embedded-sdk/tree/v1.4.2       |
| AWS IoT Device Defender     | 1.4.1               | 04/30/2028 | https://github.com/aws/Device-Defender-for-AWS-IoT-embedded-sdk/tree/v1.4.1     |
| AWS IoT Jobs                | 2.0.1               | 04/30/2028 | https://github.com/aws/Jobs-for-AWS-IoT-embedded-sdk/tree/v2.0.1                |
| AWS IoT Fleet Provisioning  | 1.2.2               | 04/30/2028 | https://github.com/aws/Fleet-Provisioning-for-AWS-IoT-embedded-sdk/tree/v1.2.2  |
| AWS IoT MQTT File Streams   | 1.2.0               | 04/30/2028 | https://github.com/aws/aws-iot-core-mqtt-file-streams-embedded-c/tree/v1.2.0    |

## Upgrading to FreeRTOS 202604-LTS from a previous version of FreeRTOS LTS

FreeRTOS 202604 LTS libraries are backward compatible with 202406.xx LTS, except
coreMQTT, coreSNTP, and AWS IoT Jobs libraries which have had major version updates.
For coreMQTT, refer to the [coreMQTT migration guide](https://github.com/FreeRTOS/coreMQTT/blob/v5.0.2/MigrationGuide.md) for upgrading from v2.x to v5.x.
For AWS IoT Jobs, refer to the [Jobs migration guide](https://github.com/aws/Jobs-for-AWS-IoT-embedded-sdk/blob/v2.0.1/MigrationGuide.md) for upgrading from v1.x to v2.x.
For coreSNTP, refer to the [coreSNTP migration guide](https://github.com/FreeRTOS/coreSNTP/blob/v2.0.0/MigrationGuide.md) for upgrading from v1.x to v2.x.

**Note:** AWS IoT OTA library is not included in the FreeRTOS LTS releases since 202212-LTS.
AWS IoT MQTT File Streams is included instead, and we suggest users reference
[Modular Over the Air Updates](https://freertos.org/freertos-core/over-the-air-updates/index.html),
which makes use of the AWS IoT MQTT File Streams library for OTA application design.


## FreeRTOS LTS Versioning and Patches

FreeRTOS LTS releases use a date-based versioning scheme (YYYYMM) followed by a patch sequential number (.XX).
For example, FreeRTOS 202604.01 LTS means the first patch to the April-2026 FreeRTOS LTS release.
You can review the [CHANGELOG](./CHANGELOG.md) and subscribe to [GitHub notifications](https://docs.github.com/en/free-pro-team@latest/github/managing-subscriptions-and-notifications-on-github/about-notifications) to receive information on patches or other updates to this repository.   

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT License. See the [LICENSE](LICENSE.md) file.

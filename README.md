## Overview
FreeRTOS offers feature stability with long term support (LTS) releases. FreeRTOS LTS libraries come with security updates and critical bug fixes to the FreeRTOS kernel and IoT libraries listed below for two years, and are maintained by AWS for the benefit of the FreeRTOS community. With FreeRTOS LTS, you get a complete set of libraries needed to build secure connected IoT and embedded products. Long term support helps reduce maintenance and testing costs associated with updating libraries on your devices already in production.

AWS also offers FreeRTOS Extended Maintenance Plan (EMP) that provides you with security patches and critical bug fixes on your chosen FreeRTOS LTS version for up to an additional 10 years. With FreeRTOS EMP, your FreeRTOS-based long-lived devices can rely on a version that has feature stability and receives security updates for years. You receive timely notification of upcoming patches on FreeRTOS libraries, so you can plan the deployment of security patches on your IoT devices. To learn more about FreeRTOS EMP, see the [FreeRTOS Features page](https://aws.amazon.com/freertos/features/).

## FreeRTOS/FreeRTOS Long Term Support

Libraries in this GitHub branch (also listed below) are part of the [FreeRTOS 202210-LTS](https://github.com/FreeRTOS/FreeRTOS-LTS/tree/202210-LTS) release. Learn more at https://freertos.org/lts-libraries.html.

| Library                     | Version             | LTS Until  | LTS Repo URL                                                                |
|-------------------------    |---------------------|------------|---------------------------------------------------------------------------  |
| FreeRTOS Kernel             | 10.5.1              | 10/31/2024 | https://github.com/FreeRTOS/FreeRTOS-Kernel/tree/V10.5.1                        |
| FreeRTOS-Plus-TCP           | 3.1.0               | 10/31/2024 | https://github.com/FreeRTOS/FreeRTOS-Plus-TCP/tree/V3.1.0                       |
| coreMQTT                    | 2.1.1               | 10/31/2024 | https://github.com/FreeRTOS/coreMQTT/tree/v2.1.1                                |
| coreHTTP                    | 3.0.0               | 10/31/2024 | https://github.com/FreeRTOS/coreHTTP/tree/v3.0.0                                |
| corePKCS11                  | 3.5.0               | 10/31/2024 | https://github.com/FreeRTOS/corePKCS11/tree/v3.5.0                              |
| coreJSON                    | 3.2.0               | 10/31/2024 | https://github.com/FreeRTOS/coreJSON/tree/v3.2.0                                |
| coreSNTP                    | 1.2.0               | 10/31/2024 | https://github.com/FreeRTOS/coreSNTP/tree/v1.2.0                                |
| Cellular Interface          | 1.3.0               | 10/31/2024 | https://github.com/FreeRTOS/FreeRTOS-Cellular-Interface/tree/v1.3.0             |
| backoffAlgorithm            | 1.3.0               | 10/31/2024 | https://github.com/FreeRTOS/backoffAlgorithm/tree/v1.3.0                        |
| SigV4                       | 1.2.0               | 10/31/2024 | https://github.com/aws/SigV4-for-AWS-IoT-embedded-sdk/tree/v1.2.0               |
| AWS IoT Device Shadow       | 1.3.0               | 10/31/2024 | https://github.com/aws/Device-Shadow-for-AWS-IoT-embedded-sdk/tree/v1.3.0       |
| AWS IoT Device Defender     | 1.3.0               | 10/31/2024 | https://github.com/aws/Device-Defender-for-AWS-IoT-embedded-sdk/tree/v1.3.0     |
| AWS IoT Jobs                | 1.3.0               | 10/31/2024 | https://github.com/aws/Jobs-for-AWS-IoT-embedded-sdk/tree/v1.3.0                |
| AWS IoT Fleet Provisioning  | 1.1.0               | 10/31/2024 | https://github.com/aws/Fleet-Provisioning-for-AWS-IoT-embedded-sdk/tree/v1.1.0  |
| AWS IoT Over-the-air Update | 3.4.0               | 10/31/2024 | https://github.com/aws/ota-for-aws-iot-embedded-sdk/tree/v3.4.0                 |

## Upgrading to FreeRTOS 202210-LTS from a previous version of FreeRTOS LTS

Refer to https://freertos.org/lts-libraries.html on how to upgrade to FreeRTOS 202210 LTS

## FreeRTOS LTS Versioning and Patches

FreeRTOS LTS releases use a date-based versioning scheme (YYYYMM) followed by a patch sequential number (.XX). For example, FreeRTOS 202210.01 LTS means the first patch to the October-2022 FreeRTOS LTS release. You can review the [CHANGELOG](./CHANGELOG.md) and subscribe to [GitHub notifications](https://docs.github.com/en/free-pro-team@latest/github/managing-subscriptions-and-notifications-on-github/about-notifications) to receive information on patches or other updates to this repository.   

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT License. See the [LICENSE](LICENSE.md) file.

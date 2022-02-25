## Overview
FreeRTOS offers feature stability with long term support (LTS) releases. FreeRTOS LTS libraries come with security updates and critical bug fixes to the FreeRTOS kernel and IoT libraries listed below for two years, and are maintained by AWS for the benefit of the FreeRTOS community. With FreeRTOS LTS, you get a complete set of libraries needed to build secure connected IoT and embedded products. Long term support helps reduce maintenance and testing costs associated with updating libraries on your devices already in production.

AWS also offers FreeRTOS Extended Maintenance Plan (EMP) that provides you with security patches and critical bug fixes on your chosen FreeRTOS LTS version for up to an additional 10 years. With FreeRTOS EMP, your FreeRTOS-based long-lived devices can rely on a version that has feature stability and receives security updates for years. You receive timely notification of upcoming patches on FreeRTOS libraries, so you can plan the deployment of security patches on your IoT devices. To learn more about FreeRTOS EMP, see the [FreeRTOS Features page](https://aws.amazon.com/freertos/features/).

## FreeRTOS/FreeRTOS Long Term Support

Libraries in this GitHub branch (also listed below) are part of the [FreeRTOS 202012.04 LTS](https://github.com/FreeRTOS/FreeRTOS-LTS/tree/202012-LTS) patch release. Learn more at https://freertos.org/lts-libraries.html.

| Library                     | Version             | LTS Until  | LTS Repo URL                                                                |
|-------------------------    |---------------------|------------|---------------------------------------------------------------------------  |
| FreeRTOS Kernel             | 10.4.3-LTS-Patch-2  | 03/31/2023 | https://github.com/FreeRTOS/FreeRTOS-Kernel/tree/V10.4.3-LTS-Patch-2        |
| FreeRTOS-Plus-TCP           | 2.3.2-LTS-Patch-2   | 03/31/2023 | https://github.com/FreeRTOS/FreeRTOS-Plus-TCP/tree/V2.3.2-LTS-Patch-2       |
| coreMQTT                    | 1.1.0               | 03/31/2023 | https://github.com/FreeRTOS/coreMQTT/tree/v1.1.0                            |
| coreHTTP                    | 2.0.0               | 03/31/2023 | https://github.com/FreeRTOS/coreHTTP/tree/v2.0.0                            |
| corePKCS11                  | 3.0.0               | 03/31/2023 | https://github.com/FreeRTOS/corePKCS11/tree/v3.0.0                          |
| coreJSON                    | 3.0.0               | 03/31/2023 | https://github.com/FreeRTOS/coreJSON/tree/v3.0.0                            |
| backoffAlgorithm            | 1.0.0               | 03/31/2023 | https://github.com/FreeRTOS/backoffAlgorithm/tree/v1.0.0                    |
| AWS IoT Device Shadow       | 1.0.2               | 03/31/2023 | https://github.com/aws/Device-Shadow-for-AWS-IoT-embedded-sdk/tree/v1.0.2   |
| AWS IoT Device Defender     | 1.1.0               | 03/31/2023 | https://github.com/aws/Device-Defender-for-AWS-IoT-embedded-sdk/tree/v1.1.0 |
| AWS IoT Jobs                | 1.1.0               | 03/31/2023 | https://github.com/aws/Jobs-for-AWS-IoT-embedded-sdk/tree/v1.1.0            |
| AWS IoT Over-the-air Update | 3.0.0               | 03/31/2023 | https://github.com/aws/ota-for-aws-iot-embedded-sdk/tree/v3.0.0             |

## FreeRTOS LTS Versioning and Patches

FreeRTOS LTS releases use a date-based versioning scheme (YYYYMM) followed by a patch sequential number (.XX). For example, FreeRTOS 202012.02 LTS means the second patch to the December-2020 FreeRTOS LTS release. You can review the [CHANGELOG](./CHANGELOG.md) and subscribe to [GitHub notifications](https://docs.github.com/en/free-pro-team@latest/github/managing-subscriptions-and-notifications-on-github/about-notifications) to receive information on patches or other updates to this repository.   

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT License. See the [LICENSE](LICENSE.md) file.


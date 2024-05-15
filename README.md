
# Easebuzz Payment Gateway

Flutter plugin for Easebuzz Android SDK .


[![pub package](https://img.shields.io/pub/v/easebuzz.svg)](https://pub.dartlang.org/packages/easebuzz)

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [API](#api)
- [Example App](https://github.com/razorpay/razorpay-flutter/tree/master/example)

## Getting Started
This flutter plugin is a wrapper around our Android SDKs.

We have developed this dependency by closely following the official documents of Easebuzz. If you need more details, you can refer to the official documents.

 **EaseBuzz Documents**:
 https://docs.easebuzz.in/docs/payment-gateway/7pno7lhpkyt0f-flutter

## Prerequisites
- Learn about the <a href="https://docs.easebuzz.in/docs/payment-gateway/y3ujtl2emd5bg-transaction-flow" target="_blank">EaseBuzz Payment Flow</a>.
-  Create an <a href="https://auth.easebuzz.in/easebuzz/login">EaseBuzz account </a> and generate the API keys from the EaseBuzz Dashboard. Utilize the Test keys to simulate a sandbox environment; no real monetary transactions occur with the Test keys. Transition to Live keys only after thoroughly testing the application and being prepared to go live.

## Installation

This plugin is available on Pub: [https://pub.dev/packages/easebuzz](https://pub.dev/packages/easebuzz)

Add this to `dependencies` in your app's `pubspec.yaml`

```yaml
easebuzz: ^1.0.0
```

**Note for Android**: Make sure that the minimum API level for your app is 21 or higher.




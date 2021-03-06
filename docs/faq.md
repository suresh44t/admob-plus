---
id: faq
title: Frequently Asked Questions
---

## How this project relates to `cordova-plugin-admob-free`?

`admob-plus` is the successor of [cordova-plugin-admob-free](https://github.com/ratson/cordova-plugin-admob-free), which provides a cleaner API and build with modern tools.

`cordova-plugin-admob-free` is orginally a fork by removing ad-sharing code from `cordova-plugin-admob-simple`, which is also fork from `cordova-plugin-admob`. Therefore, many hacks and APIs are inherited. As the project evolves, the code for Android was completely rewritten, and new APIs were added under constraints of existing code orginalization and architecture.

With the growing number of reported issues, it is clear that a better solution is needed, so `admob-plus` is borned with the following features in mind:

* Written in TypeScript
* First-class promise API
* Rewrite iOS part using Swift
* Official Ionic support
* Rich documentation

## Why funding using subscription plan instead of a (open amount) donation button?

Unfortunately, transfer money between two parties is not free, payment processors charges transaction fee plus a fixed fee based on currency received.

Therefore, small transactions means the percentage for payment processors will be higher, it is more like funding the payment processor rather than my work, I would prefer people to wait and accumulate until they are ready pay with a reasonable bigger amount.

IMO, small teams should focus on their product and move forward as quick as possible, while established teams should consider giving back to the community for what makes them succeed.

I choose to have [a few fixed amount subscription plans](https://ratson.name/fund-admob-plus/), which can be cancelled at any time, so people who want to fund more could simply subscribe the plan longer. This also help me easily determine how much time I would spend on the projects each month.

Maintaining an open source project is a continuous effort, I wish the support goes the same if possible.

Other funding options are welcome, feel free to [suggest your preference](https://github.com/admob-plus/admob-plus/issues/new?title=%5BFunding%20Suggestion%5D).

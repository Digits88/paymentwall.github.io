---
id: go_live
title: Go Live Integration Checklist
sectionid: docs
permalink: go_live-home
---

# Project go live

Your project is always in sandbox environment when its status is not live, where only [test payment](/paymentwall.github.io/sandbox/test-payment) is allowed to be used.

You can submit your project for review by clicking **SUBMIT FOR REVIEW** button.

<div class="docs-img" style="text-align: center;">
	<img src="/paymentwall.github.io/textures/pic/reference/golive/golive-submit-for-review.png" style="max-width: 30%">
</div>

## Adjustment before going live

Paymentwall team will take a whole review of your project and set your project status according to [checklist](#checklist). You just need to do a few adjustments to assurance your project could work normally in live environment.

* API credentials

It mostly depends on the product you are using.

[PayAlto](/paymentwall.github.io/payalto-home) uses same API credentials in both sandbox and live environment.

For merchants who are using [Brick](/paymentwall.github.io/brick-home), you will need to replace your brick test credentials to the live one.

* Disable test payment method

By default, we disable test payment immediately for your project when its status is changed to live. 

We recommend you to create another project under your Paymentwall account as staging project.

## Checklist

A checklist form will be opened and asking you to confirm that you have completed associated operations once you submit your project for review.

* [Integration checklist](/paymentwall.github.io/go_live-integration).

* [Business checklist](/paymentwall.github.io/go_live-compliance).



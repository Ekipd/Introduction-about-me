---
title: MerchantValidationEvent.methodName
slug: Web/API/MerchantValidationEvent/methodName
page-type: web-api-instance-property
status:
  - deprecated
browser-compat: api.MerchantValidationEvent.methodName
---

{{APIRef("Payment Request API")}}{{Deprecated_Header}}{{SecureContext_Header}}

The {{domxref("MerchantValidationEvent")}} property
**`methodName`** is a read-only value which returns a string
indicating the payment method identifier which represents the payment handler that
requires merchant validation.

## Value

A read-only string which uniquely identifies the payment handler
which is requesting merchant validation. See
[Merchant validation](/en-US/docs/Web/API/Payment_Request_API/Concepts#merchant_validation) for more information on the process.

## Browser compatibility

{{Compat}}

## See also

- [Payment Request API](/en-US/docs/Web/API/Payment_Request_API)
- [Using the Payment Request API](/en-US/docs/Web/API/Payment_Request_API/Using_the_Payment_Request_API)
- [Payment processing concepts](/en-US/docs/Web/API/Payment_Request_API/Concepts)

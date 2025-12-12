# Unzer Payment extension for Hyvä React Checkout Magento 2
Hyvä React Checkout Compatibility module for Unzer payment plugin.

## Supported payment methods

Unzer payment plugin includes the following payment methods:
* [Alipay](https://docs.unzer.com/payment-methods/alipay/)
* [Apple Pay](https://docs.unzer.com/payment-methods/applepay/)
* [Bancontact](https://docs.unzer.com/payment-methods/bancontact/)
* [Cards and Click to Pay (CTP)](https://docs.unzer.com/payment-methods/card/)
* [EPS](https://docs.unzer.com/payment-methods/eps/)
* [Google Pay](https://docs.unzer.com/payment-methods/googlepay/#page-title)
* [Klarna](https://docs.unzer.com/payment-methods/klarna/)
* [PayPal](https://docs.unzer.com/payment-methods/paypal/)
* [Przelewy24](https://docs.unzer.com/payment-methods/przelewy24/)
* [TWINT](https://docs.unzer.com/payment-methods/twint/)
* [Unzer Direct Bank Transfer](https://docs.unzer.com/payment-methods/open-banking/)
* [Unzer Direct Debit](https://docs.unzer.com/payment-methods/unzer-direct-debit/)
* [Unzer Invoice B2B](https://docs.unzer.com/payment-methods/unzer-invoice-upl/)
* [Unzer Prepayment](https://docs.unzer.com/payment-methods/unzer-prepayment/)
* [WeChat Pay](https://docs.unzer.com/payment-methods/wechat-pay/)
* [Wero](https://docs.unzer.com/payment-methods/wero/)

## Requirements

- Magento 2.4.6, 2.4.7 or 2.4.8
- [Base Unzer Magento 2 Plugin](https://docs.unzer.com/plugins/magento-2/) installed.
- [Hyvä Theme module](https://docs.hyva.io/hyva-themes/getting-started/index.html) installed.
- [Hyvä React Checkout module](https://docs.hyva.io/checkout/react-checkout/installing-react-checkout-with-composer.html) installed and enabled.

## Installation

Open the package.json file and add the following line:

```bash
"config": {
"paymentMethodsRepo": {
"unzer": "git@github.com:unzerdev/magento2-hyva-react-checkout.git"
  }
}
```

Under `src/components/DefaultRenderer.js` import:
```bash
import unzerRenderers from './unzer/renderers';

export default {
  ...unzerRenderers,
};
```
Next, run npm install. This should install the repository into your checkout.

## Support

For any issues or questions please get in touch with our support.

**Email**: support@unzer.com

**Phone**: +49 (0)6221/6471-100

**Twitter**: [@UnzerTech](https://twitter.com/UnzerTech)

**Webpage**: https://unzer.com/

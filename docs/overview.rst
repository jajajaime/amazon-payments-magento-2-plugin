Overview
========
This extension provides an official integration of your Magento 2 store with **Amazon Pay and Login with Amazon** services. The extension is a checkout and payment solution that does not share any item level information (product information, prices, basket content, etc) with Amazon. The extension integrates Amazon Pay seamlessly into the Magento 2 shop backend (configuration, order management, billing, etc.).

About Amazon Pay
----------------

Amazon Pay offers a familiar and convenient buying experience that can help your customers spend more time shopping and less time checking out. Amazon Pay is used by large and small companies. From years of shopping safely with Amazon, customers trust their personal information will remain secure and know many transactions are covered by the Amazon A-to-z Guarantee. Businesses have the reassurance of our advanced fraud protection and payment protection policy.

Extension features
------------------

* `Amazon Pay` button in the shopping cart, mini-cart, on product pages and in the 1st step of checkout
* `Login with Amazon` button on the customer login and registration page
* `Amazon Pay` in the list of available payment methods during the final step of checkout
* Configuration of `Amazon Pay` extension from within Magento admin
* Support for payment authorizations, captures and refunds (also partial refunds)
* Support for synchronous and asynchronous authorization mode
* Supports `Amazon Pay` Instant Payment Notifications
* Live & sandbox modes available
* Options for simulating payment states in sandbox mode
* [EU/UK only] Multi-currency support
* [EU/UK only] Support for Strong Customer Authorization (PSD2 compliant)

Prerequisites
-------------

* PHP 7.1 (or higher) when using the latest version of the extension. Older versions of the extension may support older PHP versions. 
* Magento CE (2.1.0 or higher)
* cURL for PHP
* DOM / XML for PHP
* valid SSL certificate
* A verified Amazon Pay merchant account - `sign up here`_!

.. _`sign up here`: https://pay.amazon.com/signup

Installation and Configuration
------------------------------

The extension is available via composer, Magento Marketplace or, with Magento 2.2.4 and higher, already pre-installed as bundled extension.

Please refer to the :doc:`installation` section to get more details concerning installation procedure.

Branch information
------------------

The following table provides an overview on which Git branch is compatible to which Magento 2 version. The last column "Latest release" refers to the latest version of our extension that is compatible to the Magento 2 version in the first column.

+---------------------+-------------------+--------------------+
| **Magento Version** | **Github Branch** | **Latest release** |
+---------------------+-------------------+--------------------+
| 2.1.0 - 2.2.3       | `1.x`_            | 1.2.8              |
+---------------------+-------------------+--------------------+
| 2.2.4 - 2.2.5       | `2.x`_            | 2.0.16             |
+---------------------+-------------------+--------------------+
| 2.2.6 - 2.2.x       | `2.1.x`_          | 2.2.14             |
+---------------------+-------------------+--------------------+
| 2.3.0 and above     | `master`_         | 3.2.9              |
+---------------------+-------------------+--------------------+

.. _`1.x`: https://github.com/amzn/amazon-payments-magento-2-plugin/tree/1.x
.. _`2.x`: https://github.com/amzn/amazon-payments-magento-2-plugin/tree/2.x
.. _`2.1.x`: https://github.com/amzn/amazon-payments-magento-2-plugin/tree/2.1.x
.. _`master`: https://github.com/amzn/amazon-payments-magento-2-plugin/tree/master
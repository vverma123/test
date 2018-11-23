Symplr\Payment\Refund\Features\Vendor1\ProspectDatabaseTransaction
===============

The short description

As many lines of extendend description as you want \Symplr\Payment\Refund\Features\Vendor1\element links to an element
[Example hyperlink inline link](http://www.example.com) links to a website
Below this goes the tags to further describe element you are documenting


* Class name: ProspectDatabaseTransaction
* Namespace: Symplr\Payment\Refund\Features\Vendor1
* Parent class: [Symplr\Payment\Refund\RefundFeatureDecorator](Symplr-Payment-Refund-RefundFeatureDecorator.md)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.





Properties
----------


### $paymentHistoryRepository

    protected mixed $paymentHistoryRepository





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $feature

    public \Symplr\Payment\Refund\RefundFeatureInterface $feature





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


Methods
-------


### __construct

    mixed Symplr\Payment\Refund\RefundFeatureDecorator::__construct(\Symplr\Payment\Refund\RefundFeatureInterface $feature)

RefundFeatureDecorator constructor.



* Visibility: **public**
* This method is defined by [Symplr\Payment\Refund\RefundFeatureDecorator](Symplr-Payment-Refund-RefundFeatureDecorator.md)


#### Arguments
* $feature **[Symplr\Payment\Refund\RefundFeatureInterface](Symplr-Payment-Refund-RefundFeatureInterface.md)**



### process

    mixed Symplr\Payment\Refund\RefundFeatureInterface::process(\Symplr\Payment\Refund\RefundData $data)





* Visibility: **public**
* This method is defined by [Symplr\Payment\Refund\RefundFeatureInterface](Symplr-Payment-Refund-RefundFeatureInterface.md)


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



### getTransaction

    mixed Symplr\Payment\Refund\Features\Vendor1\ProspectDatabaseTransaction::getTransaction(\Symplr\Payment\Refund\RefundData $data)

This feature is used to fetch the prospect database transaction from the database and set the data in the refund data object.



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



### fetchTransactionDetail

    mixed Symplr\Payment\Refund\Features\Vendor1\ProspectDatabaseTransaction::fetchTransactionDetail(\Symplr\Payment\Refund\RefundData $data)

This feature is used to fetch the prospect database transaction from the database and set the data in the refund data object.



* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



### nextFeature

    mixed Symplr\Payment\Refund\RefundFeatureDecorator::nextFeature(\Symplr\Payment\Refund\RefundData $data)





* Visibility: **public**
* This method is defined by [Symplr\Payment\Refund\RefundFeatureDecorator](Symplr-Payment-Refund-RefundFeatureDecorator.md)


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



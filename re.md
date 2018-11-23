Symplr\Payment\Refund\Features\Vendor1\ProspectDatabaseTransaction
===============

This feature is used to fetch the prospect database transaction from the database and set the data in the refund data object.




* Class name: ProspectDatabaseTransaction
* Namespace: Symplr\Payment\Refund\Features\Vendor1
* Parent class: [Symplr\Payment\Refund\RefundFeatureDecorator](Symplr-Payment-Refund-RefundFeatureDecorator.md)





Properties
----------


### $paymentHistoryRepository

    protected mixed $paymentHistoryRepository





* Visibility: **protected**


### $feature

    public \Symplr\Payment\Refund\RefundFeatureInterface $feature





* Visibility: **public**


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





* Visibility: **public**


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



### fetchTransactionDetail

    mixed Symplr\Payment\Refund\Features\Vendor1\ProspectDatabaseTransaction::fetchTransactionDetail(\Symplr\Payment\Refund\RefundData $data)





* Visibility: **public**


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



### nextFeature

    mixed Symplr\Payment\Refund\RefundFeatureDecorator::nextFeature(\Symplr\Payment\Refund\RefundData $data)





* Visibility: **public**
* This method is defined by [Symplr\Payment\Refund\RefundFeatureDecorator](Symplr-Payment-Refund-RefundFeatureDecorator.md)


#### Arguments
* $data **[Symplr\Payment\Refund\RefundData](Symplr-Payment-Refund-RefundData.md)**



# ScheduledTransactionDetail

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**date_first** | **date** | The first date for which the Scheduled Transaction was scheduled. | 
**date_next** | **date** | The next date for which the Scheduled Transaction is scheduled. | 
**frequency** | **str** |  | 
**amount** | **float** | The scheduled transaction amount in milliunits format | 
**account_id** | **str** |  | 
**account_name** | **str** |  | 
**subtransactions** | [**list[ScheduledSubTransaction]**](ScheduledSubTransaction.md) | If a split scheduled transaction, the subtransactions. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



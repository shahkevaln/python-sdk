# OptionPrice

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**date** | **str** | The date of the price, in the format YYYY-MM-DD | [optional] 
**close** | **float** | The closing price of the options contract. | [optional] 
**close_bid** | **float** | The closing bid price of the options contract. | [optional] 
**close_ask** | **float** | The closing ask price of the options contract. | [optional] 
**volume** | **int** | The cumulative volume of this options contract that traded that day. | [optional] 
**volume_bid** | **int** | The cumulative volume of this options contract that traded on the bid price that day. | [optional] 
**volume_ask** | **int** | The cumulative volume of this options contract that traded on the ask price that day. | [optional] 
**trades** | **int** | The number of trades executed that for this options contract on that day. | [optional] 
**open_interest** | **int** | The total number of this options contract that are still open. | [optional] 
**open_interest_change** | **int** | The change in the total number of this options contract that are still open from the previous day. | [optional] 
**next_day_open_interest** | **int** | The total number of this options contract that are still open at the start of the next day. | [optional] 
**implied_volatility** | **float** | The estimated volatility of the Security&#39;s price. Volatility is a statistical measure of dispersion of returns for the Security. Standard deviation of a Security&#39;s returns and a market index is an example of a measurement of volatility. Implied volatility approximates the future value of an option, and the option&#39;s current value takes this into consideration. | [optional] 
**implied_volatility_change** | **float** | The change in implied volatility for that day. | [optional] 
**delta** | **float** | Delta measures the degree to which an options contract is exposed to shifts in the price of the underlying Security. Values of delta range from 0.0 to 1.0 for call options and -1.0 to 0.0 for put options. For example, if a put option has a delta of -0.50, if the price of the underlying Security increases by $1, the price of the put option will decrease by $0.50. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



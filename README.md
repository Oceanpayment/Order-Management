#Overview
Oceanpayment order management API can query pre-authorize changes to the order status in real-time, process refunds, upload logistics information, customs push, etc.
##Precautions

+ Order management request methods are: Socket or HttpClient,
+ The server IP needs to be registered before all function requests, please contact Oceanpayment technical support staff.
#List
##Query Orders
The order status query function can query the real-time transaction status of the order and supports batch query.


##Query Success Orders
The successful order acquisition function can query the successful transaction data in a certain period of time.


##Query Business Orders
The business order acquisition function can query the business status of the order, such as: refund result, refusal, appeal, counterfeiting, order transfer, etc.


##Refund
You can submit orders that require a refund, and support partial refunds and full refunds.


##Refund Query
The result of the refund can be checked through this function.


##Pre-Auth
The pre-authorized order can be successfully authorized and withdrawn through the pre-authorization function.


##Tracking Number Upload
Successful orders need to upload the logistics order number through this function.


##Void
The order viod function can only be used in offline scenarios of WeChatPay & Alipay.


##Customs Upload
WeChatPay&Alipay&UnionPay orders can be sent through customs through this function.


##Health examination
Check whether the account number / terminal number / secureCode is filled in correctly,Check whether the correct setting info matches to the corresponding source URL.


##Card bin verification
Obtain accurate card type information.
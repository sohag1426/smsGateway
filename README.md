# SMS Gateway

#### # 1000 BDT for provisioning fee.
#### # Monthly SMS Bills Based on Usage.
#### # No Limit on SMS Usages.
#### # No SMS Merchant if not payment GW Merchant.
#### # SMS Bills must be paid through the online payment gateway owned by the merchant of the SMS Gateway.

### # Three important methods of SMS gateway.
* isMerchant(operator $operator) {}
  * Is the operator has one sms gateway.
  * Return is boolean
  
* getMerchant(sms_gateway $sms_gateway){}
  * Return operator instance of the sms gateway

* getSmsGw(operator $operator){}
  * If operator has one sms gateways return the sms gateway.
  * If group admin of the operator has one sms gateway return the sms gateway.
  * If Super Admin of the operator has one sms gateway return the sms gateway.
  * Return must be instance of sms gateway if has sms gateway.
  

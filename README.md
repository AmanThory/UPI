# UPI Payment Service
UPI Payment Service for Merchant
## Workflow:
1. User go to UPI payment page and enter details like Remitter Mobile Number, Remitter Email, Payee VPA, Payee Name, Amount, Transaction Reference ID, Transaction Note.
2. On clicking submit button, a UPI link is generated along with it’s short url.
3. This short URL is sent as SMS to user mobile and his email.
4. When user browse this short URL in mobile, it will redirect to that UPI link and invokes the local PSP application (like BHIM or PhonePe), where the user can confirm the details, and complete the payment.

![UPI](https://github.com/atultherajput/UPI/blob/master/assets/upi-screenshot.png)

## Note:
You need to register at [Textlocal](https://www.textlocal.in) (SMS service provider) to get API key (10 free credits to new users).

##### Testing Server: http://104.211.76.88:5000/

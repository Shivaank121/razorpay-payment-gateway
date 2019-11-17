# razorpay-payment-gateway
How to integrate razorpay payment gateway in front-end using Standard Checkout Integration?


## Flow:
1. When you load the page index.html, an order creation API will be hit in the url provided on line 24 (checkout API),
2. When you click pay, razorpay opens a payment box. The payment can be made there.
3. After the payment is successful, razorpay sends razorpay-order-id, razorpay-signature, and razorpay-payment-id, on the API mentioned on line 43 (payment capture API) where the payment needs to be verified as mentioned on the docs page of razorpay.
4. Backend logic needs to be implemented on the mentioned API endpoints.

Response can be stored in database accordingly.

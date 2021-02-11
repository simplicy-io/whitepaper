## Problems

For most ecommerce retailers, payment gateways are seen as a necessary evil. Yes, they help you accept payments from your customers, but they’re not at the top of your list of organizations you like working with. They’ve developed a reputation of being sleazy, money-grubbing middlemen that take advantage of retailers, both big and small.

Some modern payment gateways, like Paypal, Stripe and Adyen, are finding ways to create more value for retailers and they’ve developed good reputations because of that. But problems remain. 

### High fees merchants

Payment gateways have long been rebuked by retailers for their high processing costs. The average rate today is 2.9% + 30c per transaction for online, or card-not-present, transactions. These costs have slowly increased for retailers, while the underlying cost and risk associated with processing these payments have decreased for gateways.

Merchants have to pay up to 15(!) different types of fees in order to accept payments from their customers.

- Transaction fees are somewhere between 2% and 6% per transaction plus a fixed fee, which is between USD 0.1 and USD 0.7. Example: every time someone makes a transaction for USD 10, the merchant on average pays => 10*((0.02+0.06)/2) + ((0.1+0.7)/2)) = USD 0.8 for banks, credit card associations, payment gateways and processors.
- Retrieval Request Fee and Chargeback Fee are paid when someone claims for a chargeback. The best-known payment gateways such as PayPal and Stripe charge merchants USD 15 for chargeback.
- Flat fees consist of such fees as payments to buy the terminal device for retail merchants, PCI fees paid to Payment Card industry for compliance OR noncompliance and others, such as Annual fees, Monthly fees, Monthly minimum fees, IRS reporting fees, network fees, etc.
- Occasional fees that consist of Address Verification Service (AVS), VoiceAuthorization Fee (VAF), Batch Fee, and NFS fee.

### Payment processors keep their fee  structure hidden
Merchant processing fees generally fall into one of two categories: 
- (1) wholesale fees, and 
- (2) markups. 

Wholesale fees are the interchange rates set by issuing banks and credit card companies.
They are consistent regardless of which gateway you choose, so don’t waste your time trying to shop around for lower interchange rates. 
Markup fees are how your processor and/or gateway make a profit from your business. With the right gateway, these fees will be modest, but with the wrong gateway, you’re in big trouble. Some gateways make it as difficult as possible to know how much markup you’re paying by using bewildering terms and pricing models that would baffle even the most experienced business owner or retailer. Just a few examples include PCI fees, early termination fees, monthly minimum fees, statement fees, IRS report fees, and batch fees.

If you’re a large enough retailer, finding an interchange plus pricing model is usually the most transparent and cost-effective. Tiered pricing is traditionally the murkiest, including the most hidden fees. The newer gateways are using a blended model that keeps pricing simple, but costs tend to be higher for high-volume businesses, especially on debit transactions.

### Payment processors treat merchants unfairly on disputes and chargebacks
Overall, chargebacks and fraud account for less than 1% of all transactions globally. However, the rate is higher for e-commerce transactions, and it’s growing. A typical e-commerce business offering physical products should see a 0.10% - 0.30% chargeback ratio, and a little over half of those will be for fraud. If you sell a non-physical product online, you’re likely to see a little higher ratio. And if you’re offering a subscription service, it will be higher still.

Chargeback fraud, also known as friendly fraud, is also a major problem for e-commerce retailers. This occurs when a consumer makes an online purchase, and then requests a chargeback from their issuing bank after receiving the purchased goods or services.

When a chargeback is approved, the merchant is accountable, regardless of the measures they took to verify the transaction. To add insult to injury, gateways will charge merchants a penalty when a chargeback occurs, because of the cost and risk to their own businesses (gateways can be shut down if their chargeback rates get too high).

Make sure you read the fine print in your gateway contracts, to better understand what the chargeback process looks like and how much you are penalized when a chargeback occurs. As a general rule, credit cards are most favorable to consumers when they request a chargeback, debit cards are in the middle, and bank payments are most favorable to merchants.

### No recurring payments
A major shift is taking place in our economy, from a pay-per-product model to a subscription-based model. While recurring revenue provides businesses more steady cash flows, it requires companies to better manage a direct, complex, responsive, multi-channel relationship with its customers. Customers are absolutely key in this relationship, and rather than putting the focus of the business on the “product” or the “transaction,” subscription economy companies live and die by their ability to monetize long-term relationships rather than shipping products.
This poses a major challenge to payment gateways as well. Subscription-based companies typically see between 15-20% of recurring payments fail due to expired or canceled credit and debit cards. This is known in the business as “incidental churn.” Companies like Recurly have sprouted up to help businesses combat churn, but the fact is, cards are not an optimal payment method for recurring payments. An interesting solution some gateways are employing, including Sezzle and PayPal, is to enable customers to pay businesses directly from their bank accounts, which significantly reduces churn due to the fact that most people rarely change checking accounts. Many gateways are still behind the times, though, and for the subscription economy to continue growing, recurring payments must get better.


### Transation settlement
Costly and complex transaction settlements with up to 16 (!) steps to accept and settle the transaction
The picture below describes the payment process with rejection handling in 8 steps regardless of if it is in a store, e-commerce or m-commerce. The process is complex and includes 8 additional steps to settle the transaction. In total, you have 16 steps for money to arrive from client’s bank account to merchant’s bank account.

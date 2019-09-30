# WP-Plugin-Delivery-date
Define delivery date by Product vendor for woocommerce 
I am trying to add delivery-date set by vendor for virtual product, Vendor should set delivery date at the time of creation of product.
the problem is many plugin offered that customer can pick and select delivery date as per there comfort, whereas in my case product 
should be delivery on VENDOR defined date.

Technical Justification:
In Virtual-product, Some services has to be delivered in predefined date " which is probably set by vendor who will create and deliver that services to
customer." for example. I hired graphic designer who will create logo for me, he will required 3 days to complete his work and deliver
the things to Customer.
Now Graphic designer will create Services-as-product and set minimum delivery time for 3 days. So. the delivery date will be 3rd day after buying
his Gig.or service."

Technical Addition:
1. Add textBox(DeliveryDate) Data type Number 1-99 range. at Product-vendor page at time of initiating product or article
2. Always display textBox(DeliveryDate) at product page 
3. Always display textBox(DeliveryDate) at Checkout page 
4. Always display textBox(DeliveryDate) at cartpage page 
5. At checkout, textBox(DeliveryDate) consider as FINAL DELIVERY DATE

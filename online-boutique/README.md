Google's Online Boutique Microservices Demo adapted for Kustomize and for a proxied env with quay.io access only.

## Deploy
~~~
# oc apply -k .
namespace/online-boutique created
service/adservice created
service/cartservice created
service/checkoutservice created
service/currencyservice created
service/emailservice created
service/frontend created
service/paymentservice created
service/productcatalogservice created
service/recommendationservice created
service/redis-cart created
service/shippingservice created
deployment.apps/adservice created
deployment.apps/cartservice created
deployment.apps/checkoutservice created
deployment.apps/currencyservice created
deployment.apps/emailservice created
deployment.apps/frontend created
deployment.apps/paymentservice created
deployment.apps/productcatalogservice created
deployment.apps/recommendationservice created
deployment.apps/redis-cart created
deployment.apps/shippingservice created
horizontalpodautoscaler.autoscaling/frontend-hpa created
route.route.openshift.io/frontend created
~~~

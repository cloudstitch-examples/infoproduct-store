---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---



<form action="{{site.data.cloudstitch.api_endpoint}}" method="POST">
  <script
    src="https://checkout.stripe.com/checkout.js" class="stripe-button"
    data-key="pk_test_cxPJbO9XxjcWpu0m52jCFETi"
    data-amount="100"
    data-name="Pretend PDF Book"
    data-description="A pretend PDF Book"
    data-image="https://stripe.com/img/documentation/checkout/marketplace.png"
    data-locale="auto">
  </script>
</form>


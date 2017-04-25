---
layout: default
---

<div class="theBook">
  <img src="book.png">
</div>
<div class="thePitch">
  <div>
    <h1>This pretend ebook is being sold by a static site</h1>
    <p class="desc">All you need is a static site project in Github, a Stripe account, and Cloudstitch to handle the backend plumbing: receipts, emails, and Google Drive-based asset storage.</p>
    <form action="{{site.data.cloudstitch.api_endpoint}}" method="POST">
      <script
        src="https://checkout.stripe.com/checkout.js" class="stripe-button"
        data-key="pk_live_or1sC0BNcVEejcrQqDGx666f"
        data-amount="100"
        data-name="Pretend PDF Book"
        data-description="A pretend PDF Book"
        data-image="https://stripe.com/img/documentation/checkout/marketplace.png"
        data-locale="auto">
      </script>
      <input type="hidden" name="stripeAmount" value="100" />
      <input type="hidden" name="stripeCurrency" value="usd" />
      <input type="hidden" name="stripeDescription" value ="A pretend book." />
      <input type="hidden" name="_redirect" value =" https://cloudstitch-examples.github.io/infoproduct-store/thanks" />
    </form>
    <p class="smallprint">*We will actually charge you, but you are buying a PRETEND book.</p>
  </div>
</div>  


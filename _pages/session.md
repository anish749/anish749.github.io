---
title: "Live Coding Sessions"
permalink: /session/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/landing/header.jpg
---
# Schedule

Choose a time (in your timezone) to have a call:
<!-- Calendly inline widget begin -->
<div class="calendly-inline-widget" data-url="https://calendly.com/anish749/meet?hide_event_type_details=1" style="min-width:320px;height:630px;"></div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js"></script>
<!-- Calendly inline widget end -->

# Subscribe to a plan
<script type="text/javascript" src="https://js.stripe.com/v3/"></script>
<form id="signup-form">
  <div class="signup-form-class">
    <!-- <label
      class="block text-gray-500 font-bold mb-2"
      for="inline-full-name"
    >
      Email address
    </label> -->
    <input
      class="appearance-none border-2 border-gray-200 rounded-md w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-pasha"
      id="email"
      type="text"
      placeholder="Email address"
      required
    />
  </div>

  <button
    id="email-submit"
    class="w-full bg-pasha hover:bg-red-200 hover:shadow-outline rounded-md hover:text-pasha hover:border hover:border-black focus:shadow-outline text-white focus:bg-white focus:text-pasha font-light py-2 px-4 rounded"
    type="submit">
    <div id="loading" class="hidden">Signing up...</div>
    <span id="button-text">Sign up</span>
  </button>
</form>
        
<!-- Code from feature row -->

<div class="feature__wrapper">
 
    <div class="feature__item">
      <div class="archive__item">
        <div class="archive__item-body">
            <h2 class="archive__item-title">Prepaid</h2>
            <div class="archive__item-excerpt">
              <p>Paid in advance, charged at 80 USD / 55 mins or equivalent</p>
            </div>
            <p><a onclick="handlePrepaid()" class="btn btn--primary">Buy</a></p>
            <div id="error-message"></div>
        </div>
      </div>
    </div>
  
    <div class="feature__item">
      <div class="archive__item">
        <div class="archive__item-body">
            <h2 class="archive__item-title">Pay-as-you-go</h2>
            <div class="archive__item-excerpt">
              <p>Submit payment details to be charged later</p>
            </div>
            
            <p><a onclick="handlePayg()" class="btn btn--primary">Submit Payment Details</a></p>
        </div>
      </div>
    </div>
    
</div>


# Bookmark
- [Zoom](https://zmurl.com/call-anish)
- [Email](mailto:anish749@gmail.com)
- [WhatsApp](https://wa.me/46725323840)

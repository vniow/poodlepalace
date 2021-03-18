---
permalink: /messenger.html
---
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId            : 'your-app-id',
      autoLogAppEvents : true,
      xfbml            : true,
      version          : 'v10.0'
    });
  };
</script>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js"></script>
      <script>

      FB.Event.subscribe('send_to_messenger', function(e) {
      // callback for events triggered by the plugin

      });

      </script>
<div class="fb-send-to-messenger" 
  messenger_app_id="<APP_ID>" 
  page_id="PAGE_ID" 
  data-ref="<PASS_THROUGH_PARAM>" 
  color="<blue | white>" 
  size="<standard | large | xlarge>">
</div>

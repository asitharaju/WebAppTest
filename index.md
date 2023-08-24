<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DD6000000VTQ2',
				'Messaging_Web_Test',
				'https://sleepforce--sebuludev6.sandbox.my.site.com/ESWMessagingWebTest1692881784310',
				{
					scrt2URL: 'https://sleepforce--sebuludev6.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://sleepforce--sebuludev6.sandbox.my.site.com/ESWMessagingWebTest1692881784310/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>


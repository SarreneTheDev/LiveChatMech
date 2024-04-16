<html>
	<body>

		<script type='text/javascript'>
			function initEmbeddedMessaging() {
				try {
					embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
		
					embeddedservice_bootstrap.init(
						'00DHo000002HbgZ',
						'Mechaniqxe_Chat_In_App_Web',
						'https://dloh-231204-63-demo.my.site.com/ESWMechaniqxeChatInApp1713160841969',
						{
							scrt2URL: 'https://dloh-231204-63-demo.my.salesforce-scrt.com'
						}
					);
				} catch (err) {
					console.error('Error loading Embedded Messaging: ', err);
				}
			};
		</script>
		<script type='text/javascript' src='https://dloh-231204-63-demo.my.site.com/ESWMechaniqxeChatInApp1713160841969/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

	</body>

</html>

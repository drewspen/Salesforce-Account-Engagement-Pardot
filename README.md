# Salesforce-Account-Engagement-Pardot
GTM tag template tpl used for the base Salesforce Account Engagement - Pardot tag

For use when the GTM tag template equivalent matches the following. 

<script type="text/javascript">
piAId = {{Pardot Account Id}} ;
piCId = {{Pardot Campaign Id}} ;
piHostname = 'pi.pardot.com';
if(!window['pi']) { window['pi'] = {}; } pi = window['pi']; if(!pi['tracker']) { pi['tracker'] = {}; } pi.tracker.pi_form = true;
(function() {
	function async_load(){
		var s = document.createElement('script'); s.type = 'text/javascript';
		s.src = ('https:' == document.location.protocol ? 'https://pi' : 'http://cdn') + '.pardot.com/pd.js';
		var c = document.getElementsByTagName('script')[0]; c.parentNode.insertBefore(s, c);
	}
	if(window.attachEvent) { window.attachEvent('onload', async_load); }
	else { window.addEventListener('load', async_load, false); }
})();
</script>

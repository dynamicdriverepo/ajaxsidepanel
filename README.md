# Ajax Side Panel script #

*Description:* Ajax Side Panel script fetches a page on your site using Ajax and displays it as part of the current page, using a slide out panel as its medium. It is ideal for showing short pages such as your "Contact Us" or "Terms of Service" page where whisking users to the new page only causes unnecessary delay and disorientation for the user. With Ajax Side Panel, the user remains on the current page while the requested one is loaded inline and asynchronously. The script supports loading a page either via Ajax or IFRAME. The later can be used to load more complex web pages on your site or from outside domains (Ajax is limited in this respect by the same domain origin policy).

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.7 or above (served via Google CDN)
+ ddajaxsidepanel.js
+ ddajaxsidepanel.css
+ Two images

*Step 2:* Add the below code to the HEAD section of your page:

	<script type='text/javascript' src='https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js'></script>
	<link rel="stylesheet" type="text/css" href="ddajaxsidepanel.css" />
	<script src="ddajaxsidepanel.js">
	
	/***********************************************
	* Ajax Side Panel script- © Dynamic Drive (www.dynamicdrive.com)
	* This notice MUST stay intact for legal use
	* Visit http://www.dynamicdrive.com/ for this script and 100s more.
	***********************************************/
	
	</script>

*Step 3:* Then, add the below sample markup to your page:

	<ul>
	<li><a href="http://www.dynamicdrive.com" rel="ajaxpanel">Dynamic Drive</a> (external link, auto loads in IFRAME)</li>
	<li><a href="http://www.cssdrive.com" rel="ajaxpanel">CSS Drive</a> (external link, auto loads in IFRAME)</li>
	<li><a href="index.html" rel="ajaxpanel">My Home Page</a> (internal link, auto loads using Ajax)</li>
	<li><a href="http://www.mysite.com/index.html" rel="ajaxpanel">My Home Page</a> (still internal link, assuming mysite.com is your site's domain, auto loads using Ajax)</li>
	<li><a href="http://www.mysite.com/index.html" rel="ajaxpanel" data-loadtype="iframe">My Home Page</a> (internal link, but explicitly load in iframe due to data attribute)</li>
	</ul>

## Ajax Side Panel script set up ##

See script project page for additional details on setup and documentation: <http://www.dynamicdrive.com/dynamicindex17/ajaxsidepanel.htm>

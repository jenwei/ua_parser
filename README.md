# userAgent
check browser and browser's version from userAgent

# usage

=========================
var ua = util.userAgent();

ua = {
    ua,
    browser: {
    	[msie | safari | firefox | chrome | opera | android | iphone | ipad | ipod | polaris | dolfin] : true,
    	version: {
    		major, // type string
    		minor, // type string
    		patch  // type string
    	}
    },
    platform : ["pc" | "tablet" | "mobile"] // type string
};
=========================
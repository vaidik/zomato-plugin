

A web site that offers a search plugin can advertise it so that Firefox users can easily download and install the plugin.

===============================================================
Autodiscovery of OpenSearch Plugins for your website's search
===============================================================
To support autodiscovery, you simply need to add one line to the <head> section of your web page:
<link rel="search" type="application/opensearchdescription+xml" title="searchTitle" href="pluginURL">

searchTitle: The name of the search to perform, such as "Search MDC" or "Yahoo! Search". This value should match your plugin file's ShortName.

pluginURL: The URL to the XML search plugin, from which the browser can download it.

===============================================================
Automatic updates for OpenSearch plugins
===============================================================
Firefox supports automatic updates for OpenSearch plugins. Refer next section.

===============================================================
Further Reading
===============================================================
https://developer.mozilla.org/en/Creating_OpenSearch_plugins_for_Firefox

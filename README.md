Mine Inspector
==============

Based on the [Variable Inspector Widget](http://nbviewer.ipython.org/github/ipython/ipython/blob/2.x/examples/Interactive%20Widgets/Variable%20Inspector.ipynb)

1. Set the configurables:
* fqdn - the fully qualified domain name of the redmine server, e.g., redmine.foo.com, WITHOUT protocol (https:// is assumed)
* endpoint - the name of the collection you wish to retrieve from redmine; currently only supports issues or projects
* api_key - your Redmine API key
* limit - the number of items to retrieve; 25-100
* offset - where in the collection to begin retrieving items
2. Call get_endpoint_dictionary.
3. Run the widget code.  After the pop up/in window is visible, changes to the endpoint will automatically show up in the window (you must re-run the call to get_endpoint_dictionary).

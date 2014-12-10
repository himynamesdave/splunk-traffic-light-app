Splunk Traffic Light Visualisations
========================

A simple demo app showing you how to build traffic light visualisations into your Splunk app. What a bright idea!

These example use Splunk's "[rangemap](http://docs.splunk.com/Documentation/Splunk/6.2.0/SearchReference/Rangemap)" command to display traffic lights that alternate depending on the threshold level set within the search.

We use a "[single value](http://docs.splunk.com/Documentation/Splunk/6.2.0/Viz/Visualizationreference#Single-value_visualizations)" panel to display the output of the search using the default rangemap config.

In the stylesheet we attach the different traffic light images to the default rangemap classes.</p>

All images and CSS stored in:

`$SPLUNKAPP/appserver/static`

You'll also find .PSD files for traffic lights here:

`$SPLUNKAPP/static/raw-graphics`

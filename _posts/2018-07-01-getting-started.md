---
layout: post
title:  "Getting started"
date:   2018-07-01 14:21:16 +0200
permalink: getting-started
---
To use snapADDY Grabber & VisitReport in connection to your CRM system in the most convinient way a CRM mapping has to be done.

The CRM mapping consists of one .json file which determines the following settings:
- "meta": Information about how your entities are named
- "defaultExport": snapADDY Grabber mapping
- "visitreport": snapADDY Visitreport mapping
- "code": Contains JavaScript functions that can be called up in "mappings"

Inside defaultExport and visitreport there are 3 more blocks:
- "mappings": Determines the mapping between the fields available in snapADDY Grabber/VisitReport and the fields in your CRM system
- "workflows": Sets up the entities which are created at the export to your CRM system
- "components": Configures the appearance of the Export 2.0 view.

{% highlight javascript %}{% raw %}
{
    "integrations": {
        "salesforce": {
            "meta": {},
            "defaultExport": {
                "mappings": {},
                "workflows": {},
                "components": {}
            },
            "visitreport": {
                "mappings": {},
                "workflows": {},
                "components": {}
            },
            "code": {}
        }
    }
}
{% endraw %}{% endhighlight %}

You will find a mapping sample for each supported CRM system in ["Mapping Samples"](https://mapping.snapaddy.com/mapping-samples)

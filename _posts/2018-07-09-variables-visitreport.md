---
layout: post
title: "Variables: VisitReport"
date: 2018-07-09 14:21:18 +0200
permalink: variables-visitreport
---
This is a list of the available variables used in the VisitReport mapping.

| Variable                       | Behaviour                             |
|--------------------------------|---------------------------------------|
| {% raw %}"{{ _answers['QUESTIONID'] }}"{% endraw %} | The answer of the referenced question [(How to get IDs)](http://mapping.snapaddy.com/mappinghelper)
  |
| {% raw %}"{{ visitreport.title }}"{% endraw %} | The title of the template |
| {% raw %}"{{ visitreport.campaignId }}"{% endraw %} | The campaign ID entered in the template settings |
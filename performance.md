---

copyright:
  years: 2015, 2018
lastupdated: "2018-06-26"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# Viewing metrics and improving query results with the Performance dashboard
{: #performance}

See the [Discovery documentation ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/docs/services/discovery/index.html#about){: new_window} for more information about {{site.data.keyword.discoveryfull}}.

The Performance dashboard can be used to view query metrics, as well as improve query results, including query relevance.

You can access the Performance dashboard by clicking the **View data metrics** icon on the left. The dashboard is not available in Premium or Dedicated environments.

There are two options to improve natural language query results:
- [Fix queries with no results by adding more data](/docs/services/discovery-sf/dashboard.html#data)
- [Bring relevant results to the top by training your data](/docs/services/discovery-sf/dashboard.html#relevancy)

You can view the data metrics in the [query overview](/docs/services/discovery-sf/dashboard.html#overview). 

## Fix queries with no results by adding more data
{: #data}

In this section of the dashboard, you can review queries that returned zero results, and add more data so that query will return results in the future. Click the **View all and add data** button to get started. 

## Bring relevant results to the top by training your data
{: #relevancy}

In this section, you can train your collections to improve the relevance of natural language query results. Click the **View all and perform relevancy training** button to get started. Then see [Adding queries and rating the relevancy of results ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/docs/services/discovery/train-tooling.html#results){: new_window} for instructions.

For more about training requirements and options, see [Improving result relevance with the tooling ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/docs/services/discovery/train-tooling.html){: new_window}.

## Query overview
{: #overview}

The Query overview section displays:
- The total number of queries made by users
- The percentage of queries with one or more results clicked
- The percentage of queries with no results clicked
- The percentage of queries with no results returned
- A graph that displays these results over time, so that you can track how adding more data and relevancy training are improving performance

These results are gathered using the Events and Feedback API. See the [API reference ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/watson/developercloud/discovery/api/v1/curl.html?curl#events-and-feedback-api){: new_window} for more information.